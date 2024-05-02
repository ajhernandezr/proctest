# proctest
# UI Automation with Cypress
https://www.cypress.io/

I had been using Selenium for around 7 years, but then I switched to Cypress and use it for some time.
The reason for that is that compared with Selenium the test are much less flaky and faster.


# Rest Automation with Karate
https://github.com/karatelabs/karate

Karate is a popular testing framework, specially for API testing,
Some features:

*Tests are super-readable - as scenario data can be expressed in-line, in human-friendly JSON, XML, Cucumber Scenario Outline tables, or a payload builder approach unique to Karate

*Express expected results as readable, well-formed JSON or XML, and assert in a single step that the entire response payload (no matter how complex or deeply nested) - is as expected

*Comprehensive assertion capabilities - and failures clearly report which data element (and path) is not as expected, for easy troubleshooting of even large payloads

*Standard Java / Maven project structure, and seamless integration into CI / CD pipelines - and support for JUnit 5

*Multi-threaded parallel execution, which is a huge time-saver, especially for integration and end-to-end tests

*Gatling integration can hook into any custom Java code - which means that you can perf-test even non-HTTP protocols such as gRPC

## Performance Testing

https://karatelabs.github.io/karate/karate-gatling/

Karate permit the Re-use Karate tests as performance tests executed by Gatling

Use Gatling (and Scala) only for defining the load-model
