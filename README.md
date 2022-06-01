# asdf-helm

![GitHub Actions Status](https://github.com/Antiarchitect/asdf-helm/workflows/Test/badge.svg?branch=master)

[Helm](https://github.com/helm/helm) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add helm https://github.com/Antiarchitect/asdf-helm.git
```

### Environment Variable Options
- ASDF_HELM_OVERWRITE_ARCH: force the plugin to use a specified processor architecture rather than the automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when there's no `arm64` binary available.

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of Helm.
