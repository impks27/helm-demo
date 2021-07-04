# helm-demo

helm install frontend-helm --set imageCredentials.username=%REGISTRY_USERNAME%,imageCredentials.password=%REGISTER_PASSWORD% .\frontend-helm --set service.type=NodePort

helm install backend-helm --set imageCredentials.username=%REGISTRY_USERNAME%,imageCredentials.password=%REGISTER_PASSWORD% .\backend-helm --set service.type=NodePort

helm list

helm delete


https://akomljen.com/package-kubernetes-applications-with-helm/
https://itnext.io/helm-3-umbrella-charts-standalone-chart-image-tags-an-alternative-approach-78a218d74e2d
https://docs.bitnami.com/tutorials/create-your-first-helm-chart/