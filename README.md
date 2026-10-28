# Noon

Run coding agents side by side, and see where they're working.

Noon runs Claude Code and Codex on your local projects. Each task gets its
own Git workspace and branch, so several agents can work at once; you follow
each task's changes and nothing reaches your project's branch until you merge
it. A live map of your code shows each agent on the part it's reading or
editing.

**[Download Noon for Mac](https://github.com/snehith01001110/noon-releases/releases/latest/download/Noon.zip)**
· [thenoonlight.com](https://thenoonlight.com)
· [all releases](https://github.com/snehith01001110/noon-releases/releases)

This repository only hosts Noon's downloads; the source code isn't public.

## What you need

- A Mac with Apple silicon and macOS 27 or later.
- Apple's Command Line Tools, for Git. Noon offers to install them.
- Claude Code, or Codex 0.160.0 or later, installed and signed in. Noon
  uses your existing accounts.

## Install

1. Download `Noon.zip` from the latest release and open it.
2. Move Noon to your Applications folder, then open it.
3. Add a Git repository and start a task. Help is in the app's Help menu.

Each release lists the ZIP's SHA-256 checksum. To check it:
`shasum -a 256 ~/Downloads/Noon.zip`

Noon doesn't update itself; new versions are posted here.

## Support

Questions or problems: snehithn5@gmail.com. Include your Noon, macOS and
agent versions and what happened; Help → Reveal Logs shows a log you can
attach.

## License

Noon is free to use; copyright © 2026 Snehith Nayak, all rights reserved.
It's provided as is, without warranty of any kind. See [LICENSE](LICENSE).
