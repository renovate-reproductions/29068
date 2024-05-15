# renovate-29068-example

This repo contains example files for <https://github.com/renovatebot/renovate/discussions/29068> .

It is expected, that renovate will create a pin-dependency branch for the two dependencies in example-deps.yaml.

Renovate will create this branch, but remove the whitespace in line 3 of example-deps.yaml, which separates the
string from the actual tag/version.

A word to the custom manager: With this manager you should be able to define the package name (docker repo)
within a comment, before the line with the actual value/version (docker image tag).
The line with the actual value is a key/value pair, where the value is either the plain docker image tag (and digest),
or a fully qualified docker repository + image tag (and digest).