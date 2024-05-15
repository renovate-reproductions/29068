# renovate-29068-example

This repo contains example files for <https://github.com/renovatebot/renovate/discussions/29068> .

It is expected, that renovate will create a pin-dependency branch for the two dependencies in example-deps.yaml.

Renovate will create this branch, but remove the whitespace in line 3 of example-deps.yaml, which separates the
string from the actual tag/version.