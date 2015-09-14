# Duty Officer Add-on #

This project creates a Google Sheets add-on that interfaces with D4H to create
a call list with basic contact information.  There are some additional features
that are specific to the SMCSAR callout process.

## Usage ##

<Add screenshot here>

## Development ##

This project uses the workflow outlined [here](https://github.com/danthareja/node-google-apps-script/pull/15), using [Shrug's fork of the node-google-apps-script](https://github.com/Shrugs/node-google-apps-script) project.

### Basic workflow: ###

1. `git clone git@github.com:smcsar/duty-officer-addon.git`
2. Setup gapps `gapps init -s src`
3. Follow instructions at https://github.com/Shrugs/node-google-apps-script.
   For step 4.1, run `gapps init -s src` since this project assumes all code is
   under the `src/` directory
2. Modify code
3. `gapps upload <target>` (currently, the only specified target is `production`)
4. Switch to the project within Google Chrome and continue testing/deploying from there

Copyright 2015, Andrew Nguyen

Distributed under the GNU Affero General Public License Version 3.
