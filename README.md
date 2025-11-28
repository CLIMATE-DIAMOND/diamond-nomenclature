# diamond-nomenclature
Data structure definition for validation of model outputs in the HORIZON EUROPE
project DIAMOND, using nomenclature-iamc

## Usage
You can either
1. use the files in this repository directly with the `nomenclature` package to
   validate model outputs, or
2. use the API in the Python package defined by this repository to obtain a
   nomenclature `DataStructureDefinition` object and a `RegionProcessor` object,
   which can then be used with the nomenclature API to perform validation and
   aggregation checking.

### 1. Use files directly

To use the files directly, download or clone the repository to a folder on your
computer.

The data definitions and region mappings are then found in the directories
`<repo_path>/diamond_nomenclature/data/definitions/` and
`<repo_path>/diamond_nomenclature/data/mappings/`, respectively, where
`<repo_path>` is the path to the root folder of the downloaded/cloned
repository. Pass these paths to `nomenclature.DataSrructureDefinition()` and
`nomenclature.RegionProcessor.from_directory()`, respectively, to get
`DataStructureDefinition` and `RegionProcessor` objects that you can use for
validation.
