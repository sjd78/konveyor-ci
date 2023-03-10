# Konveyor CI

Work in progress.

## Status

### End-to-End suite tests

#### API
[![E2E API Test](https://github.com/konveyor/go-konveyor-tests/actions/workflows/e2e-api-test.yml/badge.svg?branch=main)](https://github.com/konveyor/go-konveyor-tests/actions/workflows/e2e-api-test.yml)


#### UI
[![E2E UI Test](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-cron.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-cron.yml)

### Components integration tests

#### Windup Addon
[![Test Windup Addon](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml)


#### Hub
[![Test Addons](https://github.com/konveyor/tackle2-hub/actions/workflows/test-addons.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-hub/actions/workflows/test-addons.yml)
(uses test from Windup addon, just executed on Hub push)

```TODO```

Add more components (like Hub) with their unit/integration tests execution status.

## Notes

### CI next steps/TODOs proposal

- Setup go-based E2E API test suite
- Fully implement QE-provided sanity API test scenarios
- Setup Tackle with auth enabled (and potentialy multiple users with different roles)
- Add upstream UI tests execution result and relevant components tests
- Extend for relevant non-main branches

## Code of Conduct
Refer to Konveyor's Code of Conduct [here](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md).
