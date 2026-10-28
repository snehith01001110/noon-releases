# Atlas

Run coding agents side by side, and see where they're working.

Atlas runs Claude Code and Codex on your local projects. Each task gets its
own Git workspace and branch, so several agents can work at once; you follow
each task's changes and nothing reaches your project's branch until you merge
it. A live map of your code shows each agent on the part it's reading or
editing.

**[Download Atlas for Mac](https://github.com/snehith01001110/atlas-releases/releases/latest/download/Atlas.zip)**
· [thenoonlight.com/atlas](https://thenoonlight.com/atlas)
· [all releases](https://github.com/snehith01001110/atlas-releases/releases)

This repository only hosts Atlas's downloads; the source code isn't public.

## What you need

- A Mac with Apple silicon and macOS 27 or later.
- Apple's Command Line Tools, for Git. Atlas offers to install them.
- Claude Code, or Codex 0.160.0 or later, installed and signed in. Atlas
  uses your existing accounts.

## Install

1. Download `Atlas.zip` from the latest release and open it.
2. Move Atlas to your Applications folder, then open it.
3. Add a Git repository and start a task. Help is in the app's Help menu.

Each release lists the ZIP's SHA-256 checksum. To check it:
`shasum -a 256 ~/Downloads/Atlas.zip`

Atlas doesn't update itself; new versions are posted here.

## Support

Questions or problems: snehithn5@gmail.com. Include your Atlas, macOS and
agent versions and what happened; Help → Reveal Logs shows a log you can
attach.

## License

Atlas is free to use; copyright © 2026 Snehith Nayak, all rights reserved.
It's provided as is, without warranty of any kind. See [LICENSE](LICENSE).
