# homebrew-tap

[Homebrew](https://brew.sh) tap for [@ianaya89](https://github.com/ianaya89)'s tools.

## Usage

Install a package directly:

```sh
brew install ianaya89/tap/<package>
```

Or add the tap once, then install by name:

```sh
brew tap ianaya89/tap
brew install <package>
```

## Available packages

| Package | Description | Source |
| --- | --- | --- |
| [`etui`](Casks/etui.rb) | Terminal UI for browsing and managing etcd clusters | [ianaya89/etui](https://github.com/ianaya89/etui) |
| [`pad`](Casks/pad.rb) | Tabbed terminal scratchpad (macOS cask) | [ianaya89/scratchpad](https://github.com/ianaya89/scratchpad) |
| [`remind`](Casks/remind.rb) | Terminal reminders with OS + phone notifications | [ianaya89/remind](https://github.com/ianaya89/remind) |
| [`termiedos`](Casks/termiedos.rb) | Live football scores, standings & fixtures in your terminal (promiedos) | [ianaya89/termiedos](https://github.com/ianaya89/termiedos) |

## Updating

```sh
brew update
brew upgrade <package>
```

Casks here are generated automatically on each release by
[GoReleaser](https://goreleaser.com) — edit them in the source repo, not here.
