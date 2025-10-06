# Windows Image Builder

## Prerequisites

1. OpenShift 4.19+
2. OpenShift GitOps
3. OpenShift Pipelines

## Installation

```shell
oc new-project vms
# update url to point to where you can find the iso
oc apply -k ./prerequisite/datavolume.yaml
```

## References

1. [Blog](https://developers.redhat.com/articles/2025/08/12/windows-image-building-service-openshift-virtualization#prerequisites)
2. [GitHub Example](https://github.com/ksimon1/windows-image-builder/tree/main)
