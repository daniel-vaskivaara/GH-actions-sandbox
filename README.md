# GitHub Actions Sandbox

  Playground for testing things related to GitHub Actions

## .github/workflows

- `test-docker`: demos running actions inside a custom container (which is built by GitHub upon invoking the action). The reference in this case is to a bundled action (`uses: ./docker-action-test`), located in the matching location.