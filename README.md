# Bomberman — C64 Edition

A single-file HTML5 Bomberman, styled after the Commodore 64 original.

**▶ Play: https://businessintelligence-lab.github.io/bomberman-c64/**

## About this repo

This repo is a **deploy target**, not where the game is developed. It holds
exactly one artifact — `index.html` — published from the private source repo's
`origin/main` by `deploy-bomberman.sh`.

It was created with a fresh, unrelated git history on purpose: the source repo
also contains unrelated private work, and pushing a branch from there would
carry that entire history into a public repo.

Every commit here records the source commit it came from, so anything playable
at the URL above is guaranteed to exist on the source repo's `main` — which is
the whole point of deploying rather than opening a local file to test.
