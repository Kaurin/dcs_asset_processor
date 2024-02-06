# Digital Combat Simulator Asset Processor -- PRE-ALPHA Work In Progress

Used by the [dcs_asset_installer][dcs_asset_installer] github template repo. 

## Usage
User instanciates `LiveryAssetCollection` with the .yaml config as the input parameter

DCSAP then:
* Reads the user-provided .yml file which has definitions for the DCS assets
* Downloads the assets into a staging area
* Parses the staging area directory structure to gather information such as pilot names, checksums etc
* Checks in terms of directory structure, naming, user-provided sting matching
* Compresses the individual assets with 7-zip

The user can use the `LiveryAssetCollection` as a data structure which contains metadata about the processed Staging area liveries.

Example boilerplate can be seen in the [dcs_asset_installer][dcs_asset_installer] repository

---

*DCS and DIGITAL COMBAT SIMULATOR are trademarks of Eagle Dynamics SA and bare no affiliation with this project*


[dcs_asset_installer]: https://github.com/Kaurin/dcs_asset_installer
