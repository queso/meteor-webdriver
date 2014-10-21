meteor-webdriver
================

A Velocity test package that combines webdriver  with a test framework for UI testing.

####The framework allows you to use:

- [-]  [WebdriverIO](http://webdriver.io)
- [-]  [WD.js](http://admc.io/wd)
- [-]  [WebDriverJs](https://code.google.com/p/selenium/wiki/WebDriverJs)

####With the following test frameworks:

- [-] [Jasmine 2.0](http://jasmine.github.io/2.0/introduction.html)
- [-] [Mocha](http://visionmedia.github.io/mocha/)

####And the package will:

- [x] Download [ChromeDriver](https://code.google.com/p/selenium/wiki/ChromeDriver) / [Selenium Server](http://www.seleniumhq.org/download/) for you
- [ ] Reuse the selenium webdriver session between tests so the browser does not flicker on and off
- [ ] Support multiple window testing
- [ ] Allow you to specify the browser matrix to run in development
- [ ] Allow you to specify the browser matrix to run in continuous integration
- [ ] SauceLabs & BrowserStack support


The driver (excuse the pun) behind this package is to allow a single testing "language" such as jasmine or mocha to be used across the entire testing stack. I will also be using this package in [The Meteor Testing Manual](www.meteortesting.com) book.
