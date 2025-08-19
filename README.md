# 010 Editor Scientific Binary Templates

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![010 Editor](https://img.shields.io/badge/010%20Editor-v16.0+-blue.svg)](https://www.sweetscape.com/010editor/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXX)

## Abstract

This repository provides a comprehensive collection of 010 Editor Binary Templates (`.bt`) specifically designed for scientific data analysis. These templates have been systematically transpiled from Kaitai Struct specifications, ensuring full semantic implementation with zero compilation errors and practical validation capabilities. The collection addresses critical gaps in binary analysis tools for scientific computing, spectroscopy, geospatial analysis, and machine learning workflows.

## Supported Scientific Data Formats

### Spectroscopy and Scientific Instrumentation

- **NT-MDT** (.mdt) - Scanning probe microscopy data from NT-MDT software
- **SPECPR** (.spec) - Spectrum Processing Routines data format for spectral analysis

### Geospatial Information Systems

- **ESRI Shapefile** (.shp) - Vector geospatial data with full geometry support
- **Shapefile Index** (.shx) - Spatial indexing for efficient data access

### Machine Learning and Serialization

- **MessagePack** (.msgpack, .mp) - Efficient binary serialization for ML models and datasets

## Features

- **Full Semantic Implementation**: Templates provide complete parsing logic, not mere annotations
- **Validation Capabilities**: Built-in assertions and checksum verification ensure data integrity
- **Optimized Performance**: Efficient parsing strategies for large scientific datasets
- **Cross-Platform Compatibility**: Tested on 010 Editor v16.0+ across multiple operating systems
- **Academic Standards**: Comprehensive documentation with literature references

## Installation and Usage

### Prerequisites

- 010 Editor v16.0 or later
- Administrative privileges for template installation (Windows/macOS)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/ajsb85/010-editor-scientific-templates.git
   ```

2. Copy desired `.bt` files to your 010 Editor templates directory:
   - **Windows**: `%USERPROFILE%\Documents\SweetScape\010 Editor\Templates\`
   - **macOS**: `~/Documents/SweetScape/010 Editor/Templates/`
   - **Linux**: `~/.SweetScape/010Editor/Templates/`

### Usage Examples

#### Analyzing NT-MDT Microscopy Data

```cpp
// Load NT-MDT template and parse scanning probe microscopy data
// Templates > Run Template > nt_mdt.bt
// Automatically detects frame types and parses spectroscopy data
```

#### Processing Geospatial Shapefiles

```cpp
// Load shapefile template for GIS vector data analysis
// Templates > Run Template > shapefile_main.bt
// Supports all geometry types including Z and M coordinates
```

## Contributing

We welcome contributions from the scientific computing community. Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines on:

- Template development standards
- Testing procedures for scientific data validation
- Documentation requirements
- Code review process

## Validation and Testing

All templates undergo rigorous validation using representative datasets from their respective scientific domains. Test datasets and validation procedures are documented in the `tests/` directory.

## Citation

If you use these templates in your research, please cite this repository:

```bibtex
@software{salas_010_editor_scientific_templates_2024,
  author       = {Salas, Alejandro J.},
  title        = {010 Editor Scientific Binary Templates},
  year         = {2024},
  publisher    = {GitHub},
  url          = {https://github.com/ajsb85/010-editor-scientific-templates},
  doi          = {10.5281/zenodo.XXXXXX}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Kaitai Struct Project** for the foundational format specifications
- **010 Editor Development Team** for the robust binary analysis platform
- **Scientific Computing Community** for format documentation and test datasets

## Contact

**Alejandro J. Salas**  
*IEEE Senior Member*  
Email: <a.salas@ieee.org>  
ORCID: [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)

---

*This repository maintains academic standards for reproducible research in computational science and binary data analysis.*
