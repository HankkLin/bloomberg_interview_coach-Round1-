# Bloomberg Interview Coach

A personal Codex skill for practicing LeetCode problems and AI-assisted codebase exercises one question at a time. It guides clarification, reasoning, implementation, complexity analysis, testing, and communication without revealing solutions upfront. It also covers when to ask the interviewer versus AI and optional follow-ups about latency, caching, databases, and the frontend.

## Install on another computer by pasting this link

Paste into Codex:

```text
Add https://github.com/HankkLin/bloomberg_interview_coach-Round1-.git to my skill set. Read its README and clone the repository directly into my personal skills directory as bloomberg-interview-coach. Keep the Git checkout so I can pull future updates. Do not install a copied snapshot.
```

The repository contains SKILL.md at its root. Clone it into the actual skill directory, rather than cloning elsewhere and copying files. The installed skill then is the Git checkout, so pulls update it directly. No symlink or additional installer script is needed.

Current Codex documentation uses `~/.agents/skills` for personal discovery. If your installed version uses `$CODEX_HOME/skills` or `~/.codex/skills`, have Codex choose its configured discovery location. Install only once to avoid duplicate skills.

Example for a setup using the current documented personal location:

```text
git clone https://github.com/HankkLin/bloomberg_interview_coach-Round1-.git ~/.agents/skills/bloomberg-interview-coach
```

If the destination already exists, preserve local changes and reconcile it before installing. Do not overwrite an existing skill blindly. For a prior copied installation, ask Codex to preserve its contents and migrate it to a Git checkout of this repository.

Codex detects skill changes automatically. If the skill or an update does not appear, restart Codex. See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills).

## Pull updates

In the installed skill directory:

```text
git pull --ff-only
```

No reinstall is required. A ZIP download or the default copied installation from $skill-installer has no Git history and cannot be updated with git pull. Use the clone-based installation above for ongoing synchronization.

## Edit and push updates

Open the installed repository in Codex and update `SKILL.md` (and `agents/openai.yaml` when needed). Review, commit, and push:

```text
git add SKILL.md agents/openai.yaml
git commit -m "Update interview coaching guidance"
git push
```

GitHub authentication and write access are required to push. This repository is public, so downloading does not require signing in. If Git reports local changes or a conflict during a pull, preserve and resolve those changes before continuing.

## Use

```text
Use $bloomberg-interview-coach to guide me through Two Sum one question at a time without giving me the answer.
```

## Contents

```text
README.md
SKILL.md
agents/openai.yaml
```

This is a personal preparation aid. Interview-format context comes from the [Bloomberg guide](https://bloomberg.pagetiger.com/chkubwh/1); follow-up topics reflect personal notes, not guaranteed interview questions. No API key or Python packages are required to use the skill.
