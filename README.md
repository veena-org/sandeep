# junit-browserstack
[JUnit](http://junit.org/junit4/) Integration with BrowserStack.

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780) 

![JUnit](http://junit.org/junit4/images/junit-logo.png)

## Setup
* Clone the repo
* Install dependencies `mvn install`
* Update *.conf.json files inside the `src/test/resources/conf` directory with your [BrowserStack Username and Access Key](https://www.browserstack.com/accounts/settings). 

## Running your tests
* To run a single test, run `mvn test -P single`
* To run parallel tests, run `mvn test -P parallel`
* To run local tests, run `mvn test -P local`

## Notes
* You can view your test results on the [BrowserStack automate dashboard](https://www.browserstack.com/automate)
* To test on a different set of browsers, check out our [platform configurator](https://www.browserstack.com/automate/java#setting-os-and-browser)
* You can export the environment variables for the Username and Access Key of your BrowserStack account. 

  ```
  export BROWSERSTACK_USERNAME=<browserstack-username> &&
  export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```

## Addtional Resources
* [Documentation for writing automate test scripts in Java](https://www.browserstack.com/automate/java)
* [Customizing your tests on BrowserStack](https://www.browserstack.com/automate/capabilities)
* [Browsers & mobile devices for selenium testing on BrowserStack](Browsers & Mobile Devices for Selenium Testing)
* [Using REST API to access information about your tests via the command-line interface](https://www.browserstack.com/automate/rest-api)
