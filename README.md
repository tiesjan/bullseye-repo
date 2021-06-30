# Debian 11 Bullseye software repository

## Installation

1. Add GPG signing key:

   ```bash
   wget -O - http://software.tiesjan.com/signing-key.gpg | sudo apt-key add -
   ```

2. Add APT source:

   ```bash
   echo "deb http://software.tiesjan.com/deb bullseye main" | sudo tee /etc/apt/sources.list.d/tiesjan-software.list
   ```

## Available software
- **libappindicator3-1** (0.5-1): a transitional package to ease upgrades to
  [**libayatana-appindicator3-1**][package-details], available in Debian 11
  Bullseye's software repositories.


---

_[Find the repository source here.][repo-source]_


[package-details]: https://packages.debian.org/bullseye/libayatana-appindicator3-1
[repo-source]: https://github.com/tiesjan/bullseye-repo
