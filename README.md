Cloned from: https://github.com/Kristonitas/ga-bool-input-test

Test dispatch inputs by calling:
- Via GHA UI
  - [Test github action call with fixed boolean inputs](https://github.com/radiomix/gha-bool-input-test/actions/workflows/call_test.yml)
  - [Test github action with manual boolean inputs](https://github.com/radiomix/gha-bool-input-test/actions/workflows/test.yml)


- Via GHA CLI `gh`:
  - fixed boolean inputs: `gh workflow run call_test.yml`
  - set boolean inputs: `gh workflow run test.yml -F passed_true=true -F passed_false=false`
