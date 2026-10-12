# sphinx-split-project

This is a stand-alone source repository that's part of a decoupled duo-repository framework and that serves as the isolated target for its companion documentation-pipeline repository.

## Demonstrated features

* **Decoupled Architecture**: Serves as a pure source repository completely isolated from the Sphinx compilation engine.
* **Source Hygiene**: Demonstrates clean docstring structuring using standard reST styling without any internal documentation tooling overhead.

## Repository layout

```text
sphinx-split-project/
├── codebase/          # Directory for a demonstration code-base
│   └── example.py     # Python module with reST docstrings
├── .gitignore         # Defensive tracking shield
├── LICENSE            # License
└── README.md          # Main document for the repository

```

*This repository is a work-in-progress and serves as a sandbox for exploring decoupled document-generation pipelines with Sphinx.*
