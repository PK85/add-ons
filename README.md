# Add-ons

## Overview

This repository contains add-ons which the [Helm Broker](https://kyma-project.io/docs/master/components/helm-broker/#overview-overview) uses. It allows you to choose a set of add-ons you want to use, define your own add-ons, and configure the Helm Broker to use them.

## Usage

The `add-ons` folder contains sources of add-ons and `index.yaml` files that are available in [releases](https://github.com/kyma-project/bundles/releases). To learn more about the release process, read [this](docs/releases.md) document.
To learn how to configure the Helm Broker to use different set of add-ons, read the [Helm Broker configuration](https://kyma-project.io/docs/master/components/helm-broker/#configuration-configuration) document.

## Development

Develop your own remote add-ons repository forked from the original repository. Read [this](docs/getting-started.md) document to learn how. On your fork, you can [create your own add-ons](https://kyma-project.io/docs/master/components/helm-broker/#details-details). Read the [`CONTRIBUTING.md`](CONTRIBUTING.md) document that includes the contributing rules specific for this repository.

### Project structure

The repository has the following structure:

```
  ├── .github                     # Pull request and issue templates    
  ├── bin                         # Tools used by Travis CI         
  ├── bundles                     # Sources of add-ons                                                
  ├── docs                        # Documentation source files
  └── scripts                     # Scripts and tools which check and create add-ons
```
