# Python Seed App

This is a simple skeleton for a generic Python (3.6.5) app. It comes loaded with:

- tox
- pytest
- pylint

As well a `.gitignore`, `.pylintrc` config file, and simple directory structure employing the `src` pattern.

## Testing

To find out more info about the testing configuration, check out the `tox.ini` file.

Run the test suite:

```
tox
```


Run the linter:

```
tox -e lint
```

## Misc Notes

- Make sure and edit the package title in `setup.py` to reflect your app name