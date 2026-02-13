<p align="center">
  <img src="https://raw.githubusercontent.com/copick/copick/main/docs/assets/logo.png" alt="copick logo" width="200">
</p>

<h1 align="center">copick</h1>

<p align="center">
  <strong>Open-source tools for collaborative cryoET annotation and analysis</strong>
</p>

<p align="center">
  <a href="https://github.com/copick/copick/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
  <a href="https://pypi.org/project/copick/"><img src="https://img.shields.io/pypi/v/copick.svg" alt="PyPI"></a>
  <a href="https://copick.github.io/copick/"><img src="https://img.shields.io/badge/docs-online-green.svg" alt="Documentation"></a>
</p>

**copick** is an open-source ecosystem for collaborative cryogenic Electron Tomography (cryoET) annotation and analysis.

We provide a cross-platform, storage-agnostic, and server-less dataset API that enables researchers to access and manage tomography data seamlessly—regardless of where it's stored.

## Packages

### Core

| Package | PyPI | Zenodo | Description | Install |
|---------|------|--------|-------------|---------|
| [copick](https://github.com/copick/copick) | [![PyPI](https://img.shields.io/pypi/v/copick.svg?logo=pypi&logoColor=white)](https://pypi.org/project/copick/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17799611-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17799611) | Core data model and API for cryoET datasets | `pip install "copick[all]"` |
| [copick-utils](https://github.com/copick/copick-utils) | [![PyPI](https://img.shields.io/pypi/v/copick-utils.svg?logo=pypi&logoColor=white)](https://pypi.org/project/copick-utils/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17799968-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17799968) | CLI utilities for data processing and conversion | `pip install copick-utils` |

### Machine Learning

| Package | PyPI | Zenodo | Description | Install |
|---------|------|--------|-------------|---------|
| [copick-torch](https://github.com/copick/copick-torch) | [![PyPI](https://img.shields.io/pypi/v/copick-torch.svg?logo=pypi&logoColor=white)](https://pypi.org/project/copick-torch/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17807121-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17807121) | PyTorch dataset classes and augmentations | `pip install copick-torch` |

### Visualization Plugins

| Package | PyPI | Zenodo | Description | Install |
|---------|------|--------|-------------|---------|
| [napari-copick](https://github.com/copick/napari-copick) | [![PyPI](https://img.shields.io/pypi/v/napari-copick.svg?logo=pypi&logoColor=white)](https://pypi.org/project/napari-copick/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17799844-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17799844) | [Napari](https://napari.org) plugin for interactive annotation | `pip install napari-copick` |
| [chimerax-copick](https://github.com/copick/chimerax-copick) | | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17799783-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17799783) | [UCSF ChimeraX](https://www.rbvi.ucsf.edu/chimerax/) plugin for 3D visualization | [ChimeraX Toolshed](https://cxtoolshed.rbvi.ucsf.edu/apps/chimeraxcopick) |
| [copick-shared-ui](https://github.com/copick/copick-shared-ui) | [![PyPI](https://img.shields.io/pypi/v/copick-shared-ui.svg?logo=pypi&logoColor=white)](https://pypi.org/project/copick-shared-ui/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17799860-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17799860) | Shared Qt UI components for plugins | `pip install copick-shared-ui` |

### Integrations

| Package | PyPI | Zenodo | Description | Install |
|---------|-----|--------|-------------|---------|
| [copick-mcp](https://github.com/copick/copick-mcp) | [![PyPI](https://img.shields.io/pypi/v/copick-mcp.svg?logo=pypi&logoColor=white)](https://pypi.org/project/copick-mcp/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17800059-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.17800059) | MCP server for Claude AI integration | `pip install copick-mcp` |
| [octopi](https://github.com/chanzuckerberg/octopi) | [![PyPI](https://img.shields.io/pypi/v/octopi.svg?logo=pypi&logoColor=white)](https://pypi.org/project/octopi/) | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18511916-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.18511916) | Deep learning framework for cryoET 3D particle picking | `pip install octopi` |
| [saber](https://github.com/chanzuckerberg/saber) | [![PyPI](https://img.shields.io/pypi/v/saber-em.svg?logo=pypi&logoColor=white)](https://pypi.org/project/saber-em/) | | Autonomous segmentation of organelles from cryoET | `pip install saber-em` |
| [py2rely](https://github.com/chanzuckerberg/py2rely) | | | Sub-tomogram averaging workflows for SLURM-based HPC | [see repo](https://github.com/chanzuckerberg/py2rely) |
| [topcup](https://github.com/czimaginginstitute/czii_cryoet_mlchallenge_winning_models) | | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18501364-blue?logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.18501364) | Winning models for CZII cryoET ML Challenge | `pip install topcup` |
| [slabpick](https://github.com/apeck12/slabpick) | | | Particle picking from 2D projections of tomography data | [see repo](https://github.com/apeck12/slabpick) |

## Quick Start

```bash
# Install core package with all storage backends
pip install "copick[all]"
```

```python
# Access data from the CZ cryoET Data Portal
from copick.impl.cryoet_data_portal import CopickRootCDP

# Open a dataset from the portal
root = CopickRootCDP.from_dataset_id(10301)

# List runs (tomograms)
for run in root.runs:
    print(run.name)
```

## Documentation

- [Documentation](https://copick.github.io/copick/) — Full documentation and tutorials
- [Quickstart Guide](https://copick.github.io/copick/quickstart/) — Get started in minutes
- [Data Model](https://copick.github.io/copick/datamodel/) — Understand the copick data structure
- [CLI Reference](https://copick.github.io/copick/cli/) — Command-line tools

## Data Resources

- [CZ cryoET Data Portal](https://cryoetdataportal.czscience.com/) — Public repository of cryoET datasets
- [Example Dataset](https://doi.org/10.5281/zenodo.16996074) — Sample copick project on Zenodo

## Contributors

| | GitHub | Packages |
|--|--------|----------|
| <img src="https://github.com/uermel.png" width="40"> | [@uermel](https://github.com/uermel) | copick, copick-utils, napari-copick, chimerax-copick, copick-torch, copick-mcp |
| <img src="https://github.com/kephale.png" width="40"> | [@kephale](https://github.com/kephale) | copick, copick-utils, napari-copick, copick-torch, copick-mcp |
| <img src="https://github.com/jtschwar.png" width="40"> | [@jtschwar](https://github.com/jtschwar) | copick, copick-utils, copick-torch |
| <img src="https://github.com/zhuowenzhao.png" width="40"> | [@zhuowenzhao](https://github.com/zhuowenzhao) | copick, copick-utils |
| <img src="https://github.com/daniel-ji.png" width="40"> | [@daniel-ji](https://github.com/daniel-ji) | copick |
| <img src="https://github.com/andy-sweet.png" width="40"> | [@andy-sweet](https://github.com/andy-sweet) | copick |

## Contributing

We welcome contributions! See our [Contributing Guide](https://github.com/copick/copick/blob/main/docs/contributing.md) for development setup and guidelines.

All projects follow the [Contributor Covenant Code of Conduct](https://github.com/chanzuckerberg/.github/blob/main/CODE_OF_CONDUCT.md).

## Citation

If you use copick in your research, please cite:

```bibtex
@article{harrington2024open,
  title={Open-source Tools for CryoET Particle Picking Machine Learning Competitions},
  author={Harrington, Kyle I. and Zhao, Zhuowen and Schwartz, Jonathan and Kandel, Saugat and Ermel, Utz and Paraan, Mohammadreza and Potter, Clinton and Carragher, Bridget},
  journal={NeurIPS 2024 Workshop on Machine Learning in Structural Biology},
  year={2024},
  doi={10.1101/2024.11.04.621608}
}
```

## License

All copick packages are released under the [MIT License](https://opensource.org/licenses/MIT).
