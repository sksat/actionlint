### Error at line 3, col 5 of `testdata/format/test.yaml`

unexpected key "branch" for "push" section. expected one of "branches", "branches-ignore", "paths", "paths-ignore", "tags", "tags-ignore", "types", "workflows"

```
    branch: main
    ^~~~~~~
```

### Error at line 6, col 14 of `testdata/format/test.yaml`

label "linux-latest" is unknown. available labels are "windows-latest", "windows-2019", "windows-2016", "ubuntu-latest", "ubuntu-20.04", "ubuntu-18.04", "ubuntu-16.04", "macos-latest", "macos-11", "macos-11.0", "macos-10.15", "self-hosted", "linux", "macos", "windows", "x64", "arm", "arm64". if it is a custom label for self-hosted runner, set list of labels in actionlint.yaml config file

```
    runs-on: linux-latest
             ^~~~~~~~~~~~
```
