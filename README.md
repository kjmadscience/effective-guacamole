# effective-guacamole
Blog repo for volt redpanda integration

All the technologies are deployed on cloud infrastructure using helm charts. helm charts make the deployment process swift and easy for any engineer to install the applications without having to follow complex instructions and creating a tree of directories. 

For the sake of these steps, we assume that kubernetes cluster is installed and ready with appropriate network configurations. From here the steps are same for public cloud or private cloud.

## Adding Helm Repos

```
helm repo add voltdb 'https://voltdb-kubernetes-charts.storage.googleapis.com'

helm repo add redpanda 'https://charts.redpanda.com'

helm repo add redpanda-console 'https://dl.redpanda.com/public/console/helm/charts/' 

helm repo add prometheus-community 'https://prometheus-community.github.io/helm-charts'

```
## Installing Volt



## Installing Redpanda

## Integration

### Import - Volt

### Export - Volt

### MessageGenerator - Redpanda

