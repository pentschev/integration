# <div align="left"><img src="https://rapids.ai/assets/images/RAPIDS-logo-white.svg" width="90px"/>&nbsp; Integration

RAPIDS - combined conda package &amp; integration tests for all of RAPIDS libraries

## RAPIDS Meta-packages

The conda recipe in the `conda` folder provides the RAPIDS meta-packages, which
when installed will provide the latest RAPIDS libraries for the given version or
setup `build`, `doc`, or `notebook` environments for RAPIDS.

See the [README](conda/recipes/README.md) for more information about the
meta-packages and how to update versions.

## RAPIDS Integration Tests

Test scripts in the `test` folder verify proper interaction across multiple
RAPIDS APIs.  Tests are separated into individual subfolders based on the usage
of a specific RAPIDS library with the other RAPIDS libs.
