# BeSecure Projects Of Interest Metadata Store
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

Maintains the metadata of open source Projects of Interest (POI) for the BeSecure community. The metadata is stored is JSON format. 
The dashboard in BeSLighthouse make use of this metadata to visualize the projects details that the community tracks. The version 
summary of each project tracked is maintained in a seperate directory version_details for better readability. In order to track a 
new project in BeSecure, simply add the metadata entry into the OSSP_Master.json file and create a new file for the version summary
in version_details directory.

The community provides a utility to generate the metadata entry for a new project to be tracked [BeSecure Contributor Toolkit](https://github.com/Be-Secure/besecure-developer-toolkit)
