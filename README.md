# .github
The Mmenm profile repo

## Renovate

This repository defines the independent Renovate preset for the mmenm owner.
Repositories under this owner can extend it with:

```json
{
  "extends": ["github>mmenm/.github:renovate-config"]
}
```

Renovate keeps supported managers enabled by auto-discovery. It opens separate major update pull requests, limits open and hourly pull requests, and does not merge updates automatically. Lock files are maintained weekly.
