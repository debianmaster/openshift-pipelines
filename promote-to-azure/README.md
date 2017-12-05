```sh
oc new-build  --strategy=pipeline --name=promote-to-azure https://github.com/debianmaster/openshift-pipelines --context-dir='promote-to-azure'

```
