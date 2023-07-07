# Helm Chart Repo for Software AG webMethods Components
This repository contains a collection of Helm charts for various webMethods components.

## Adding the Helm Chart Repo
To add this Helm chart repository to your Helm CLI, run the following command:

```shell
helm repo add pswm-inno-container-helm https://github..softwareag.com/PS/pswm-inno-container-helm/charts
```

## Available Charts
| Chart Name | Description |
| --- | --- |
| api-gateway| Helm Chart for API Gateway | 
| microservicesruntime | Helm Chart for Microservices Runtime |
| service-auditing-monitor | Helm Chart for Microservices Runtime using Service Auditing |
| universal-messaging | Helm Chart for Universal Messaging |
| mywebmethods-server| Helm Chart for MyWebMethods Server |
 
## Installing Charts
To install a chart from this repository, run the following command:

```shell
helm install pswm-inno-container-helm https://github.softwareag.com/pswm-inno-container-helm
```

## Contributing
If you want to contribute to this repository, please read the contributing guidelines first.