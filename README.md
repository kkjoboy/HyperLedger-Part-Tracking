# Hyperledger Supplier Part Tracking

A problem on many manufacturing lines, specifically in heavy or industrial manufacturing, is the access to real-time data on the expected delivery of parts in the critical path of manufacturing. For example, in an assembly line of planes, each plane will have an order in which assembly of subsystems need to take place. For assembly to be done in a streamlined fashion, the supply chain needs to be perfect so that parts from potentially hundreds of suppliers are ready when a subsystem is being assembled. Delays in the supply chain can propogate across the line, not only adding time in the critical path manufacturing to that specific plane, but also to others.

The access to this real-time data is typically not easily available and requires the supplier reporting the data, which is then inserted into an internal database for use in analysis on the supply chain. This can lead to stale data that can't be used for predictive manufacturing applications. When the data is stale by days or even weeks, predictions cannot be made to account for supplier impacts on the manufacturing line. A more robust way of tracking and sharing data is needed.

In a perfect world, suppliers would have no issues with sharing their data on their manufacturing with others in the industry. In reality, data is the oil of the new world and sharing it with your competitors could prove harmful to business in the future, especially if two businesses no longer work together and become competitors. Each entity controlling their data and only sharing it when it benefits both parties is of utmost importance.

By implementing a solution using Hyperledger Fabric, we can create a situation where suppliers are able to control their own nodes that post data about their own manufacturing which can then be shared with their customers. Not only does this benefit the customer who will recieve real-time data on the expected completion of their parts, the suppliers are also able to use the data stored for their own internal analytics. Certain data can be chosen to share, or all of it can be shared. Permissions can also be revoked at any time.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
