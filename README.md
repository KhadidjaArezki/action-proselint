# action-proselint
A GitHub action for proselint.
## Example
```
on:
  push:
    branches:
      - master

name: 'Trigger: Push action'

jobs:
  proselint:
    name: proselint
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - run: Run proselint
    uses: KhadidjaArezki/action-proselint@master
```

