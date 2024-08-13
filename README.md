# Mridul_Pandita_teladoc_challenge

//The language used in the testing suite is groovy
//The framework used is spock and also some features of geb are also used.
//TestingWebtableSpec contains two test case for the website https://www.way2automation.com/angularjs-protractor/webtables/ and it extends loginspec page and that page contains all the initialization of the driver and browser instance.
//And all the page methods have been declared in HomePage,and homepage extends customlocator class which contain methods that are not specific to any page.

---
For groovy and spock framework best build tool is gradle which it is groovy based DSL
So command to run the test cases:
gradle test --tests TestingWebtableSpec

