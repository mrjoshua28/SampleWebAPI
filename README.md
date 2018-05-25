[![Build Status](https://travis-ci.com/mrjoshua28/SampleWebAPI.svg?branch=master)](https://travis-ci.com/mrjoshua28/SampleWebAPI)

# SampleWebAPI

A small sample web api with tests, for playing around with CI tools. And MUCH MORE!

## How This Works

[Travis](https://www.travis-ci.com/) is watching... Travis integration has been installed. See [travis.yml](https://github.com/mrjoshua28/SampleWebAPI/blob/master/.travis.yml) for all the details.

Basially this is what's happening:

1. When a push is made to the repo, Travis builds the project and runs the tests.

2. When a Pull Request is created, Travis builds the project and runs the tests.

3. When a merge is made into Master, Travis builds the project and runs the tests.

4. When a merge is made into Master, Travis will package up the artifacts from the build and deploy to Elastic Beanstalk in AWS.

[URL](http://precisionexercise-env.kkxcvkqyhr.us-east-2.elasticbeanstalk.com/) - DOES NOT WORK

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you have to get a development env running

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

* [Visual Studio](https://www.visualstudio.com/) - Good luck not using it!
* [.NET](https://www.microsoft.com/net/) - C# baby
* [NUnit](http://nunit.org/) - Test all the things!

## Contributing

Please read [CONTRIBUTING.md](https://github.com/mrjoshua28/SampleWebAPI/blob/master/CONTRIBUTING.md) for the process for submitting pull requests to us.

## Versioning

Explain versioning

## License

This project is licensed under the ??? License - see the [LICENSE.md](LICENSE.md) file for details
