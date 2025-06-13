name: Validate Plugin Version
on:
  push


permissions:
  contents: write
  pull-requests: write
  
jobs:
  validate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
        with:
          fetch-depth: 0
      - name: Validate Plugin Version
        uses: pwtyler/action-validate-plugin-version@handle-past-branches-ii