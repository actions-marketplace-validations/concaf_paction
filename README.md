# paction
pac + action, yeah yeah i know

### Example

```yaml
on: workflow_dispatch

jobs:
  paction-job:
    runs-on: ubuntu-latest
    steps:
    - uses: concaf/paction@v1
      with:
        openshift_token: ${{ secrets.OPENSHIFT_TOKEN }}
        openshift_server: ${{ secrets.OPENSHIFT_SERVER }}
        github_token: ${{ secrets.GITHUB_TOKEN }}
```
