# Example Python integration testing with docker-compose

## Objectives:

1. demonstrate using pyton unittest to build, start up, execute tests against, and tear down an app defined in a docker-compose file.
- Compatible with standard python unittest (`python -m unittest integration_tests.test_`)
- Compatible with testing frameworks such as nosetest and pytest (`nosetest`, `pytest -v --log-level DEBUG`)
- Bonus: make the tests executable against a live environment, for diagnostics

## Requirements:
- Docker
- docker-compose
