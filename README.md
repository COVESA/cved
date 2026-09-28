![Status - Incubating](https://img.shields.io/static/v1?label=Status&message=Incubating&color=FEFF3A&style=for-the-badge)
# Connected Vehicle Emergency Dataset Specification (CVEDS)

[![License](https://img.shields.io/badge/License-MPL%202.0-blue.svg)](https://opensource.org/licenses/MPL-2.0)

### Maintainers

Ulf Björkengren - Ford Motor Company

Tim VanGoethem - Emergency Safety Solutions

Lawrence Williams - Lidar Saving Lives Public Safety Coalition

## Connected Vehicle Emergency Dataset (CVED)
This COVESA project develops a vehicle emergeny dataset.
The data model used to represent it is the [HIM Data profile](https://covesa.github.io/hierarchical_information_model/#him-data-profile).
This datamodel uses the vspec syntax to define the CVED tree found in the spec folder.

### CVED export
The vspec format can be exported to other formats using the COVESA [VSS-tools](https://github.com/COVESA/vss-tools) exporter.
However, the VSS-tools exporter only supports the HIM VehicleData profile therefore a modified version must be used that also supports other HIM profiles.
This extended VSS-tools exporter is found [here](https://github.com/UlfBj/vss-tools/tree/him-support).
The exporter CLI is as is described in the documetnation exended with a --profile <profile-name> parameter, else it is identical with the upstream exporter CLI.

## Contributors
CVED is an open standard and we invite anybody to contribute. Currently CVED contains - among others - significant  contributions from

 - [Ford Motor Company](https://www.ford.com/)
