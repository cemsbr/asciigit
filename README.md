# asciigit
ASCII-only ZSH prompt theme (using oh-my-zsh). For git users who are not fan of fancy glyphs. Features:
- Works well in terminal or console. No need to change your font!
- Git info:
  - Remote url, e.g. github.com/cemsbr/asciigit;
  - Relative path from git root dir;
  - Branch name;
  - Status (diverged, added, untracked, etc...).
- Colors known to work well with solarized light (probably with other schemes, too).

<img src="https://github.com/cemsbr/asciigit/blob/screenshot/screenshot.png" width="606" height="468">

## Install
Add to your ~/.zshrc:
```bash
antigen theme cemsbr/asciigit asciigit
```
