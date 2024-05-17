# Role Name

Infrastructure role.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## License

MIT

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -e .
```

## Contribute

First, run :

```bash
pip install -e .'[dev]'
pre-commit install
pre-commit run --all-files
```

You'll need to install `tflint` and `trivy`.
