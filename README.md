# Root App chart

This Helm chart is imported by https://gitlab.com/vlasman/terraform-argo-cd.

Fork this repository and customize it to your needs. **The only requirement is `templates/argo-cd.application.yaml` to be present. Edit it, but don't rename that file.**

## Development

While you're developing the Helm chart, use the test values to ensure complex settings are being tested.

```sh
helm template . --values=values.test.yaml --debug
```
