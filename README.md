<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.svg">
  <img src=".github/assets/banner-light.svg" width="880" alt="pam-native-php: The PAM Native 1.0.36 Composer distribution. Development continues in pam-native.">
</picture>

**Use [push-in/pam-native](https://github.com/push-in/pam-native): it is where PAM Native is developed and released.**<br>
This repository was the immutable Composer release split of the PAM Native PHP SDK; its last split is 1.0.36. Packagist's `pushinbr/pam-native` now resolves from push-in/pam-native, which ships the newer releases.

![PHP 8.5](https://img.shields.io/badge/php-8.5-777bb4)
[![License](https://img.shields.io/github/license/push-in/pam-native-php?color=1f6feb)](LICENSE)

[Install](#install) · [Contents](#contents) · [Docs](#docs) · [Canonical repository](https://github.com/push-in/pam-native)

</div>

<a id="install"></a>
## <picture><img src=".github/assets/icons/terminal.svg" width="22" height="22" alt=""></picture> Install

Create a PAM Native project with the current SDK:

```sh
pam init my-app --template native
cd my-app
pam doctor --fix
pam dev
```

`pam init --template native` already requires `pushinbr/pam-native` (`^1.0`). See the [PAM Native README](https://github.com/push-in/pam-native#readme).

<a id="platform-support"></a>
## <picture><img src=".github/assets/icons/grid.svg" width="22" height="22" alt=""></picture> Platform support

| Platform | Support | Notes |
| --- | --- | --- |
| Android, iOS | Through push-in/pam-native | See the [PAM Native platform support](https://github.com/push-in/pam-native#readme) |
| PHP | 8.5+ | From `composer.json` |

<a id="contents"></a>
## <picture><img src=".github/assets/icons/box.svg" width="22" height="22" alt=""></picture> What is in this repository

The PHP SDK as split for the 1.0.36 release: `src/`, `resources/`, `bin/`, `tests/`, `benchmarks/` and [PROTOCOL.md](PROTOCOL.md). The README of that distribution (repository ownership, first application walk-through, HTTP) is preserved verbatim in **[docs/distribution-readme.md](docs/distribution-readme.md)**; nothing was removed.

Source, roadmap, architecture, issues, security reports and contributions live in [push-in/pam-native](https://github.com/push-in/pam-native).

<a id="docs"></a>
## <picture><img src=".github/assets/icons/book.svg" width="22" height="22" alt=""></picture> Docs

- [Previous README (1.0.36 distribution)](docs/distribution-readme.md)
- [PAM Native (canonical repository)](https://github.com/push-in/pam-native)
- [PAM Native overview](https://push-in.github.io/pam-docs/native/overview/)
- [Protocol](PROTOCOL.md)

<a id="pam-ecosystem"></a>
## <picture><img src=".github/assets/icons/plug.svg" width="22" height="22" alt=""></picture> Part of the PAM ecosystem

<p align="center"><picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/pam-wordmark-dark.svg">
  <img src=".github/assets/pam-wordmark-light.svg" height="56" alt="PAM">
</picture></p>

PAM runs PHP natively on servers, desktops and phones. This repository is one piece of it.

| [**PAM**](https://github.com/push-in/pam) | [**PAM Desktop**](https://github.com/push-in/pam-desktop) | [**PAM Native**](https://github.com/push-in/pam-native) | [**Ecosystem**](https://github.com/push-in/pam#ecosystem) |
| --- | --- | --- | --- |
| the runtime and CLI | native desktop apps in PHP | native Android and iOS apps in PHP | every official package and plugin |

<sub>Docs: [push-in.github.io/pam-docs](https://push-in.github.io/pam-docs/introduction/) · [Issues](https://github.com/push-in/pam-native-php/issues)</sub>

<p align="center"><sub><a href="LICENSE">Apache License 2.0</a> · Made in Brazil by Pushin</sub></p>
