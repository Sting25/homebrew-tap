# homebrew-tap

Homebrew tap for [ai-coding-rules-scaffold](https://github.com/Sting25/ai-coding-rules-scaffold)
— agent-agnostic pre-commit + CI guardrails (file size, forbidden patterns,
secret/credential scanning, hygiene) you install into your own repo.

## Install

```sh
brew install sting25/tap/ai-coding-rules-scaffold
```

Then, from your project's root:

```sh
ai-coding-rules-scaffold            # auto-detects Python / JS
ai-coding-rules-scaffold --both     # or pick the stack explicitly
ai-coding-rules-scaffold --help     # all flags
```

## Updating the formula on a new release

The formula's `url` (tag) + `sha256` are bumped per release — see
[RELEASING.md](https://github.com/Sting25/ai-coding-rules-scaffold/blob/main/RELEASING.md)
in the main repo. The canonical formula source lives there under
`packaging/homebrew/`; this tap holds the published copy.
