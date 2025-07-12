# Actions Sandbox

GitHub Actions SandBox

## Manual start

```
on:
  workflow_dispatch:

```

## Jobs

```
jobs:
  job-name:
    runs-on: windows-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v4
```


## Upload artifact

```
- name: Upload ...
  uses: actions/upload-artifact@v4
  with:
    name: executable
    path: dist/*
```


## Links

Run GitHUb Actions locally: https://github.com/nektos/act
