# Awesome Nomad

> **Note:** This repository contains an *automatically compiled* list of resources, tools, and information related to ClickHouse.

A curated list of amazingly awesome Nomad tools and shiny things.

Pull requests with additional tools and projects are more than welcome!

- [Documentation, examples, demos, and awesome lists](#documentation,-examples,-demos,-and-awesome-lists) (5)
- [Demo and Learning Resources](#demo-and-learning-resources) (1)
- [Infrastructure setup](#infrastructure-setup) 
    - [Automation and Infrastructure Management](#automation-and-infrastructure-management) (13)
    - [Deployment and Cluster Setup](#deployment-and-cluster-setup) (5)
    - [Integrated Solutions and Applications](#integrated-solutions-and-applications) (7)
    - [Monitoring and Logging](#monitoring-and-logging) (4)
    - [Tools and Utilities](#tools-and-utilities) (3)
    - [User Interfaces and Dashboards](#user-interfaces-and-dashboards) (2)
- [Ops tools](#ops-tools) (13)
- [DevOps tools](#devops-tools) (2)
- [CI / CD](#ci--cd) (1)
- [Integrations](#integrations) (1)
- [Plugins](#plugins) (9)
- [SDK](#sdk) (1)



## Documentation, examples, demos, and awesome lists

- [jippi/awesome-nomad](https://github.com/jippi/awesome-nomad) - Awesome Nomad is a curated list of various tools and utilities that enhance the usability and functionality of HashiCorp Nomad.
- [mentoriaiac/awesome-devops](https://github.com/mentoriaiac/awesome-devops) - A curated list of resources on DevOps fundamentals and tools including Docker, Kubernetes, and Hashicorp Nomad.
- [mr-karan/nomad-events-sink](https://github.com/mr-karan/nomad-events-sink) - Nomad Events Sink is an agent for collecting and processing Nomad events to external sinks like HTTP.
- [nairnavin/practical-nomad-consul](https://github.com/nairnavin/practical-nomad-consul) - This project is a detailed tutorial for setting up a multi-tier application using Nomad and Consul.
- [romantomjak/ansible-roles](https://github.com/romantomjak/ansible-roles) - This repository offers a collection of Ansible roles and example playbooks for automating setup tasks on Debian-based hosts.

## Demo and Learning Resources

- [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) - This project offers a Vagrant-based demo for integrating and running Hashicorp Nomad with other HashiCorp tools.

## Infrastructure setup


### Automation and Infrastructure Management

- [ansible-community/ansible-nomad](https://github.com/ansible-community/ansible-nomad) - Ansible-Nomad is an Ansible role that automates the installation and configuration of Nomad.
- [dsaidgovsg/terraform-modules](https://github.com/dsaidgovsg/terraform-modules) - A set of reusable Terraform modules for provisioning HashiCorp tools, including Nomad, on AWS.
- [eschudt/hashistack-digitalocean](https://github.com/eschudt/hashistack-digitalocean) - Hashistack Digitalocean is a Terraform project for setting up a Consul and Nomad cluster on DigitalOcean.
- [freeCodeCamp/infra](https://github.com/freeCodeCamp/infra) - This project provides infrastructure-as-code resources for managing freeCodeCamp.org's infrastructure.
- [fwkz/dill](https://github.com/fwkz/dill) - Dill is a cloud-ready L4 TCP proxy that improves load balancing and routing through dynamic listeners.
- [hashicorp/levant](https://github.com/hashicorp/levant) - Levant is an open-source tool that offers templating and deployment capabilities for HashiCorp Nomad jobs.
- [hyperbadger/nomad-pipeline](https://github.com/hyperbadger/nomad-pipeline) - Nomad Pipeline is a tool that enables the execution of pipeline-style workloads in HashiCorp's Nomad with job dependencies management.
- [kadalu/kadalu](https://github.com/kadalu/kadalu) - Kadalu is a lightweight persistent storage solution for Kubernetes, OpenShift, and Nomad utilizing GlusterFS.
- [mr-karan/homelab](https://github.com/mr-karan/homelab) - This project provides infrastructure as code and setup scripts for a personal home server using Nomad.
- [multani/docker-nomad](https://github.com/multani/docker-nomad) - This project provides a Docker image for running Hashicorp Nomad.
- [picatz/terraform-google-nomad](https://github.com/picatz/terraform-google-nomad) - Terraform module for setting up Nomad clusters with Consul on Google Cloud Platform.
- [sagarrakshe/nomad-dtree](https://github.com/sagarrakshe/nomad-dtree) - nomad-dtree is a tool that facilitates dependency management between Nomad jobs.
- [tristanpemble/nix-nomad](https://github.com/tristanpemble/nix-nomad) - A tool for generating HashiCorp Nomad job definitions using Nix.

### Deployment and Cluster Setup

- [astro/skyflake](https://github.com/astro/skyflake) - Skyflake is a hyperconverged infrastructure solution for NixOS that utilizes Nomad for managing virtual machines.
- [efbar/hashicorp-labs](https://github.com/efbar/hashicorp-labs) - Hashicorp Labs simplifies the deployment of a local Hashicorp cluster for testing applications with Vault, Consul, and Nomad.
- [internetarchive/hind](https://github.com/internetarchive/hind) - HinD simplifies the setup of a Nomad cluster with Consul and Caddy server in a single Docker container.
- [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) - hashi-up is a utility for quickly installing HashiCorp Nomad, Consul, or Vault on remote Linux hosts over SSH.
- [zerodha/nomad-cluster-setup](https://github.com/zerodha/nomad-cluster-setup) - This project provides Terraform modules for deploying a HashiCorp Nomad cluster on AWS.

### Integrated Solutions and Applications

- [FRosner/cluster-broccoli](https://github.com/FRosner/cluster-broccoli) - Cluster Broccoli is a self-service platform for managing Nomad jobs through a RESTful web service and UI.
- [dokku/dokku-scheduler-nomad](https://github.com/dokku/dokku-scheduler-nomad) - dokku-scheduler-nomad is a plugin for integrating Dokku with Nomad to deploy applications.
- [eBayClassifiedsGroup/KomPaaS](https://github.com/eBayClassifiedsGroup/KomPaaS) - KomPaaS is a compact PaaS solution utilizing Nomad, Consul, and Fabio for efficient deployment.
- [kangaroot/rootstack-devfactory](https://github.com/kangaroot/rootstack-devfactory) - Devfactory is an integrated solution that utilizes Hashicorp tools to provide quick VM and container runtime environments.
- [thangchung/coffeeshop-modular](https://github.com/thangchung/coffeeshop-modular) - A modular .NET coffee shop application that can be started with docker-compose and integrates with HashiCorp Nomad.
- [thangchung/coffeeshop-on-nomad](https://github.com/thangchung/coffeeshop-on-nomad) - This .NET coffeeshop application showcases the use of Docker, Nomad, and Consul Connect for running microservices.
- [thangchung/go-coffeeshop](https://github.com/thangchung/go-coffeeshop) - A practical event-driven microservices demo built with Golang, utilizing Nomad, Consul Connect, Vault, and Terraform for deployment.

### Monitoring and Logging

- [jrasell/nomad-toast](https://github.com/jrasell/nomad-toast) - Nomad Toast is a tool for receiving notifications based on HashiCorp Nomad events.
- [mr-karan/nomad-monitoring](https://github.com/mr-karan/nomad-monitoring) - A complete monitoring solution for Nomad clusters using Grafana dashboards and jobspecs.
- [mr-karan/nomad-vector-logger](https://github.com/mr-karan/nomad-vector-logger) - Nomad-vector-logger is a daemon that generates Vector configuration files for enriched logging in Nomad clusters.
- [seatgeek/nomad-firehose](https://github.com/seatgeek/nomad-firehose) - The `nomad-firehose` is a monitoring tool for changes in Nomad job, allocation, nodes, and evaluations.

### Tools and Utilities

- [franckverrot/trek](https://github.com/franckverrot/trek) - Trek is a CLI/ncurses explorer for HashiCorp Nomad clusters.
- [myENA/consul-backinator](https://github.com/myENA/consul-backinator) - Consul-backinator is a command line utility for backing up and restoring Consul data, including key-value pairs and ACL tokens.
- [seatgeek/nomad-helper](https://github.com/seatgeek/nomad-helper) - Nomad-helper is a tool designed to enhance the usability of HashiCorp Nomad at scale.

### User Interfaces and Dashboards

- [cvandal/nomad-ui](https://github.com/cvandal/nomad-ui) - Nomad UI is a user interface for HashiCorp's Nomad designed to facilitate the management of Nomad clusters.
- [hashicorp/damon](https://github.com/hashicorp/damon) - Damon is a terminal dashboard for effectively interacting with HashiCorp Nomad.

## Ops tools

- [42wim/nomadctld](https://github.com/42wim/nomadctld) - nomadctld is an SSH server facilitating interaction with HashiCorp Nomad clusters.
- [aldoborrero/hashi-homelab](https://github.com/aldoborrero/hashi-homelab) - Hashi Homelab is a repository that provides Nomad recipes for various open source projects designed for use on a Nomad, Consul, and Vault-enabled Intel Nuc cluster.
- [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) - Envoy Consul Service Discovery Service integrates Envoy with Consul and Nomad to provide service discovery functionalities.
- [assareh/tfc-agent](https://github.com/assareh/tfc-agent) - This repository provides examples for using the Terraform Cloud Agent, a remote runner designed for Terraform Cloud Business and Enterprise, with specific implementations for Nomad.
- [cosmonic-labs/netreap](https://github.com/cosmonic-labs/netreap) - Netreap is a non-Kubernetes tool for managing Cilium endpoints across a Nomad cluster.
- [davidsbond/homad](https://github.com/davidsbond/homad) - This project manages a HashiCorp Nomad deployment for a personal home lab using Terraform, Vault, and Consul for high availability.
- [istio/istio](https://github.com/istio/istio) - Istio is an open source service mesh that connects, secures, controls, and observes services.
- [kencx/homelab](https://github.com/kencx/homelab) - This project automates the deployment and management of a Hashicorp cluster including Nomad, Consul, and Vault on Proxmox.
- [mr-karan/nomctx](https://github.com/mr-karan/nomctx) - Nomctx is a tool for quickly switching between different Nomad clusters and namespaces.
- [mxab/nacp](https://github.com/mxab/nacp) - NACP is an Admission Controller that acts as a proxy for the Nomad API, enabling validation and mutation of job data.
- [nomad-ops/nomad-ops](https://github.com/nomad-ops/nomad-ops) - Nomad-Ops is an operator for Nomad that reconciles running jobs with Git repositories.
- [robinovitch61/wander](https://github.com/robinovitch61/wander) - Wander is a terminal application designed to interact with HashiCorp Nomad clusters.
- [sepulworld/deadman-check](https://github.com/sepulworld/deadman-check) - Deadman Check is a monitoring tool for ensuring Nomad periodic jobs and Cron tasks run at expected intervals.

## DevOps tools

- [dokku/dokku](https://github.com/dokku/dokku) - Dokku is a Docker-powered platform-as-a-service that simplifies the process of building and managing app lifecycles.
- [star3am/hashiqube](https://github.com/star3am/hashiqube) - HashiQube is a DevOps development lab for running all HashiCorp products in Docker or Vagrant.

## CI / CD

- [jrasell/nomadfiles](https://github.com/jrasell/nomadfiles) - A collection of Nomad job files for deploying applications to a cluster, featuring continuous delivery examples.

## Integrations

- [crazy-max/diun](https://github.com/crazy-max/diun) - Diun is a CLI application that notifies users when a Docker image is updated on a registry.

## Plugins

- [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) - This project is a Nomad task driver that enables the launching of containers using containerd directly.
- [bbopt/NOMAD.jl](https://github.com/bbopt/NOMAD.jl) - NOMAD.jl is a Julia interface for the NOMAD blackbox optimization software.
- [cneira/firecracker-task-driver](https://github.com/cneira/firecracker-task-driver) - A Nomad task driver for managing micro-vms using Firecracker.
- [cneira/jail-task-driver](https://github.com/cneira/jail-task-driver) - This project is a Nomad task driver that leverages FreeBSD jails for container-like environments.
- [hashicorp/nomad-driver-podman](https://github.com/hashicorp/nomad-driver-podman) - A Nomad task driver plugin that helps in sandboxing workloads in Podman containers.
- [hashicorp/terraform-provider-nomad](https://github.com/hashicorp/terraform-provider-nomad) - The HashiCorp Terraform provider for Nomad enables management of Nomad resources using Terraform.
- [jsiebens/nomad-droplets-autoscaler](https://github.com/jsiebens/nomad-droplets-autoscaler) - This project is a plugin for HashiCorp Nomad that allows for the automated scaling of DigitalOcean Droplets.
- [jvirtanen/vim-hcl](https://github.com/jvirtanen/vim-hcl) - This project provides syntax highlighting for the HashiCorp Configuration Language (HCL) used in various HashiCorp tools, including Nomad.
- [mayuresh82/gocast](https://github.com/mayuresh82/gocast) - GoCast is a tool for managing controlled BGP route announcements from a host.

## SDK

- [jrxFive/python-nomad](https://github.com/jrxFive/python-nomad) - A Python client library for Hashicorp Nomad that enables easy interaction with the Nomad API.


## License

[<img src="http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
