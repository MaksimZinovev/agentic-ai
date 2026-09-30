## Installing specific version of Python package

When to use: when you have any issues with installing the latest version of package, for example, when blocked ny safe chain.

```shell
To update, run: pip install --upgrade pip
ERROR: 403 Client Error: Forbidden - blocked by safe-chain direct download minimum package age (fastapi@0.142.1) for url: https://files.pythonhosted.org/packages/4d/17/bb503d4b3bea614eae48ffecafe192b097082e8afcf3f2dbde3d78438cc4/fastapi-0.142.1-py3-none-any.whl.metadata

Safe-chain: blocked 1 direct package download request(s) due to minimum package age:
 - fastapi@0.142.1 (https://files.pythonhosted.org/packages/4d/17/bb503d4b3bea614eae48ffecafe192b097082e8afcf3f2dbde3d78438cc4/fastapi-0.142.1-py3-none-any.whl.metadata)
  To disable this check, use: --safe-chain-skip-minimum-package-age

Safe-chain: Exiting without installing packages blocked by the direct download minimum package age check.
```

Usage example:

```shell
pip install "notebook<7.6.3"
```
