Go to https://quay.io/repository/openshift-release-dev/ocp-release?tag=latest&tab=tags to find out the digest URL for the OCP version.

Then run `generate-ocp-release-configmap <ocp version> <digest url>`.

For example:
```
$ ./generate-ocp-release-configmap \
  4.6.19 \
  https://quay.io/repository/openshift-release-dev/ocp-release/manifest/sha256:d74b1cfa81f8c9cc23336aee72d8ae9c9905e62c4874b071317a078c316f8a70
```

Then check in the YAML ConfigMap file.
