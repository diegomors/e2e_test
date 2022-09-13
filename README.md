# e2e_test

A simple end to end test.

### Run Tests

[Setup your environment for integration_test](https://docs.flutter.dev/testing/integration-tests)

```
# Start chromedriver
$ chromedriver --port=4444
# Run tests
$ flutter drive --driver=test_driver/integration_test.dart --target=integration_test/template_test.dart -d chrome
```