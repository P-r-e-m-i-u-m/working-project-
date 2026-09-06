# Contributing to Build Origin

Thanks for taking a look.

This repo is meant to stay practical and easy to contribute to. You do not need a huge setup or a perfect PR.

## Before you start

If the change is more than a tiny fix, opening an issue first is a good way to make sure we're solving the same problem.

For small fixes, you can go straight to a pull request.

## A simple workflow

```bash
git clone https://github.com/P-r-e-m-i-u-m/build-origin.git
cd build-origin

git checkout -b fix/short-description
```

Make the change, check it, then:

```bash
git add .
git commit -m "fix: describe the change"
git push origin fix/short-description
```

Open a pull request on GitHub.

## Keep PRs focused

A good PR usually does one thing well.

- Explain what changed.
- Explain why it changed when the reason is not obvious.
- Keep unrelated cleanup out of the same PR.
- Use a clear title.
- Test anything that can reasonably be tested.

## Commit style

There is no need to overthink commits, but a short conventional prefix keeps the history readable:

```text
feat: add ...
fix: correct ...
docs: update ...
refactor: simplify ...
chore: update ...
```

## The main rule

Be useful, be respectful, and leave the code or documentation a little better than you found it.
