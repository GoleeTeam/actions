# Golee Build Action Workflow

In order not to subscribe to the enterprise version of GitHub we publish our template actions here ;)

Usage

```
- name: Package
  id: package
  uses: GoleeTeam/actions/package@v0.2
  with:
    name: ${{ github.repository }}
    branch: ${{ github.ref }}
    commit_hash: ${{ github.sha }}
```
