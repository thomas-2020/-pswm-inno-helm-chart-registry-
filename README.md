# Helm Chart Repository for Software AG webMethods Components

This repository contains a collection of Helm charts for various webMethods components. The section *Available Charts* provides more information about the contents. We test and develop all Helm Charts for webMethods release version 10.15.

## Adding the Helm Chart Repository

To add this Helm chart repository to your Helm CLI, run the following command:

```shell
helm repo add webmethods-helm-charts https://github.com/SoftwareAG/webmethods-helm-charts
```

## Available Charts

| Chart Name | Description |
| --- | --- |
| [api-gateway](./api-gateway/helm/README.md) | Helm Chart for API Gateway |
| [developer-portal](./developer-portal/helm/README.md) | Helm Chart for Developer Portal |
| [microservicesruntime](./microservicesruntime/helm/README.md) | Helm Chart for Microservices Runtime |
| [mywebmethodsserver](./mywebmethodsserver/helm/README.md) | Helm Chart for My WebMethods Server |
| [universalmessaging](./universalmessaging/helm/README.md) | Helm Chart for Universal Messaging |

## Contributing

If you want to contribute to this repository, please read the [contributing guidelines](./CONTRIBUTING.md) first.
