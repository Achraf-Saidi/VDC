# VDC Engineering MVP

A desktop application prototype built with **Python** and **PyQt5** around a local database-backed workflow.

The current public repository is a **partial project snapshot**: it contains the application entry point, but the referenced `models/`, `gui/`, `data/` and `icons/` modules/assets are not included here. As a result, this repository is not currently a standalone runnable release.

## Entry point

`main.py` is responsible for:

- creating the Qt application;
- initializing a local database;
- creating the initial administrator account when needed;
- loading the application icon;
- opening the login window.

## Intended structure

```text
.
├── main.py
├── models/
│   └── database.py
├── gui/
│   └── login.py
├── data/
└── icons/
```

## Technology

- Python
- PyQt5
- Local database persistence

## Status

Prototype / public code snapshot.

## Author

**Achraf Saidi**
