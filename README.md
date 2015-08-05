# Smartsheet Live Data Connector User Guide

Documentation source files for the [Smartsheet Live Data Connector](http://www.smartsheet.com/apps/smartsheet-odbc).

## Purpose

This repository contains the source files used to generate the documentation for the Smartsheet Live Data Connector.
The actual Smartsheet Live Data Connector documentation can be viewed [here](http://smartsheet-platform.github.io/odbc-docs). 

## Submitting Feedback

To report documentation bugs or to request documentation enhancements, simply submit an issue [here](https://github.com/smartsheet-platform/odbc-docs/issues). 
And, of course, feel free to [submit pull requests](https://help.github.com/articles/using-pull-requests) with bug fixes or changes.

## Running the Docs Locally

Follow the steps below if you'd like to run the documentation locally on your machine.

### Prerequisites

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 1.9.3 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

 1. Fork this repository on Github.
 2. Clone *your forked repository* (not our original one) to your hard drive.
 3. Navigate to the directory of your local repository.
 4. Install all dependencies: `bundle install`
 5. Start the test server: `bundle exec middleman server`
 6. View the site in a browser:  <http://localhost:4567>

### Learning about Markdown Syntax
 
This documentation is based upon [Slate](https://github.com/tripit/slate/) and uses Slate [markdown syntax](https://github.com/tripit/slate/wiki/Markdown-Syntax).

## License

	Copyright 2015 Smartsheet, Inc.

	Licensed under the Apache License, Version 2.0 (the
	"License"); you may not use this file except in compliance
	with the License. You may obtain a copy of the License at

	http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing,
	software distributed under the License is distributed on an
	"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
	either express or implied. See the License for the specific
	language governing permissions and limitations under the
	License.
