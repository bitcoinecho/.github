# Bitcoin Echo

> Build once. Build right. Stop.

A complete Bitcoin implementation in pure C—built for permanence, not continued development. Upon completion and audit, the codebase freezes. No version 2.0. No roadmap beyond completion.

## 🎯 The Mission

Bitcoin Echo is a faithful implementation of the Bitcoin protocol—designed to freeze forever. The rules are stable. Why shouldn't the software be?

## 📊 What's Built

- ✅ **Cryptographic primitives** — SHA-256, RIPEMD-160, secp256k1, Schnorr signatures
- ✅ **Consensus engine** — Full transaction & block validation (SegWit, Taproot)
- ✅ **Storage layer** — UTXO database, block storage, chain state management
- ✅ **Protocol layer** — P2P networking, mempool, transaction relay
- ✅ **Application layer** — JSON-RPC server, observer mode
- ✅ **Live GUI** — Real-time visualization of Bitcoin network activity
- 🔨 **In development** — Mining interface, full node mode

**Comprehensive test coverage** | **~20,000 lines of C** | **Zero dependencies**

## 🔗 Links

- 🌐 **Website:** [bitcoinecho.org](https://bitcoinecho.org)
- 📄 **Whitepaper:** [Technical Specification](https://bitcoinecho.org/docs/whitepaper)
- 📜 **Manifesto:** [Why Permanence Matters](https://bitcoinecho.org/docs/manifesto)
- 🐦 **X/Twitter:** [@bitcoinechoorg](https://twitter.com/bitcoinechoorg)
- 💰 **Funding:** [Support the Mission](https://bitcoinecho.org/funding)

## 🚀 Try Observer Mode

Watch Bitcoin mainnet live, right now (macOS/Linux):

### Quick Start (see live output)

```bash
# Clone and build the node
git clone https://github.com/bitcoinecho/bitcoin-echo
cd bitcoin-echo && make
./echo --observe
```

Your terminal will show live connection logs as the node connects to Bitcoin peers. Press **Ctrl+C** to stop.

### Start the GUI

In another terminal:

```bash
# Clone and run the web interface
git clone https://github.com/bitcoinecho/bitcoinecho-gui
cd bitcoinecho-gui && npm install && npm run dev
# Visit http://localhost:5173
```

### Running in Background (optional)

If you prefer the node to run silently in the background:

```bash
./echo --observe > /dev/null 2>&1 &
```

To stop the background process:

```bash
pkill -f "echo --observe"
```

> **Note:** Windows support is in active development. Current instructions are for macOS and Linux.

## 📚 Repositories

| Repo | Description |
|------|-------------|
| [bitcoin-echo](https://github.com/bitcoinecho/bitcoin-echo) | Core C implementation (the ossified artifact) |
| [bitcoinecho-gui](https://github.com/bitcoinecho/bitcoinecho-gui) | Web interface (can evolve) |
| [bitcoinecho-org](https://github.com/bitcoinecho/bitcoinecho-org) | Website, docs, whitepaper, roadmap |
| [.github](https://github.com/bitcoinecho/.github) | Organization profile (this page!) |

## 💡 Philosophy

**The rules are stable. The software is not.**

Bitcoin's consensus rules haven't changed since 2008. But the software implementing them never stops changing. Every update is a risk. Every refactor is a chance for divergence.

What if we built software the way Bitcoin builds its chain? Append-only. Immutable. Final.

---

*Bitcoin Echo: The Last Implementation*
