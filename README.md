# JobTech Passport


## Preface:
Arbetsförmedlingen has made the commitment to implement parts of the MyData principles within the JobTech MyData initiative.

“ MyData Global is a registered non-profit association and a global network with the mission to empower individuals by improving their right to self-determination regarding their personal data . "
Read more about myData principles.

Our mission with this project is to help job seekers and employers to find each other, to boost innovation within the labor market and to create opportunities for all actors within the industry sector.

## Background:
The ‘JobTech-Passport’ initiative is about creating a decentralised infrastructure that allows job-seekers to create and manage their CVs in one place and use it on all job sites and TTS available in Sweden and to transfer their CV data from where they are initially stored to another destination system (most likely to a potential employer database). 

Arbetsförmedlingen, together with a partner within the private sector, has developed a generic, multi-purpose POC (Proof Of Concept) that enables individuals to store and control who has access to their data and which information they have access to. Read more about EgenData infrastructure.

‘JobTech-Passport’ is meant as an application built on top of the generic EgenData, that makes the CV-data available to the players who have an interest in reading or writing onto it, upon receiving the appropriate consent from the data owner.

## MVP description:
An intermediate layer between systems in the labor market where the individual is given the opportunity to handle approval of what information is to be shared and to whom.

## MVP elements:
Export of CV data: an API for retrieving CV data from their source (requires the individual to have a strong identification)
Import of CV data: an API allowing third parties to receive CV data.
CV-data standardization: a mapping allowing third parties to understand the data sent
User consent: An interface where the individual requests the collection of own data and handles the consent for the data transfer.
Data storage: A storage solution for personal data where third parties can only access the information that they have been allowed to access by the data owner.

## Architectural constituent:
Storage: The user chooses where the information should be stored
Consent: An APP where the user handles transfer consent of their data
Operator: Technical service that coordinates information flows between services.
Automation: Handling offline transactions
Encryption: Modules to facilitate and ensure that an encryption takes place when information is created or read.

_______________________

![alt text][logo]

[logo]: https://github.com/MagnumOpuses/project-meta/blob/master/img/jobtechdev_black.png "JobTech dev logo"
[A JobTech Project](https://www.jobtechdev.se)

* [Gravity Beacon](https://github.com/MagnumOpuses/gravity-beacon)
* [Gravity Connector](https://github.com/MagnumOpuses/gravity-connector)
* [Gravity Ground Control](https://github.com/MagnumOpuses/gravity-ground-control)
* [Gravity Infrastructure](https://github.com/MagnumOpuses/gravity-infrastructure)
* [Gravity Portability](https://github.com/MagnumOpuses/gravity-portability)
* [Gravity Specs](https://github.com/MagnumOpuses/gravity-specs)

# Gravity

This repository is the starting point of the Gravity project with documentation and links to Gravity sub-projects.

## Versions, current dev state and future

No versions yet.

## Getting started

No getting started guidelines yet.

### Prerequisites

No prerequisites guidelines yet.

### Installation

```bash
git clone https://github.com/MagnumOpuses/gravity.git
cd gravity
```

## Test

No tests yet.

## Deployment

No deployment guidelines yet.

## Built with

No technologies yet.

## Contributing

We would love if you'd like to help us build and improve this product for the benefit of everyone. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org/) code of conduct.

Any contributions, feedback and suggestions are more than welcome.

Please read our guidelines for contribution [here](CONTRIBUTING_TEMPLATE.md).

## License

[Apache License 2.0](LICENSE.md)

## Acknowledgments

No acknowledgments yet.
