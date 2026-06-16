# .github

Shared GitHub configurations, templates, and reusable workflows for my projects.

## Contents

- **[workflows/](workflows/)** — Reusable GitHub Actions workflows.
- **[templates/](templates/)** — Shared template files for project scaffolding.
- **[LICENSE](LICENSE)** — MIT License.

## Using Reusable Workflows

Any repository under this account can reference workflows from this repo:

```yaml
jobs:
  my-job:
    uses: juanmiguelruiz/.github/.github/workflows/<workflow-file>@main
```

## License

MIT © [Juan Miguel Ruiz Pazos](https://github.com/juanmiguelruiz)
