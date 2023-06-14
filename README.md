# Konveyor CI

Work in progress.

## Status

Component | CI (after merge) | Nightly (cron)
--|--|--
**Hub** | [![Hub main](https://github.com/konveyor/tackle2-hub/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-hub/actions/workflows/main.yml) | [![Hub Test Suite](https://github.com/konveyor/tackle2-hub/actions/workflows/test-nightly.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-hub/actions/workflows/test-nightly.yml)
**UI** | [![UI test](https://github.com/konveyor/tackle2-ui/actions/workflows/ci-actions.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-ui/actions/workflows/ci-actions.yml) | -
**Addon Windup** | [![Test Windup Addon](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml) | - |
**E2E API** | [![API CI Test Suite](https://github.com/konveyor/go-konveyor-tests/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/konveyor/go-konveyor-tests/actions/workflows/main.yml) | [![API End-To-End Test Suite](https://github.com/konveyor/go-konveyor-tests/actions/workflows/test-nightly.yml/badge.svg?branch=main)](https://github.com/konveyor/go-konveyor-tests/actions/workflows/test-nightly.yml)
**E2E UI** | [![UI E2E test](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-ci.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-ci.yml) | [![UI E2E test](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-cron.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle-ui-tests/actions/workflows/k8s-cron.yml)


### Release nightlies

Branch | Status
--|--
**main** | [![Run Konveyor main nightly tests](https://github.com/konveyor/ci/actions/workflows/nightly-main.yaml/badge.svg?branch=main)](https://github.com/konveyor/ci/actions/workflows/nightly-main.yaml)
**release-0.2** | [![Run Konveyor release-0.2 nightly tests](https://github.com/konveyor/ci/actions/workflows/nightly-release-0.2.yaml/badge.svg?branch=main)](https://github.com/konveyor/ci/actions/workflows/nightly-release-0.2.yaml)
**release-0.1** | [![Run Konveyor release-0.1 nightly tests](https://github.com/konveyor/ci/actions/workflows/nightly-release-0.1.yaml/badge.svg?branch=main)](https://github.com/konveyor/ci/actions/workflows/nightly-release-0.1.yaml)

## Code of Conduct
Refer to Konveyor's Code of Conduct [here](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md).
