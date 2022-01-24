# skaffold-path-templating-example
An example project that would work if [this](https://github.com/GoogleContainerTools/skaffold/pull/7049) PR is merged.

Usage:

`NAMESPACE=foo skaffold run`

You can manage multiple namespaces, e.g.
```
NAMESPACE=foo skaffold run
NAMESPACE=bar skaffold run
NAMESPACE=foo skaffold delete
```
