# Build TorchData Release

These are a collection of scripts that are to be used for release activities.

## Conda

### Official Release

```bash
PYTHON_VERSION=3.9 PYTORCH_VERSION=1.11.0 packaging/biuld_conda.sh
```

### Nightly

```bash
PYTHON_VERSION=3.9 packaging/biuld_conda.sh
```

## Wheel

### Official Release

```bash
PYTHON_VERSION=3.9 PYTORCH_VERSION=1.11.0 packaging/biuld_wheel.sh
```

### Nightly

```bash
PYTHON_VERSION=3.9 packaging/biuld_wheel.sh
```
