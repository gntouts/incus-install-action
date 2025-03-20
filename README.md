# incus-install-action

## Usage

To use this action, include it in your workflow:

```yaml
jobs:
  setup_incus:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Setup Incus
        uses: gntouts/incus-setup-action@v1
```
