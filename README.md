# devcodes9/homebrew-tap

Homebrew formulae for [devcodes9](https://github.com/devcodes9) tools.

```sh
brew install devcodes9/tap/agsearch
```

## Formulae

| Formula | What |
|---|---|
| [`agsearch`](https://github.com/devcodes9/agsearch) | Search every Claude Code and Codex CLI session by what was said in it, then resume it |

## Why a tap and not homebrew-core

Homebrew's notability audit only fails a repository when it is below **all three**
of 30 forks, 30 watchers and 75 stars (tripled if you submit your own repo).
agsearch is not there yet, and the audit is skipped entirely for taps.

If it ever clears one of those, the formula moves to homebrew-core and this tap
goes away: Homebrew's own bot takes over the version bumps.

## Maintenance

`Formula/agsearch.rb` is a copy. The source of truth lives at
[`packaging/agsearch.rb`](https://github.com/devcodes9/agsearch/blob/main/packaging/agsearch.rb)
in the agsearch repo, and `bump-tap.yml` there opens the version + sha256 bump
here when a release is published.
