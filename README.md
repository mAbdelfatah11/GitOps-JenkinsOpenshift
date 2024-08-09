# Configuring OpenShift using GitOps and Jenkins
In this exercise, you apply gitops practices in openshift to automate the configuration of HTPasswd authentication and group
membership from resource files in Git using Jenkins.
## Outcomes
You should be able to:

• Create a Jenkins pipeline that applies HTPasswd identity provider settings and RBAC
permissions from YAML files in a Git repository.

• Create another Jenkins pipeline that compares configuration in an OpenShift cluster with
YAML files and, if there are differences, remediates the configuration drift.

## Before You Begin
To perform this exercise, ensure you have access to:

• A running OpenShift cluster.

• The Jenkins master and Node.js agent container images from Red Hat.

• Resource files for configuring an HTPasswd identity provider and RBAC permissions.
