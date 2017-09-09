## COMMENT-TAGS.el

An emacs package to highlight and list comment tags such as 'TODO', 'FIXME', 'BUG', 'XXX', 'HACK', 'KLUDGE'.

## Customizations
Ability to customize highlight colors and keywords list.

  * `comment-tags-keywords` to alter the list of highlighted/searched words.
  * `comment-tags-require-colon` to require a matching colon (default t).
  * `comment-tags-comment-start-only` to only match tags at the beginning of a comment (default nil).
  * `comment-tags-keymap-prefix` to alter the default prefix (default `C-c t`).
  * `comment-tags-case-sensitive` to toggle case-sensitivity (default t).
  * `comment-tags-foreground-color` to set default color for keywords (default red).
  * `comment-tags-background-color` to set default background color for keywords (default nil).
  * `comment-tags-keyword-colors` to alter colors for keywords.

## Usage
The prefix for commands is `C-c t`.

Commands include:
  * `b` to list tags in current buffer.
  * `a` to list tags in all buffers.
  * `s` to jump to tag in current buffer by a word or phrase using reading-completion.

## TODO:
  * Filter tags in all buffers with search of comment text.
  * Issues here: https://github.com/vincekd/comment-tags/issues


## Screenshots

List tags in buffer and select to jump to point.
![screenshot](screenshots/buffer-list.png)

Search tags in buffer (with search of line text) and jump to point.
![screenshot](screenshots/buffer-search.png)
