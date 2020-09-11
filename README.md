# Kubernautic.logging.stack

Software K8s logging stack, with Kibana, Elasticsearch and some logging tools like Fluentd,Fluentbit ...

## Deploy

use deploy.sh for deploying the elastic operator with kibana and fluentd or fluentbit

### k3s

fluentd has knows issues with k3s therefore you should use fluentbit for log forwarding
