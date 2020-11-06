# sample-poetry
 
## Installing

```bash
$pip install poetry
```

## Create New Project

```bash
$poetry new sample-project
```

This will create the following files and folders:

```txt
sample-project
├── README.rst
├── pyproject.toml
├── sample_project
│   └── __init__.py
└── tests
    ├── __init__.py
    └── test_sample_project.py
```

## Add New Dependency

```bash
$cd sample-project
$poetry add [--dev] <package name>
```
