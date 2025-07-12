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
