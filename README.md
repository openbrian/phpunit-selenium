This package contains a Selenium2Testcase class that can be used to run end-to-end tests against Selenium 2.

Requirements:

- PHPUnit 5.x
- PHP 5.6 or higher (required by PHPUnit 5.x)

The current mainline of this package is 2.x. The old line 1.x is not maintained anymore, but will continue to be available for usage with PHP < 5.6 and PHPUnit < 5.x.

Please direct pull requests to [giorgiosironi/phpunit-selenium](https://github.com/giorgiosironi/phpunit-selenium) for automated testing upon merging. Pull requests should be feature branches containing all the commits you want to propose.

Running the test suite
---

#### Via Vagrant

Just run the following Vagrant commands (a minimal version of `v1.7` is required) and everything will be set up for you. The first start will take some time which depends on the speed of your connection (and less - speed of your computer):

    vagrant up
    vagrant provision
    vagrant ssh

    cd /vagrant
    vendor/bin/phpunit Tests
 
and you must see the `phpunit` testing `phpunit-selenium` project.

