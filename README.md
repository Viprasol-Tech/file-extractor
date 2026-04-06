# File Extractor

Extract archives (zip, tar, gz)

## Features

- Zero external dependencies (stdlib only)
- Easy-to-use CLI interface
- Professional Python implementation
- MIT licensed

## Installation

```bash
pip install -e .
```

Or clone and install:

```bash
git clone https://github.com/Viprasol-Tech/file-extractor
cd file-extractor
pip install -e .
```

## Usage

### Python

```python
from file_extractor import FileExtractor

result = FileExtractor.process("data")
print(result)
```

### CLI

```bash
python -m file_extractor "your input here"
```

## Documentation

See the source code and docstrings for detailed API documentation.

## License

MIT License - see LICENSE file for details

## About

Part of Viprasol Utilities: https://viprasol.com

Created by Viprasol - Building AI-focused tools for developers.
