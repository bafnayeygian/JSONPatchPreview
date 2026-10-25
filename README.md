# JSONPatchPreview

Apply and preview a practical RFC 6902 JSON Patch subset locally, with add, remove, replace, and test operations plus change summaries.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/JSONPatchPreview.git
cd JSONPatchPreview
python -m pip install .
```

## Usage

```bash
json-patch-preview --help
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
