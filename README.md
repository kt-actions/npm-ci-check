# npm-ci-check

NPM Continuous Integration check action

- checkout
- kt-actions/npm-run-script
  - setup node environment (kt-actions/setup-node-minmax, use cache)
  - install dependencies or restore from cache (uses cache)
  - run checks
