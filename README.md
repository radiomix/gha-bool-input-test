Cloned from: https://github.com/Kristonitas/ga-bool-input-test

Test dispatch inputs by calling

[Test github action call with fixed boolean inputs](https://github.com/radiomix/gha-bool-input-test/actions/workflows/call_test.yml)
[Test github action with manual boolean inputs](https://github.com/radiomix/gha-bool-input-test/actions/workflows/test.yml)


Via GHA CLI `gh` with fixed boolean inputs:
```
gh workflow run call_test.yml
```

Via GHA CLI `gh` with manual boolean inputs:
```
gh workflow run test.yml -F passed_true=true -F passed_false=false
```

