# vscode-erde

VSCode language extension for the Erde programming language. See CHANGELOG.md
for version changes.

## Features

- [x] Syntax highlighting
- [x] Bracket matching
- [x] Bracket autoclosing
- [x] Bracket autosurrounding
- [x] Comment toggling
- [x] Auto indentation
- [ ] Folding
- [ ] Semantic Highlighting?

## Shortcomings

Due to limitations with [TextMate grammars](https://macromates.com/manual/en/language_grammars), there are a couple of shortcomings with the current syntax highlighting:

- `catch` name or destructure must happen on the same line as the `catch` keyword itself.
- Arrow function params must happen on the same line as the arrow token (`->`, `=>`).

Please feel free to open an issue if there are any other problems or if you think you have a solution to any of the above!
