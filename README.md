# This is test app

## The tests can be run with the following CLI options:

    --config: Extend/Overwrite the default config with your values, e.g. --config config.local.ts
    --includes: Expects a string/regexp to filter the tests to run, e.g. --includes "login|signup"

Running the tests on your machine

You have two options when running the e2e tests:

    Run a debug build of the app (useful when developing a test)
    Run two (e2e) release builds against each other (useful to test performance regression and the suite as a whole)

Running a debug build

    You need to create a debug build of the app that's configured with some build flags to enable e2e testing. The build flags should be specified in your ./.env file. You can use the ./tests/e2e/.env.e2e file as a template:
