# Caviel Open Authorization Library
The Caviel Open Authorization library provides easy implication for projects to support logins from sources like Caviel, Google, Twitter, Facebook and more added every day.

> Caviel Open Authentication Library may sometimes be referred to as `COA`/`COAL`, `oAUTH` or `Open Auth` in diffrent places.

[![](https://data.jsdelivr.com/v1/package/gh/CavielApps/OpenAuth/badge)](https://www.jsdelivr.com/package/gh/CavielApps/OpenAuth)

## What Makes It Diffrent
In the COA library, we automaticly format external service data to a standardized JSON format for easy parsing even if they use an unorthadoxed method other than email and password.

## Supported Login Services
* [Caviel](https://caviel.com)
* [Google](https://google.com)
* [Twitter](https://twitter.com)
* [Facebook](https://facebook.com)
* [Apple](https://apple.com) - Coming Soon
* [Microsoft](https://microsoft.com) - Coming Soon

## Installation
To start using this in your application, it couldn't be easier.

* First, visit the [Caviel Develper Portal](https://cdp.caviel.com) and create a new application and enable the Open Auth settings, configure your login portal and remember your client id and your auth app id. - For refrence our client id will be `mycoolapp`(`mycoolapp.cda.caviel.com`) and our auth app id will be `9199-1999-8a88-8aji-9skj`.

* Secondly, you will need to implement our api in to your library, check our [documentation](https://github.com/CavielApps/OpenAuth)'s implication guide for your library. For refrence our library is available at https://scripts.caviel.com/system/openauth.js. `openauth.js` should be replaced with your specified language, for example we can use `openauth.php`, `openauth.cpp`, `openauth.java`, and more.

Additionally, you may use our [jsDelivr](https://jsdelivr.com) cdn link, if necessary, available [over here](https://cdn.jsdelivr.net/gh/CavielApps/OpenAuth/).

## Usage
Unfortunatley usage is diffrent for each language
