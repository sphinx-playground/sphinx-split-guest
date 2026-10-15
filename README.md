# sphinx-split-guest

This is a stand-alone source repository that's part of a decoupled split-repository framework. It serves as the isolated target for its companion [sphinx-split-host](https://github.com/sphinx-playground/sphinx-split-host) documentation-pipeline repository.

## Demonstrated features

* **Decoupled architecture**: Serves as a pure source repository completely isolated from the **Sphinx** compilation-engine.
* **Source hygiene**: Demonstrates clean docstring structuring using standard **reST** styling without any internal documentation-tooling overhead.

## Repository layout

```text
sphinx-split-guest/
├── codebase/          # Directory for a demonstration code-base
│   └── example.py     # Python module with reST docstrings
├── .gitignore         # Defensive tracking shield
├── LICENSE            # License
└── README.md          # Main document for the repository

```

*This repository is a work-in-progress and serves as a sandbox for exploring decoupled document-generation pipelines with Sphinx.*
