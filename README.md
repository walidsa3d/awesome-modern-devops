# Awesome Modern Devops [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome modern devops tools and resources


## Contents

- [Databases](#Databases)
- [Search](#Search)
- [Observability](#Observability)
- [Containers](#Containers)
- [Messaging](#Messaging)
- [Storage](#Storage)
- [DevSecOps](#DevSecOps)
- [CI/CD](#CI/CD)
- [IaC](#IaC)
- [Misc](#Misc)
- [Resources](#Resources)

## CI/CD
- [Jenkins](http://jenkins-ci.org/) - An open source automation server.
- [Gitlab](https://gitlab.com/)
- [Gitness](https://github.com/harness/gitness) - An open source developer platform with source control management, continuous integration and continuous delivery.
- [Gitea](https://github.com/go-gitea/gitea) - Self-hosted Git hosting, code review, team collaboration, package registry and CI/CD.

## IaC
- [Terraform](https://www.terraform.io/) -  An infrastructure as code tool that enables you to safely and predictably provision and manage infrastructure in any cloud.
    - [OpenTufu](https://opentofu.org/) - A community-driven fork of Terraform.
    - [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation.
    - [Localstack](https://github.com/localstack/localstack) -  cloud software development framework to develop and test your AWS applications locally.
    - [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) - A CLI tool that generates terraform files based on existing infrastructure.
- [Ansible](https://www.ansible.com/) - A Configuration management and application-deployment tool.
    - [Molecule](https://github.com/ansible/molecule) - Test Ansible roles.
    - [AWX](https://github.com/ansible/awx) - A web UI for Ansible.
- [Cloud-init](https://github.com/canonical/cloud-init) - Cross-platform cloud instance initialisation tool.

## Observability
- [Prometheus](https://prometheus.io/) - The leading open-source
monitoring solution.
    - [Awesome Prometheus alerts](https://samber.github.io/awesome-prometheus-alerts/) - A collection of alerting rules.
    - [Node_Exporter](https://github.com/prometheus/node_exporter) - A system metrics exporter.
    - [Blackbox_Exporter](https://github.com/prometheus/blackbox_exporter) - Allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP and ICMP.
- [Grafana](https://grafana.com/) - An interactive data-visualization platform.
- [Sentry](https://sentry.io/) - Application performance monitoring and error tracking software.
- [Elasticsearch](https://www.elastic.co/elasticsearch)
- [FluentBit](https://github.com/fluent/fluent-bit) - A fast log processor and forwarder.
- [Fluentd](https://github.com/fluent/fluentd) - A log collector and shipper.
- [Grafana Loki](https://github.com/grafana/loki) - A log aggregation system designed to store and query logs from all your applications and infrastructure.

## Containers
- [Docker](https://www.docker.com/)
    - [Watchtower](https://github.com/containrrr/watchtower) - A tool for automating Docker container base image updates.
    - [Diun](https://crazymax.dev/diun/) - A Docker image update notifier.
    - [Lazydocker](https://github.com/jesseduffield/lazydocker) - A simple terminal UI for both docker and docker-compose.
- [Podman](https://github.com/containers/podman) -  A tool for managing OCI containers and pods.
- [k8s](https://github.com/kubernetes/kubernetes)
    - [Minikube](https://minikube.sigs.k8s.io/) - A tool to setup a local Kubernetes cluster. 
    - [K9s](https://k9scli.io/) - A terminal UI to interact with your Kubernetes clusters.
    - [ArgoCD](https://github.com/argoproj/argo-cd) - A declarative, GitOps continuous delivery tool for Kubernetes.
    - [Helm](https://helm.sh/) - A tool for managing packages of pre-configured Kubernetes resources.
    - [Kompose](https://kompose.io/) -  A conversion tool for Docker Compose to container orchestrators such as Kubernetes.
    - [Karpenter](https://karpenter.sh/) - Just-in-time nodes for any kubernetes cluster.
    - [Keda](https://keda.sh/) - Allows for fine grained autoscaling for event driven Kubernetes workloads.
    - [kyverno](https://github.com/kyverno/kyverno) - Cloud-Native policy management tool.

## Databases
- [Cassandra](https://cassandra.apache.org/) - A NoSQL distributed database.
    - [Medusa](https://github.com/thelastpickle/cassandra-medusa) - A Cassandra backup tool.
- [Postgres](https://www.postgresql.org/)
    - [Pgbouncer](https://github.com/pgbouncer/pgbouncer) - A connection pooler for Postgresql.
    - [Barman](https://pgbarman.org/) - A Postgresql backup tool.
    - [pgAdmin](https://github.com/pgadmin-org/pgadmin4) - A web-based management tool for the Postgres.
    - [Postgres Exporter](https://github.com/prometheus-community/postgres_exporter) - A Prometheus exporter for PostgreSQL server metrics.
    - [PGVector](https://github.com/pgvector/pgvector) - Vector similarity search for Postgres.

## Search
- [Elasticsearch](https://www.elastic.co/elasticsearch) - A distributed, RESTful search and analytics engine.
    - [OpenSearch](https://github.com/opensearch-project/OpenSearch) - An open-source fork of Elasticsearch.
    - [Curator](https://github.com/elastic/curator) - Tending your Elasticsearch indices.
- [TypeSense](https://github.com/typesense/typesense) - A fast, typo- tolerant, in-memory fuzzy search engine.

## WebServers
- [HAProxy](https://www.haproxy.org/) - The reliable, high performance tco/http load balancer.
- [Nginx](http://nginx.org/) - The famous web server.
- [Caddy](https://caddyserver.com/) - A powerful, enterprise-ready web server with automatic HTTPS.

## Messaging
- [Redis](https://redis.io/) - The famous key-value store.
- [RabbitMQ](https://www.rabbitmq.com/) - A reliable and mature messaging and streaming broker, 
- [ZeroMQ](https://github.com/zeromq) - An open-source universal messaging library.

## Storage
- [Minio](https://github.com/minio/minio) - A high performance object storage.
- [Longhorn](https://github.com/longhorn/longhorn) - A distributed block storage system for Kubernetes.
- [Garage](https://garagehq.deuxfleurs.fr/) - An open-source distributed object storage service tailored for self-hosting.

## DevSecOps
- [Trivy](https://github.com/aquasecurity/trivy) - An open source security scanner.
- [Snyk](https://snyk.io/) - Scans and monitors your projects for security vulnerabilities.
- [Checkov](https://github.com/bridgecrewio/checkov) - Prevents cloud misconfigurations and finds vulnerabilities during build-time in infrastructure as code.
- [SonarQube](https://github.com/SonarSource/sonarqube) - Code Quality, security and static analysis tool. 
- [Gitleaks](https://github.com/gitleaks/gitleaks) - A fast, light-weight, portable, and open-source secret scanner for git repositories, files, and directories.
- [Trufflehog](https://github.com/trufflesecurity/trufflehog) - A secrets scanning tool.
- [Vault](https://github.com/hashicorp/vault) - A tool for secrets management, encryption as a service, and privileged access management.

## Misc
- [Vagrant](https://www.vagrantup.com/) - A tool to build and manage virtual machines.
- [Airflow](https://github.com/apache/airflow) - A platform to programmatically author, schedule, and monitor workflows.
- [Keycloak](https://github.com/keycloak/keycloak) - Open-source identity and access management for modern applications and services.

## Resources
- [Git Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet)
- [Git tips](https://github.com/git-tips/tips)
- [Git flow cheat sheet](https://danielkummer.github.io/git-flow-cheatsheet/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
