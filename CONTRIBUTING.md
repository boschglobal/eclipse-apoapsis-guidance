# How to Contribute to Eclipse Apoapsis guidance

First of all, thanks for considering to contribute to Eclipse Apoapsis. We really
appreciate the time and effort you want to spend helping to improve things around here.

In order to get you started as fast as possible we need to go through some organizational issues first, though.

## Eclipse Contributor Agreement

Before your contribution can be accepted by the project team contributors must
electronically sign the Eclipse Contributor Agreement (ECA).

* http://www.eclipse.org/legal/ECA.php

Commits that are provided by non-committers must have a Signed-off-by field in
the footer indicating that the author is aware of the terms by which the
contribution has been provided to the project. The non-committer must
additionally have an Eclipse Foundation account and must have a signed Eclipse
Contributor Agreement (ECA) on file.

For more information, please see the Eclipse Committer Handbook:
https://www.eclipse.org/projects/handbook/#resources-commit

## Code Style Guide
* tbd

## Making Your Changes

* Fork the repository on GitHub.
* Create a new branch for your changes.
* Install docusaurus: https://docusaurus.io/docs/installation 
* Make your changes following the code style guide (see Code Style Guide section above).
* When you create new files make sure you include a proper license header at the top of the file (see License Header section below).
* Test the docusaurus website locally by 
    - npm run build and
    - npm run serve  
    in the "website" subfolder
* Commit your changes into that branch.
* Use descriptive and meaningful commit messages. Start the first line of the commit message with the issue number and title e.g. `[#9517] Fixed typo in the description`.
* Squash multiple commits that are related to each other semantically into a single one.
* Make sure you use the `-s` flag when committing as explained above.
* Push your changes to your branch in your forked repository.

## Dependency Management

tbd

### Website dependencies
* tbd

### "External Reference Links" dependencies
* tbd

### Development tools dependencies
* tbd

## License Header

Please make sure any file you newly create contains a proper license header like this:

For content in Markdown / React
```
# Copyright (c) <year> Contributors to the Eclipse Foundation
#
# These materials are made available under the
# terms of the Creative Commons Attribution 4.0 International Public License which is available at
# https://creativecommons.org/licenses/by/4.0/legalcode .
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
# WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
# License for the specific language governing permissions and limitations
# under the License.
#
# SPDX-License-Identifier: CC-BY-4.0
```
Please adjusted the comment character to the specific file format.


For "functional files" adding functionality to the website:
```
# Copyright (c) <year> Contributors to the Eclipse Foundation
#
# This program and the accompanying materials are made available under the
# terms of the Apache License, Version 2.0 which is available at
# https://www.apache.org/licenses/LICENSE-2.0.
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
# WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
# License for the specific language governing permissions and limitations
# under the License.
#
# SPDX-License-Identifier: Apache-2.0
```
Please adjusted the comment character to the specific file format.

## Submitting the Changes

Submit a pull request via the normal GitHub UI.

## After Submitting

* Do not use your branch for any other development, otherwise further changes that you make will be visible in the PR.