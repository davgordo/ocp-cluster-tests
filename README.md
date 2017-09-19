# OCP Cluster Tests

## Docker Build

Tests a docker build and a deployment of the resulting container.

`$ oc process -f docker-build/template.yml | oc apply -f -`

`$ oc start-build example`

`$ oc rollout latest example`
