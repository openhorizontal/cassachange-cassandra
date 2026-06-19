# Cassandra Migrations
This repository provide a reusable base for running 
Cassandra schema migrations using [cassachange](https://cassachange.com) 
in Kubernetes.


## Structure

- `db/` — Base Docker image with cassachange installed
- `k8s/` — shared Kustomize base for the migration job
