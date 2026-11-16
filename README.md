# test-pr 2

Sandbox for testing GitHub stacked pull requests (`gh stack`) together with
merge rules on `main`:

- Every PR into `main` needs at least 1 approval.
- PRs that change `protected/` must be approved by a code owner
  (@JoseAntonioSanofi or @albert-rc-sanofi).
