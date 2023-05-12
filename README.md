# Action

This action will handle an npm install

**Required** The branch to be installed.
## `target`

## Outputs
No outputs

## Example usage

```
uses: akerolabs/setup@v1
with:
  target: ${GITHUB_REF#refs/heads/}
```