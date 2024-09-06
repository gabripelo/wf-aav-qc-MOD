# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

## [v1.1.1]
## Added
- Publish report missing from v1.0.3.
### Fixed
- Automated basecaller detection not finding a basecaller model.

## [v1.1.0]
### Changed
- Increase memory allocated to the medaka process.
- Updated Medaka to v1.12.0.
### Removed
- Options for specifying Medaka model (`--medaka_model` and `--basecaller_cfg`) as this is now inferred automatically from the input data.
### Added
- Tagging of BAMs with `AV:Z` specifying AAV genome type.
- Option `--output_genometype_bams` to output BAMs by assigned genome type.
- Support for creating IGV JSON config files.
- Automatic detection of basecalling model and medaka model selection.
- `--override_basecaller_cfg` parameter for cases where automatic basecall model detection fails or users wish to override the automatic choice.

## [v1.0.3]
### Fixed
- Datatype inference error during CSV loading. 

## [v1.0.2]
### Fixed 
- Missing data when using reference files containing FASTA header descriptions.

## [v1.0.1]
### Fixed
- `<img>` tags in the docs.

## [v1.0.0]
### Added
- Added memory and CPU directives to all processes.

### Changed
- Updated docs.

## [v0.0.2]
### Fixed
- Related protocols link

## [v0.0.1]
### Added
- First release of wf-aav-qc
