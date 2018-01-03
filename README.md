# visual-regression-test-example

[![CircleCI](https://circleci.com/gh/janivihervas/visual-regression-test-example.svg?style=svg)](https://circleci.com/gh/janivihervas/visual-regression-test-example)

Example for visual regression test using [BackstopJS](https://github.com/garris/BackstopJS) and [CircleCI](https://circleci.com/). CircleCI commits changed screenshots automatically for branches other than `master`.

## CircleCI environment variables

- `PUSHBACK_USER_NAME`
  - Github user name
- `PUSHBACK_USER_EMAIL`
  - Github user email
- `PUSHBACK_TOKEN`
  - Github token with `repo` permissions
