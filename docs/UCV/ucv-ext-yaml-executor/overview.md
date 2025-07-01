
# YAML Executor - Overview

The YAML Executor plug-in is automatically installed and configured without manual configuration. You can apply the YAML file under **Settings>External Config Pipeline** to initiate the YAML Executor plug-in integration process.


## Compatability

This plug-in requires DevOps Velocity version 4.0.12 and later.

## Versions

DevOps Velocity plug-in images are located in DockerHub. To
view available versions, see the [UrbanCode DockerHub](https://hub.docker.com/r/urbancode/ucv-ext-yaml-executor/tags).


## History


### Version 0.0.7

* **Added extra parameter**: Added below new parameters to configure valuestream.
* **name**: Specify the name for the ValueStream.
* **application**: Filter resources to include only the specified application in the pipeline section.
* **integrationId**: Reuse an existing integration configuration. If integrationId specified then `configs` field is optional.
* **team**: Associate the ValueStream with a specific team.
* **appEnvOrder**: To order the environment in the valuestream pipeline while syncing

### Version 0.0.5

* Initial release

|Back to ...||Latest Version|YAML Executor |||
| :---: | :---: | :---: | :---: | :---: | :---: |
|[All Plugins](../../index.md)|[Velocity Plugins](../README.md)|[0.0.7-File 1 ](https://raw.githubusercontent.com/UrbanCode/IBM-UCV-PLUGINS/main/files/ucv-ext-yaml-executor/ucv-ext-yaml-executor%3A0.0.7.tar.7z.001)[and 0.0.7-File 2](https://raw.githubusercontent.com/UrbanCode/IBM-UCV-PLUGINS/main/files/ucv-ext-yaml-executor/ucv-ext-yaml-executor%3A0.0.7.tar.7z.002)|[Readme](README.md)|[Steps](steps.md)|[Downloads](downloads.md)|
