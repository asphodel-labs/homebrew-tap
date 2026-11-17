# asphodel-labs Homebrew tap

This tap holds the Homebrew casks of the asphodel-labs tools.

## Install

```fish
brew install asphodel-labs/tap/argus
```

You can also add the tap first and then install by name:

```fish
brew tap asphodel-labs/tap
brew install argus
```

## Casks

| Cask | Description |
|---|---|
| [argus](https://github.com/asphodel-labs/argus) | Terminal UI for the GitHub pull requests that concern you. |

## Updates

Do not edit the files in `Casks/` by hand.
The release workflow of each tool writes its cask with GoReleaser when a version tag is pushed.
