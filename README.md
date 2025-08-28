> This Plugin / Repo is being maintained by a community of developers.
There is no warranty given or bug fixing guarantee; especially not by
Programmfabrik GmbH. Please use the github issue tracking to report bugs
and self organize bug fixing. Feel free to directly contact the committing
developers.

# custom-data-type-tnadiscovery

Custom Data Type "TNADiscovery" for fylr

This is a plugin for [fylr](https://docs.fylr.io/) with Custom Data Type `CustomDataTypeTNADiscovery` for references to entities of the [Nationalarchives-Discovery-System](<http://discovery.nationalarchives.gov.uk/>).

The Plugins uses <http://discovery.nationalarchives.gov.uk/API/> for the autocomplete-suggestions and additional informations about Nationalarchives-entities.

## installation

The latest version of this plugin can be found [here](https://github.com/programmfabrik/fylr-plugin-custom-data-type-tnadiscovery/releases/latest/download/customDataTypeTNADiscovery.zip).

The ZIP can be downloaded and installed using the plugin manager, or used directly (recommended).

Github has an overview page to get a list of [all releases](https://github.com/programmfabrik/fylr-plugin-custom-data-type-tnadiscovery/releases/).

## requirements
This plugin requires https://github.com/programmfabrik/fylr-plugin-commons-library. In order to use this Plugin, you need to add the [commons-library-plugin](https://github.com/programmfabrik/fylr-plugin-commons-library) to your pluginmanager.


## configuration

There is no custom configuration yet.

## saved data
* conceptName
    * Preferred label of the linked record
* conceptURI
    * URI to linked record
* discoveryID
    * ID in discovery-system
* discoveryURL
    * URL in discovery-system
* referenceNumber
* locationHeld
* title
* description
* _fulltext
    * easydb-fulltext
* _standard
    * easydb-standard

## sources

The source code of this plugin is managed in a git repository at <https://github.com/programmfabrik/fylr-plugin-custom-data-type-tnadiscovery>.

## updater
Note: The automatic updater is implemented and can be configured in the baseconfig. You need to enable the "custom-data-type"-update-service globally too.


