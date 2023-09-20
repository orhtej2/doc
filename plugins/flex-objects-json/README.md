# Flex Objects Json Plugin

The **Flex Objects Json** Plugin is an extension for [Grav CMS](http://github.com/getgrav/grav). Add JSON templates for Flex Objects

## Usage

If you want to get output of your flex objects as a JSON, and you use the default `Flex-objects` (`flex-objects.md`) page template provided by [Flex Objects plugin](https://github.com/trilbymedia/grav-plugin-flex-objects), just add `.json` extension to URL. Eg.: `https://example.com/flex-objects.json` and you should get a JSON response.

## Configuration

Before configuring this plugin, you should copy the `user/plugins/flex-objects-json/flex-objects-json.yaml` to `user/config/plugins/flex-objects-json.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```yaml
enabled: true
```

Note that if you use the Admin Plugin, a file with your configuration named flex-objects-json.yaml will be saved in the `user/config/plugins/`-folder once the configuration is saved in the Admin.

## Installation

Installing the Flex Objects Json plugin can be done in one of three ways: The GPM (Grav Package Manager) installation method lets you quickly install the plugin with a simple terminal command, the manual method lets you do so via a zip file, and the admin method lets you do so via the Admin Plugin.

### GPM Installation (Preferred)

To install the plugin via the [GPM](http://learn.getgrav.org/advanced/grav-gpm), through your system's terminal (also called the command line), navigate to the root of your Grav-installation, and enter:

    bin/gpm install flex-objects-json

This will install the Flex Objects Json plugin into your `/user/plugins`-directory within Grav. Its files can be found under `/your/site/grav/user/plugins/flex-objects-json`.

### Manual Installation

To install the plugin manually, download the zip-version of this repository and unzip it under `/your/site/grav/user/plugins`. Then rename the folder to `flex-objects-json`. You can find these files on [GitHub](https://github.com/karmalakas/grav-plugin-flex-objects-json) or via [GetGrav.org](http://getgrav.org/downloads/plugins#extras).

You should now have all the plugin files under

    /your/site/grav/user/plugins/flex-objects-json
	
> NOTE: This plugin is a modular component for Grav which may require other plugins to operate, please see its [blueprints.yaml-file on GitHub](https://github.com/karmalakas/grav-plugin-flex-objects-json/blob/master/blueprints.yaml).

### Admin Plugin

If you use the Admin Plugin, you can install the plugin directly by browsing the `Plugins`-menu and clicking on the `Add` button.
