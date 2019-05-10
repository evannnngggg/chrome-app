# BitLox Chrome App

This is the Chrome implementation of the USB interface for BitLox cryptocurrency hardware wallets

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Tested and working with the following on macOS 10.14.4

```
node v7.10.1
npm 6.4.1
bower 1.8.2
Google Chrome Version 76.0.3788.1 (Official Build) dev (64-bit)
```

### Installing

Clone the repo to your local machine, saving to _bitlox-chrome-app_

```
git clone https://github.com/BitLox/chrome-app.git bitlox-chrome-app
```

Change into the new directory

```
cd bitlox-chrome-app
```

Install npm components

```
npm install
```

Install bower

```
bower install
```

Make

```
make
```

Built chrome app will be in the _build_ folder


## Deployment

Open Chrome and find "More tools..." then "Extensions"
Select "Load unpacked" then navigate to the _build_ directory. Load and run.

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Pull requests for improvements welcome!

## Authors

* **Dana L. Coe** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* thanks to all the coders on the Bitcoin project for your amazing work
* if you don't own your private keys, you don't own your coins