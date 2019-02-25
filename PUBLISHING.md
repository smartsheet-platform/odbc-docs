# Publishing Smartsheet Live Data Connector User Guide

## Purpose

This document outlines the process for publishing the Smartsheet Live Data Connector User Guide onto Github Pages. The actual Smartsheet Live Data Connector documentation can be viewed [here](http://smartsheet-platform.github.io/odbc-docs). 

## Publishing Process
1. Make sure that the `master` branch has the version of the code you would like to publish. 
2. Tag the branch with a git tag using the command `git tag <TAG_NAME>`.
3. Push the tag to git using the command `git push --tags`. 
4. Run the command `rake publish` to publish the code in the `master` branch to `gh-pages`, which is the branch that Github Pages uses to build the static documentation site. 
5. In the [Releases](https://github.com/smartsheet-platform/odbc-docs/releases) tab of the repository, draft and publish a new release using the tag you created in step 2. 

## Contributing
If you would like to contribute a change to the documentation files, see [Contributing](CONTRIBUTING.md).

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
