# usdtweak blueprints
## Description
This repository contains a collection of usd scenes that can be used in [usdtweak](https://github.com/cpichard/usdtweak) as "blueprints". The blueprints are organised hierarchically following the directory structure. The blueprint menu in ustweak will follow the directory structure (although this might change in the future). Blueprints are not part of usdtweak as different users might want different blueprints, presets, and having a separate repository allows for more flexibility, sharing back or personalising.

## Enable blueprints in usdtweak
First, clone this repository with:

    git clone https://github.com/cpichard/usdtweak-blueprints.git

By default usdtweak doesn't have the blueprints enabled. To enable them you'll have to edit the file `usdtweak_gui.ini` and add a line with the blueprints locations.

    BlueprintLocations=/path/to/the/blueprints/location/root

Change `/path/to/the/blueprints/location/root` to the root location of the blueprints. As an example if you cloned this repository in `/Users/john/usdtweak-blueprints` the line will be:

    BlueprintLocations=/Users/john/usdtweak-blueprints/root

The file `usdtweak_gui.ini` is generally found in `$HOME/Library/Preferences/usdtweak_gui.ini` on macOS and `$HOME\AppData\Local\usdtweak_gui.ini` on Windows.

 Note that you can add other directories containing blueprints in `BlueprintLocations`, the syntax allows a list of directories separated by semi-colons.

## How to use blueprints
In the usdtweak layer hierarchy editor, right clicking on a prim will show a popup menu with "add blueprint". Under this menu the hierarchy or blueprint is accessible and clicking on a blueprint name will copy the content of the blueprint under the selected prim. It's a way of having standard presets, lights, rendersettings, cameras, ready to be used.

