# ECOMMEDIA/.github

Workflows reutilizables de GitHub Actions de Ecommedia.

| Workflow | Qué hace |
|---|---|
| `shopify-theme-check.yml` | `shopify theme check` en PRs; solo fallan los errores nuevos respecto a la rama base. No usa secretos. |

Uso:

```yaml
jobs:
  theme-check:
    uses: ECOMMEDIA/.github/.github/workflows/shopify-theme-check.yml@main
```

La fuente se mantiene en el repo interno del harness; los cambios se hacen allí y se copian aquí.
