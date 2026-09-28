# Markdown Viewer

A single-page tool for reading, editing and formatting Markdown files in the browser. No build step and no server: everything runs from `index.html`.

## Features

- **Three views**: Read (with heading outline), Split (editor + live preview with synced scrolling), Source.
- **Visual formatting**: the toolbar applies to whichever side you last clicked. In the editor it writes Markdown syntax; in the preview you edit the rendered page directly and the Markdown updates to match.
- **Typography panel**: serif / sans / kai typefaces, font size, line height, characters per line, paragraph spacing, heading scale, justification, first-line indent, and a manuscript grid overlay.
- **Files**: open or drag in `.md` / `.txt`, download the edited `.md`, or export the typeset result as a standalone `.html`.
- Drafts are auto-saved in your browser (localStorage).

## Shortcuts

| Action | Windows | macOS |
| --- | --- | --- |
| Bold | Ctrl + B | ⌘ + B |
| Italic | Ctrl + I | ⌘ + I |
| Link | Ctrl + K | ⌘ + K |
| Heading 1–3 | Ctrl + Alt + 1–3 | ⌘ + ⌥ + 1–3 |
| Download .md | Ctrl + S | ⌘ + S |

## Run locally

Open `index.html` in a browser, or serve the folder with any static server.

## Libraries

[marked](https://github.com/markedjs/marked), [DOMPurify](https://github.com/cure53/DOMPurify), [Turndown](https://github.com/mixmark-io/turndown) and [turndown-plugin-gfm](https://github.com/mixmark-io/turndown-plugin-gfm), loaded from jsDelivr. Fonts from Google Fonts.
