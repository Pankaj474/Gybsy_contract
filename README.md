# Gybsy Program Library

Gybsy smart contracts and SDK.

## Development

### Versioning and Publishing Packages

Smart contract SDK packages are versioned independently since a contract isn't necessarily coupled
to other contracts.

In order to version and then publish a package just run the following commands from the folder of
the package you want to update:

- `npm version <patch|minor|major>`
- `npm publish`

As you note if version + publish succeeds the scripts end up pushing those updates to the master
branch. Therefore please ensure to be on and up to date `master` branch before running them. Please
**don't ever publish from another branch** but only from the main one with only PR approved changes
merged.

### Rust Crates

| Package        | Link                                                         | Version                                                      |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Candy Machine  | [mpl-candy-machine](https://crates.io/crates/mpl-candy-machine) | [![Crate](https://img.shields.io/crates/v/mpl-candy-machine)](https://crates.io/crates/mpl-candy-machine) |
| Token Metadata | [mpl-token-metadata](https://crates.io/crates/mpl-token-metadata) | [![Crate](https://img.shields.io/crates/v/mpl-token-metadata)](https://crates.io/crates/mpl-token-metadata)                                                             |
| Token Vault    | [mpl-token-vault](https://crates.io/crates/mpl-token-vault)  |  [![Crate](https://img.shields.io/crates/v/mpl-token-vault)](https://crates.io/crates/mpl-token-vault)                                                            |


## Reporting security issues

To report a security issue, please follow the guidance on the [SECURITY](.github/SECURITY.md) page.
