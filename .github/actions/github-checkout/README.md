# GitHub Checkout

Checkout the repository at the current ref. Exposes the checked ref and SHA.

```yaml
- uses: krudi/reusable-actions/.github/actions/github-checkout@main
```

Optional inputs:

- `fetch_depth`
- `ref`

Outputs:

- `checked_sha`: commit SHA checked out
- `checked_ref`: ref checked out (branch/tag)
