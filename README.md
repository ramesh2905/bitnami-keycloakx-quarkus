# bitnami-keycloakx-quarkus
bitnami-keycloak-kube

## Getting started ##
Keycloak is an opensource identity and access management tool used for securely authenticating users into their applications. 

## Prerequisites ##
This installation assumes that an instance of Postgresql DB is already running on the minikube cluster or kubernetes cluster 

### Installation ###
`helm repo add bitnami  https://charts.bitnami.com/bitnami`
`helm install keycloak bitnami/keycloak -n bitnami -f .\keycloakx-values.yaml`

### Uninstall ###
`helm uninstall keycloak -n bitnami`