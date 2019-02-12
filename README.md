# Brownie

Brownie is a python framework for deploying, testing and interacting with ethereum smart contracts.

## Dependencies

* [git](https://git-scm.com/)
* [pip](https://pypi.org/project/pip/)
* [python3.6](https://www.python.org/downloads/release/python-368/), python3.6-dev, python3.6-venv

As brownie relies on [py-solc-x](https://github.com/iamdefinitelyahuman/py-solc-x), you do not need solc installed locally but you must install all required [solc dependencies](https://solidity.readthedocs.io/en/latest/installing-solidity.html#binary-packages).

If you wish to run a local test environment you must also install an Ethereum client which supports the standard JSON RPC API. Brownie is designed to work with [ganache-cli](https://github.com/trufflesuite/ganache-cli), but you can easily change this by editing the ``brownie-config.json`` file in your project.

You may also wish to install [opview](https://github.com/iamdefinitelyahuman/opview) for test coverage visualization.

## Installation

Ubuntu:

```bash
curl https://raw.githubusercontent.com/iamdefinitelyahuman/brownie/master/brownie-install.sh | sh
```

## Quick Usage

To set up the default folder and file structure for brownie use:

```bash
brownie init
```

From there, type `brownie` for basic usage information.

## Documentation

Brownie documentation is hosted at [Read the Docs](https://eth-brownie.readthedocs.io/en/latest/).

## Development

This project is still in development and should be considered a beta. Comments, questions, criticisms and pull requests are welcomed.

## License

This project is licensed under the [MIT license](LICENSE).