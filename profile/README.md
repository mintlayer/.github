# Mintlayer Projects

Welcome to the central hub for [Mintlayer](https://www.mintlayer.org) projects. Here you'll find links to our primary repositories hosted on our GitHub instance.

## Documentation

Comprehensive documentation for users, operators, and developers lives at **[docs.mintlayer.org](https://docs.mintlayer.org)**:

- [Getting Started](https://docs.mintlayer.org/docs/getting-started): how a Mintlayer node and wallet fit together, and your first commands
- [Install a Mintlayer node](https://docs.mintlayer.org/docs/getting-started/install): native deb/rpm packages, binaries, Docker, one-command web GUI installer, or from source
- [Use the Mintlayer GUI](https://docs.mintlayer.org/docs/getting-started/install/install-web-gui): a full node with wallet and web interface in Docker
- [Wallet CLI reference](https://docs.mintlayer.org/docs/wallet/cli/commands): every `wallet-cli` command, each with its own page
- [Learn how to stake](https://docs.mintlayer.org/docs/guides/cli/managing-a-staking-pool): run a staking pool or delegate, on testnet and mainnet
- [API reference](https://docs.mintlayer.org/docs/api): the indexer REST API behind explorers and wallets
- [SDK guides and reference](https://docs.mintlayer.org/docs/build/sdks/go): Go, JavaScript, Rust, and Python
- [Whitepaper](https://docs.mintlayer.org/docs/whitepaper/blockchain-architecture): the architecture, tokenization standard, and DEX design

For AI agents and LLM-based tooling, a machine-readable index of the whole site is available at [docs.mintlayer.org/llms.txt](https://docs.mintlayer.org/llms.txt).

## Repositories

### [Mintlayer Core](https://github.com/mintlayer/mintlayer-core)

The heart of our operation: the node daemon, wallet daemons, blockchain scanner, and DNS seed server. Dive in to understand the backbone of the system.

### [Mojito Mobile Wallet (iOS & Android)](https://github.com/mintlayer/mojito_mobile_wallet)

Discover Mojito, our non-custodial mobile wallet for both iOS and Android. Stay connected and manage your assets on the go.

### [Mojito Browser Extension](https://github.com/mintlayer/mojito-browser-extension)

The Mojito wallet as a browser extension, compatible with Chrome, Firefox, and Edge. It injects a `window.mojito` provider so dApps can request accounts and signatures; see the [dApp integration guide](https://docs.mintlayer.org/docs/build/mojito-inject).

### [Block Explorer](https://github.com/mintlayer/explorer)

The block explorer running at [explorer.mintlayer.org](https://explorer.mintlayer.org).

### SDKs

Official SDKs for building on Mintlayer, each with guides and a full API reference in the documentation:

| Language | Repository | Documentation |
| -------- | ---------- | ------------- |
| Go | [go-sdk](https://github.com/mintlayer/go-sdk) | [docs](https://docs.mintlayer.org/docs/build/sdks/go) |
| JavaScript | [mintlayer-connect-sdk](https://github.com/mintlayer/mintlayer-connect-sdk) | [docs](https://docs.mintlayer.org/docs/build/sdks/javascript) |
| Rust | [rust-sdk](https://github.com/mintlayer/rust-sdk) | [docs](https://docs.mintlayer.org/docs/build/sdks/rust) |
| Python | [python-sdk](https://github.com/mintlayer/python-sdk) | [docs](https://docs.mintlayer.org/docs/build/sdks/python) |

### [Mintlayer Web-GUI](https://github.com/mintlayer/web-gui)

A full node with a graphical interface, deployed in Docker. Install it with one command from [get.mintlayer.org](https://get.mintlayer.org).

### [ZK Thunder Network](https://github.com/mintlayer/zk-thunder) (Testnet)

A ZK rollup implementation built on top of Mintlayer.

## Contributions

We welcome and appreciate contributions! Please refer to individual repositories for guidelines and details on the contribution process.

## Report a Bug

Encountered an issue? Report non-security related bugs by [opening an issue](https://github.com/mintlayer/mintlayer-core/issues/new) in the core Mintlayer repository. Provide as much detail as possible to help us understand and resolve the issue promptly. For security-related issues, refer to the [security policy](https://github.com/mintlayer/mintlayer-core/blob/master/SECURITY.md).

## License

Please see the `LICENSE` file in individual repositories for details on usage rights and restrictions.

---

Thank you for your interest in Mintlayer. Together, we're pioneering the future of digital assets on the blockchain.
