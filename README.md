# TaPas for Poe

This is a modified version for incorporating TaPas with Poe. For the original instructions of TaPas, please refer to [README0.md](./README0.md).

## Installation

The repository uses protocol buffers, and requires the `protoc` compiler to run.
You can download the latest binary for your OS [here](https://github.com/protocolbuffers/protobuf/releases).
On Ubuntu/Debian, it can be installed with:

```bash
sudo apt-get install protobuf-compiler
```

Afterwards, clone and install the git repository:

```bash
cd tapas4poe
pip install -e .
```

To run the test suite we use the [tox](https://tox.readthedocs.io/en/latest/) library which can be run by calling:

```bash
pip install tox
tox
```
