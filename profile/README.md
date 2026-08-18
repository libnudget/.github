<div align="center">

# libnudget

**small tools, plainly made**

[libnudget.github.io](https://libnudget.github.io)

</div>

```mermaid
classDiagram
    direction TB

    class Palmshed {
        AI tools
        Agents
        SDKs
    }

    class harpertoken {
        Software
    }

    class libnudget {
        Utilities
        Actions
        Libraries
        Templates
    }

    Palmshed --> libnudget
    harpertoken --> libnudget
```

[Palmshed](https://github.com/palmshed) · [harpertoken](https://github.com/harpertoken) · [libnudget](https://github.com/libnudget)

## Projects

### Released

| Tool                                                          | Latest                                                                                                                                                   | Use it                                                                     |
| ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [clipb](https://github.com/libnudget/clipb)                   | [![clipb](https://img.shields.io/github/v/release/libnudget/clipb?label=latest)](https://github.com/libnudget/clipb/releases)                            | `cargo install --git https://github.com/libnudget/clipb`                   |
| [craft](https://github.com/libnudget/craft)                   | [![craft](https://img.shields.io/github/v/release/libnudget/craft?label=latest)](https://github.com/libnudget/craft/releases)                            | `cargo install --git https://github.com/libnudget/craft`                   |
| [mini](https://github.com/libnudget/mini)                     | [![mini](https://img.shields.io/github/v/release/libnudget/mini?label=latest)](https://github.com/libnudget/mini/releases)                               | `go get github.com/libnudget/mini@latest`                                  |
| [startkit](https://github.com/libnudget/startkit)             | [![startkit](https://img.shields.io/github/v/release/libnudget/startkit?label=latest)](https://github.com/libnudget/startkit/releases)                   | `npx --yes github:libnudget/startkit mylib`                                |
| [dotenv-keep](https://github.com/libnudget/dotenv-keep)       | [![dotenv-keep](https://img.shields.io/github/v/release/libnudget/dotenv-keep?label=latest)](https://github.com/libnudget/dotenv-keep/releases)          | `pip install git+https://github.com/libnudget/dotenv-keep`                 |
| [release-notes](https://github.com/libnudget/release-notes)   | [![release-notes](https://img.shields.io/github/v/release/libnudget/release-notes?label=latest)](https://github.com/libnudget/release-notes/releases)    | `uses: libnudget/release-notes@main`                                       |
| [gh-tag](https://github.com/libnudget/gh-tag)                 | [![gh-tag](https://img.shields.io/github/v/release/libnudget/gh-tag?label=latest)](https://github.com/libnudget/gh-tag/releases)                         | `uses: libnudget/gh-tag@main`                                              |
| [fmtcheck](https://github.com/libnudget/fmtcheck)             | [![fmtcheck](https://img.shields.io/github/v/release/libnudget/fmtcheck?label=latest)](https://github.com/libnudget/fmtcheck/releases)                   | `uses: libnudget/fmtcheck@main`                                            |
| [bump](https://github.com/libnudget/bump)                     | [![bump](https://img.shields.io/github/v/release/libnudget/bump?label=latest)](https://github.com/libnudget/bump/releases)                               | `uses: libnudget/bump@main`                                                |
| [echo](https://github.com/libnudget/echo)                     | [![echo](https://img.shields.io/github/v/release/libnudget/echo?label=latest)](https://github.com/libnudget/echo/releases)                               | `uses: libnudget/echo@main`                                                |
| [gon](https://github.com/libnudget/gon)                       | [![gon](https://img.shields.io/github/v/release/libnudget/gon?label=latest)](https://github.com/libnudget/gon/releases)                                  | `uses: libnudget/gon/.github/workflows/gon.yml@main`                       |
| [nightly](https://github.com/libnudget/nightly)               | [![nightly](https://img.shields.io/github/v/release/libnudget/nightly?label=latest)](https://github.com/libnudget/nightly/releases)                      | `uses: libnudget/nightly/.github/workflows/nightly.yml@main`               |
| [release-assets](https://github.com/libnudget/release-assets) | [![release-assets](https://img.shields.io/github/v/release/libnudget/release-assets?label=latest)](https://github.com/libnudget/release-assets/releases) | `uses: libnudget/release-assets/.github/workflows/release-assets.yml@main` |
| [rust-nightly](https://github.com/libnudget/rust-nightly)     | [![rust-nightly](https://img.shields.io/github/v/release/libnudget/rust-nightly?label=latest)](https://github.com/libnudget/rust-nightly/releases)       | `uses: libnudget/rust-nightly/.github/workflows/nightly.yml@main`          |
| [activity](https://github.com/libnudget/activity)             | [![activity](https://img.shields.io/github/v/release/libnudget/activity?label=latest)](https://github.com/libnudget/activity/releases)                   | `uses: libnudget/activity/.github/workflows/tracking.yml@main`             |
| [release](https://github.com/libnudget/release)               | [![release](https://img.shields.io/github/v/release/libnudget/release?label=latest)](https://github.com/libnudget/release/releases)                      | `uses: libnudget/release@v1.0.0`                                           |
| [auto-label](https://github.com/libnudget/auto-label)         | [![auto-label](https://img.shields.io/github/v/release/libnudget/auto-label?label=latest)](https://github.com/libnudget/auto-label/releases)             | `uses: libnudget/auto-label@v2`                                            |
| [auto-merge](https://github.com/libnudget/auto-merge)         | [![auto-merge](https://img.shields.io/github/v/release/libnudget/auto-merge?label=latest)](https://github.com/libnudget/auto-merge/releases)             | `uses: libnudget/auto-merge@v1`                                            |
| [bot](https://github.com/libnudget/bot)                       | [![bot](https://img.shields.io/github/v/release/libnudget/bot?label=latest)](https://github.com/libnudget/bot/releases)                                  | `uses: libnudget/bot/actions/commit@v1`                                    |
| [cancel](https://github.com/libnudget/cancel)                 | [![cancel](https://img.shields.io/github/v/release/libnudget/cancel?label=latest)](https://github.com/libnudget/cancel/releases)                         | `uses: libnudget/cancel@v1`                                                |
| [lock](https://github.com/libnudget/lock)                     | [![lock](https://img.shields.io/github/v/release/libnudget/lock?label=latest)](https://github.com/libnudget/lock/releases)                               | `uses: libnudget/lock@v1`                                                  |
| [prune](https://github.com/libnudget/prune)                   | [![prune](https://img.shields.io/github/v/release/libnudget/prune?label=latest)](https://github.com/libnudget/prune/releases)                            | `uses: libnudget/prune@v1`                                                 |
| [rust-fix](https://github.com/libnudget/rust-fix)             | [![rust-fix](https://img.shields.io/github/v/release/libnudget/rust-fix?label=latest)](https://github.com/libnudget/rust-fix/releases)                   | `uses: libnudget/rust-fix@v1`                                              |
| [stale](https://github.com/libnudget/stale)                   | [![stale](https://img.shields.io/github/v/release/libnudget/stale?label=latest)](https://github.com/libnudget/stale/releases)                            | `uses: libnudget/stale@v1`                                                 |
| [title](https://github.com/libnudget/title)                   | [![title](https://img.shields.io/github/v/release/libnudget/title?label=latest)](https://github.com/libnudget/title/releases)                            | `uses: libnudget/title@v1`                                                 |
