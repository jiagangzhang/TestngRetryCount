# TestngRetryCount
Understand how to implement Retry logic on failed test cases in TestNG

code from the following url
http://toolsqa.com/selenium-webdriver/implement-iretryanalyzer-to-retry-failed-test-in-testng-framework/

Implemented 2 TestNg listeners:
@IRetryAnalyzer
@IAnotationTransformer

Create a custome annotation:
@RetryCountIfFailed
