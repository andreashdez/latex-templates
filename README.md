# Latex Templates

Templates for some LaTeX documents

## How to build

Use `latexmk` with the following options to easily build a document and continuously monitor its changes:

```bash
latexmk -pdflua -pvc
```

## How to install missing packages

In case a package is missing it can be installed with the following command (might require `sudo`):

```bash
tlmgr install <package-name>
```

