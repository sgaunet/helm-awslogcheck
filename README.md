# helm-awslogcheck

```
helm repo add awslogcheck https://sgaunet.github.io/helm-awslogcheck/
helm repo update
helm search repo awslogcheck
```

[Here is the documentation to configure the helm chart.](charts/awslogcheck/README.md)

# Development

This project is using :

* [helm](https://helm.sh/)
* [task for development](https://taskfile.dev/#/)
* [pre-commit](https://pre-commit.com/)

There are hooks executed in the precommit stage. Once the project cloned on your disk, please install pre-commit:

```
brew install pre-commit
```

And install the hooks:

```
task dev:install-pre-commit
```

If you like to launch manually the pre-commmit hook:

```
task dev:pre-commit
```
