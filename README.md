# DatingApp
This repo was created by following the Udemy Course - ["Build an app with ASPNET Core and Angular from scratch"](https://www.udemy.com/build-an-app-with-aspnet-core-and-angular-from-scratch/). 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system - TLDR: I've not tried a live deployment yet.

### Prerequisites

To run this project, you will need to have the following prerequisites installed:

- [ASP.net Core SDK](https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial/install) - created using v2.2.106
- [SQLite](http://sqlitebrowser.org/) - created using v3.11.2
- [NodeJS](https://nodejs.org/en/) - created using v11.2.0
- [Angular 2+](https://angular.io/) - created using v6.0.3

### Installation
#### API (DotNet Core / SQLite Backend)
From your command line / terminal, navigate into the `DatingApp.API` folder and run...

```cli
$ dotnet watch run
```

Once running, you should be able to test the API using either Postman, Insomnia, or any other REST client to ensure that the API is serving data on `http://localhost:5000/api/`

**Note:** Should you need to change the port the server is running on, this is configured in `DatingApp.API/Properties/launchSettings.json`. The SPA would need a matching change of port number at `DatingApp-SPA/src/app/_services/auth.service.ts`.

#### Single Page Application (Angular Frontend)

From your command line / terminal, navigate into the `DatingApp-SPA` folder and run...

```cli
$ npm i
```
... to install the dependencies.


To start the SPA server, run...

```cli
$ ng serve
```
If it doesn't do so automatically, navigate to `http://localhost:4200/`, to see the Angular SPA page, register a username and password to have a look at how the app works inside.

Note: Should you need to change the port the server is running on, this is configured in `DatingApp-SPA/e2e/protractor.conf.js`


## Running the tests

_TBD_ Explain how to run the automated tests for this system

### Break down into end to end tests

_TBD_ Explain what these tests test and why

```
Give an example
```

### And coding style tests

_TBD_ Explain what these tests test and why

```
Give an example
```

## Deployment

_TBD_ Add additional notes about how to deploy this on a live system

## Built With

* TBD

## Contributing

Please read _TBD_ for details on our code of conduct, and the process for submitting pull requests.

## Versioning

_TBD_

## Authors

* **Chris Perry** - *Initial work* - [christopherallanperry](https://github.com/christopherallanperry)

See also the list of [contributors](https://github.com/christopherallanperry/DatingApp/graphs/contributors) who have participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Udemy course tutor, Neil Cummings
