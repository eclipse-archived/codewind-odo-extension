# Codewind-ODO-extension
OpenShift Do (ODO) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on OpenShift. 

The ODO extension allows you to see the list of available projects to clone and then lets you build and deploy your project to an OpenShift cluster. 

## Accessing OpenShift to support ODO extensions
See the following instructions to get started with the ODO extension: 

1. In your home directory, run the following command to clone the ODO extension repository.
```
git clone https://github.com/eclipse/codewind-odo-extension
```
2. Log in to your `OpenShift/OKD cluster`.
3. Go into `~/codewind-odo-extension/odo-RBAC` then run the following commands to add additional rules for ODO extension.
```
kubectl apply -f codewind-odoclusterrole.yaml
kubectl apply -f codewind-odoclusterrolebinding.yaml
```
## Contributing 
We welcome submitting issues and contributions.
1. [Submitting issues](https://github.com/eclipse/codewind/issues)
2. [Contributing](CONTRIBUTING.md)