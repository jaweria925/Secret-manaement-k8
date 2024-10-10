# Secret-manaement-k8

Seceret management in Kubernetes

# External secret controller

External Secrets Operator is a Kubernetes operator that integrates external secret management systems like AWS Secrets Manager, HashiCorp Vault, Google Secrets Manager, Azure Key Vault, IBM Cloud Secrets Manager, Akeyless, CyberArk Conjur, Pulumi ESC and many more

Documentation Link:https://external-secrets.io/latest/

General purpose k8 sceret operator which integrate various external secret management systems.
A Kubernetes controller that reads information from the external api and automatically inject the values into k8s secrets.

Integrate the AWS Service AWS

# Enable externel secret controller using helm charts

helm repo add external-secrets https://charts.external-secrets.io

helm install external-secrets \
 external-secrets/external-secrets \
 -n external-secrets \
 --create-namespace \

# --set installCRDs=false
