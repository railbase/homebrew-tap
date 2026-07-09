# railbase/homebrew-tap

Homebrew tap for [Railbase](https://railbase.app) — a single-file enterprise backend.

## Install

```sh
brew install railbase/tap/railbase
```

or

```sh
brew tap railbase/tap
brew install railbase
```

The macOS build is signed and notarized (Silkway Tech LLC), so it runs with no
Gatekeeper prompt. This tap holds only the formula (the recipe) — **no source and
no binary**; `brew` downloads the release binary from <https://railbase.app/dl>.
The formula is regenerated on every release by `scripts/brew-formula.sh` in the
core repo.
