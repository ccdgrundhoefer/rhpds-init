# Configs, samples and demos to be used with OpenShift (RHPDS in particular)

The target of this repository is to provide useful default configs, which can be used with an RHPDS provisioned cluster.
Furthermore this includes a collection of samples and demos for specific use cases and operators

## Folders
- init-config: useful core configuration items, that can be applied to an OpenShift cluster or RHPDS cluster in particular
- demos: demos for several usecases and operators
- gitea operator catalog can be installed via `oc apply -f https://raw.githubusercontent.com/redhat-gpte-devopsautomation/gitea-operator/master/catalog_source.yaml`