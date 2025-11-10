# Protocubo's Rust Crate Audits

Protocubo uses [cargo-vet](https://mozilla.github.io/cargo-vet/) to ensure
third-party Rust dependencies have been audited by Protocubo or another trusted
entity.

This repository automatically
[aggregates](https://mozilla.github.io/cargo-vet/multiple-repositories.html)
Protocubo's audits from various repositories to make them easily reusable by
others.

To import Protocubo's audits into another cargo-vet instance, add the following
lines to your `config.toml`:

```
[imports.jonasmalacofilho]
url = "https://raw.githubusercontent.com/protocubo/supply-chain/main/audits.toml"
```
