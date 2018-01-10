
# Unit tests

```
unit/
	├── components/
	├── models/
	├── services/
	├── store/
	└── util/
test/
	└── unit/
```

Unit tests run on [Jest](https://facebook.github.io/jest/). Unit tests can be written for all the elements of application code, meaning services, models, components and utilities as well as Vuex code.

You can use the scripts listed in [setup instructions](../overview/setup.md) to run tests.

Running unit tests on the command line gives you a report like this:

![Unit test results on command line](../images/unit-test-report-cli.png)

An HTML version will also be generated:

![Unit test results in browser](../images/unit-test-report-html.png)

The test pipeline will also generate an HTML report about the coverage, which looks like this:

![Unit test results in browser](../images/unit-test-coverage-report-html.png)

The HTML report will be available under `/reports/lcov-report/`. You can open it over `file://`, no file server is needed.