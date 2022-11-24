# Rusty WoolCogs

## Description
This is just a test package for utilizing the Rust runtime for AWS Lambda.

## Commands

* `cargo test` - Runs the unit testing suite
* `cargo lambda watch` - Starts the local AWS Lambda emulator
* `cargo lambda invoke --data-ascii '{"name": "Wooly"}'` - Runs a test hello world event against the local AWS Lambda emulator
* `cargo lambda build --release` - Builds a production optimized release
* `cargo lambda deploy` - Deploys the production optimized release to your AWS Account using the AWS CLI
* `cargo lambda invoke --remote --data-ascii '{"name": "Wooly"}' --output-format json rusty-woolcogs` - Runs a test hello world event against the deployed Lambda