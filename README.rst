# aioquic-webtransport-patched

> ✅ A patched fork of [`aiortc/aioquic`](https://github.com/aiortc/aioquic) with support for **WebTransport** on top of QUIC, intended for use in projects that require full WebTransport handling (#).

---

## 📌 Purpose

This repository extends the official `aioquic` QUIC implementation with **WebTransport protocol support**, which is not yet officially available in the upstream.

The patch includes:
- `aioquic/webtransport/` module
- `WebTransportProtocol` class for datagram-based communication over QUIC
- Updated `setup.py` and `pyproject.toml` to ensure installability via `pip`
- Fully compatible with existing `aioquic.asyncio` and `aioquic.quic` modules

---

## 🔧 Installation

To install this patched version directly from GitHub:

```bash
pip install git+https://github.com/akshatshaha/aioquic-webtransport-patched.git@main
