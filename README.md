# Team Status Update

A simple Github action to update your Team Status for https://github.com/ebot7/bot-andy

## Usage
Use the following step your Github workflow.

```
- uses: ebot7/team-status-update@v0.1.4
  if: ${{ always() }}
  with:
    team-name: ap
    test-name: End-to-end tests
    app-version: v1
```

The context parameter is optional. If provided, it must be a valid JSON string.
