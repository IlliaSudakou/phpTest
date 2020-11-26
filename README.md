# phpTest

install XAMPP PHP
install PHPUnit

https://phpunit.de/getting-started/phpunit-9.html


phpunit --bootstrap ./src/autoload.php --log-junit tests.xml tests

--bootstrap src/autoload.php instructs the PHPUnit command-line test runner to include src/autoload.php before the tests are run.

--log-junit tests.xml instructs the PHPUnit command-line test runner to Log test execution in JUnit XML format to file

tests instructs the PHPUnit command-line test runner to execute all tests found declared in *Test.php sourcecode files in the tests directory
