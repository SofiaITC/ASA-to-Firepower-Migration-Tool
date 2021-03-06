# ASA to Firepower FMC Migration Tool

The goal of this project was to create an easy to use script that will gather custom objects from an ASA configuration file and import them into Firepower Management Center via a REST API. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

CiscoConfParse (http://www.pennington.net/py/ciscoconfparse/)
You can install this with pip via "pip install CiscoConfParse"

## Deployment

Just execute the script and answer the questions

## Built With

* [CiscoConfParse](http://www.pennington.net/py/ciscoconfparse/) - The cisco configuration parser used

## Features
- Migration of Network Objects
- Migration of Network Object Groups*
- Migration of Port Objects
- Migration of Port Object Groups

## *Caveats
- Does not import network groups inside network groups

## Versioning

Version 1.3 - (Added) Section for ACL deployment

## Authors

* **Matt Cross** - [RouteAllThings](https://github.com/routeallthings)

See also the list of [contributors](https://github.com/routeallthings/ASA-to-Firepower-Converter/contributors) who participated in this project.

## License

This project is licensed under the GNU - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to #DEVNET and their excellent API guides that got me started
