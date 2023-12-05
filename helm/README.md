# confluent-helm
This helm chart deploys confluent services
  - connect
  - schema-registry
  - ksqldb
  - rest-proxy
  - ALB ingress (cp-msk)
  - ClusterExternalSecret

Confluent-Platform version: 7.5.0

Local-dns
connect.usva.dbdev.web.elco.cloud 10.244.125.210
proxy.usva.dbdev.web.elco.cloud 10.244.124.241
registry.usva.dbdev.web.elco.cloud 10.244.125.17
ksqldb.usva.dbdev.web.elco.cloud 10.244.124.217