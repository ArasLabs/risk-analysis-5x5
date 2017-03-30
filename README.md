# Risk Analysis Tool 5x5

Risk Analysis using Workbooks, Worksheets and 5x5 analysis.

This is a stand-alone solution with no dependencies on the Program management.

Original idea from Jean-Marc and Jim at ITT Defense.

## History

This project and the following release notes have been migrated from the old Aras Projects page. Unlike community projects that have been migrated and archived, this project will be updated for compatibility with the latest release of Aras Innovator.

Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/risk-analysis-5x5/releases/tag/v1) | First baseline release. Can be Imported into 8.2.0 or 9.0.1.

#### Supported Aras Versions

Project | Aras
--------|------
[v1](https://github.com/ArasLabs/risk-analysis-5x5/releases/tag/v1) | 8.2.0, 9.0.1

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **RAT5x5** import packages

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\risk-analysis-5x5\Import\imports.mf` file in the Manifest File field.
6. Select **RAT5x5** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

See [Aras - Risk Analysis Tool.doc](./Documentation/Aras%20-%20Risk%20Analysis%20Tool.doc) for more information on using this project.

![Screenshot of Risk Analysis Tool Worksheet](./Screenshots/RAT5x5.jpg)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Created by Peter Schroer for Aras Corporation.

Original idea by Jean-Marc and Jim at ITT Defense.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
