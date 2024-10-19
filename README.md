# Awesome Nomad

> **Note:** This repository contains an *automatically compiled* list of resources, tools, and information related to ClickHouse.

A curated list of amazingly awesome Nomad tools and shiny things.

Pull requests with additional tools and projects are more than welcome!

- [Knowledge](#knowledge) (3)
    - [Documentation](#documentation) (4)
    - [Tutorial](#tutorial) 
    - [Examples and demos](#examples-and-demos) (1)
    - [Awesome lists](#awesome-lists) (2)
- [Infrastructure setup](#infrastructure-setup) (40)
- [Ops tools](#ops-tools) (7)
- [DevOps tools](#devops-tools) (1)
- [CI / CD](#ci--cd) 
- [Integrations](#integrations) (1)
- [Plugins](#plugins) (8)
- [SDK](#sdk) (1)



## Knowledge

- [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) - Envoy Consul Service Discovery Service integrates Envoy with Consul and Nomad to provide service discovery functionalities.
- [nairnavin/practical-nomad-consul](https://github.com/nairnavin/practical-nomad-consul) - This project is a detailed tutorial for setting up a multi-tier application using Nomad and Consul.
- [thangchung/go-coffeeshop](https://github.com/thangchung/go-coffeeshop) - A practical event-driven microservices demo built with Golang, utilizing Nomad, Consul Connect, Vault, and Terraform for deployment.

### Documentation

- [RemoteCampHQ/how-to-work-remotely](https://github.com/RemoteCampHQ/how-to-work-remotely) - This project is a comprehensive resource for finding remote job opportunities and understanding remote work culture.
- [istio/istio](https://github.com/istio/istio) - Istio is an open source service mesh that connects, secures, controls, and observes services.
- [romantomjak/ansible-roles](https://github.com/romantomjak/ansible-roles) - A collection of Ansible roles and example playbooks for setup on Debian-based hosts.
- [star3am/hashiqube](https://github.com/star3am/hashiqube) - HashiQube is a hands-on DevOps development lab for running all HashiCorp products in Docker or Vagrant.

### Tutorial


### Examples and demos

- [jrasell/nomadfiles](https://github.com/jrasell/nomadfiles) - A collection of Nomad job files for deploying applications to a cluster, featuring continuous delivery examples.

### Awesome lists

- [jippi/awesome-nomad](https://github.com/jippi/awesome-nomad) - Awesome Nomad is a curated list of various tools and utilities that enhance the usability and functionality of HashiCorp Nomad.
- [mentoriaiac/awesome-devops](https://github.com/mentoriaiac/awesome-devops) - A curated list of resources on DevOps fundamentals and tools including Docker, Kubernetes, and Hashicorp Nomad.

## Infrastructure setup

- [42wim/nomadctld](https://github.com/42wim/nomadctld) - nomadctld is an SSH server facilitating interaction with HashiCorp Nomad clusters.
- [FRosner/cluster-broccoli](https://github.com/FRosner/cluster-broccoli) - Cluster Broccoli is a self-service platform for managing Nomad jobs through a RESTful web service and UI.
- [ansible-community/ansible-nomad](https://github.com/ansible-community/ansible-nomad) - Ansible role designed for the installation and configuration of Nomad.
- [astro/skyflake](https://github.com/astro/skyflake) - Skyflake is a project that delivers hyperconverged infrastructure for NixOS, leveraging Nomad for virtual machine management.
- [cvandal/nomad-ui](https://github.com/cvandal/nomad-ui) - Nomad UI is a user interface for HashiCorp's Nomad designed to facilitate the management of Nomad clusters.
- [dokku/dokku-scheduler-nomad](https://github.com/dokku/dokku-scheduler-nomad) - dokku-scheduler-nomad is a plugin for integrating Dokku with Nomad to deploy applications.
- [dsaidgovsg/terraform-modules](https://github.com/dsaidgovsg/terraform-modules) - A set of reusable Terraform modules for provisioning HashiCorp tools, including Nomad, on AWS.
- [eBayClassifiedsGroup/KomPaaS](https://github.com/eBayClassifiedsGroup/KomPaaS) - KomPaaS is a compact PaaS solution built around a small Golang application that incorporates Nomad, Consul, and Fabio for easy deployment.
- [efbar/hashicorp-labs](https://github.com/efbar/hashicorp-labs) - The Hashicorp Labs project facilitates the deployment of a local Hashicorp cluster featuring Vault, Consul, and Nomad for application testing.
- [eschudt/hashistack-digitalocean](https://github.com/eschudt/hashistack-digitalocean) - Hashistack Digitalocean is a Terraform project for setting up a Consul and Nomad cluster on DigitalOcean.
- [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) - This repository provides a Vagrant-based demo setup for running Hashicorp Nomad along with other HashiCorp tools.
- [franckverrot/trek](https://github.com/franckverrot/trek) - Trek is a CLI/ncurses explorer for HashiCorp Nomad clusters.
- [freeCodeCamp/infra](https://github.com/freeCodeCamp/infra) - This project offers infrastructure-as-code resources for managing freeCodeCamp.org's infrastructure.
- [fwkz/dill](https://github.com/fwkz/dill) - `dill` is a cloud-ready L4 TCP proxy with robust support for dynamic listeners and integration with Nomad.
- [hashicorp/damon](https://github.com/hashicorp/damon) - Damon is a terminal dashboard for interacting with HashiCorp Nomad.
- [hashicorp/levant](https://github.com/hashicorp/levant) - Levant is an open-source tool that offers templating and deployment capabilities for HashiCorp Nomad jobs.
- [hyperbadger/nomad-pipeline](https://github.com/hyperbadger/nomad-pipeline) - Nomad Pipeline is a tool to run pipeline-style workloads in HashiCorp's Nomad, allowing for job dependencies management.
- [internetarchive/hind](https://github.com/internetarchive/hind) - HinD is a Docker-based project that simplifies the setup of a Nomad cluster with Consul and Caddy server in a single container.
- [jrasell/nomad-toast](https://github.com/jrasell/nomad-toast) - Nomad Toast is a tool for receiving notifications based on HashiCorp Nomad events.
- [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) - hashi-up is a utility for quickly installing HashiCorp Nomad, Consul, or Vault on remote Linux hosts over SSH.
- [jsiebens/nomad-droplets-autoscaler](https://github.com/jsiebens/nomad-droplets-autoscaler) - This project is a DigitalOcean Droplets target plugin for HashiCorp Nomad Autoscaler.
- [kadalu/kadalu](https://github.com/kadalu/kadalu) - Kadalu provides a lightweight persistent storage solution for Kubernetes, OpenShift, and Nomad using GlusterFS.
- [kangaroot/rootstack-devfactory](https://github.com/kangaroot/rootstack-devfactory) - Devfactory provides an integrated solution using Hashicorp tools for quick VM and container runtime environments.
- [mr-karan/homelab](https://github.com/mr-karan/homelab) - Project providing infrastructure as code and setup scripts for a personal home server using Nomad.
- [mr-karan/nomad-events-sink](https://github.com/mr-karan/nomad-events-sink) - Nomad Events Sink is an agent for collecting and processing Nomad events to external sinks like HTTP.
- [mr-karan/nomad-monitoring](https://github.com/mr-karan/nomad-monitoring) - A complete monitoring solution for Nomad clusters using Grafana dashboards and jobspecs.
- [mr-karan/nomad-vector-logger](https://github.com/mr-karan/nomad-vector-logger) - A daemon that watches Nomad jobs to generate Vector configuration files for enriched logging.
- [mr-karan/nomctx](https://github.com/mr-karan/nomctx) - `nomctx` is a tool for quickly switching between different Nomad clusters and namespaces.
- [multani/docker-nomad](https://github.com/multani/docker-nomad) - This project provides a Docker image for running Hashicorp Nomad.
- [mxab/nacp](https://github.com/mxab/nacp) - NACP is an Admission Controller that acts as a proxy for the Nomad API, enabling validation and mutation of job data.
- [myENA/consul-backinator](https://github.com/myENA/consul-backinator) - Consul-backinator is a command line utility for backing up and restoring Consul data, including key-value pairs and ACL tokens.
- [picatz/terraform-google-nomad](https://github.com/picatz/terraform-google-nomad) - Terraform module for setting up Nomad clusters with Consul on Google Cloud Platform.
- [robinovitch61/wander](https://github.com/robinovitch61/wander) - Wander is a terminal application designed to interact with HashiCorp Nomad clusters.
- [sagarrakshe/nomad-dtree](https://github.com/sagarrakshe/nomad-dtree) - nomad-dtree is a tool that facilitates dependency management between Nomad jobs.
- [seatgeek/nomad-firehose](https://github.com/seatgeek/nomad-firehose) - The `nomad-firehose` is a tool that facilitates the monitoring of changes in Nomad job, allocation, nodes, and evaluations, and pushes those changes to various outputs.
- [seatgeek/nomad-helper](https://github.com/seatgeek/nomad-helper) - Nomad-helper is a Go-based tool designed to enhance the usability of HashiCorp Nomad at scale.
- [thangchung/coffeeshop-modular](https://github.com/thangchung/coffeeshop-modular) - A modular .NET coffee shop application that can be started with docker-compose and integrates with HashiCorp Nomad.
- [thangchung/coffeeshop-on-nomad](https://github.com/thangchung/coffeeshop-on-nomad) - The .NET coffeeshop application showcases the use of Docker, Nomad, and Consul Connect for running microservices.
- [tristanpemble/nix-nomad](https://github.com/tristanpemble/nix-nomad) - A tool for generating HashiCorp Nomad job definitions using Nix.
- [zerodha/nomad-cluster-setup](https://github.com/zerodha/nomad-cluster-setup) - This project provides Terraform modules to deploy a HashiCorp Nomad cluster on AWS.

## Ops tools

- [aldoborrero/hashi-homelab](https://github.com/aldoborrero/hashi-homelab) - Hashi Homelab is a repository that provides Nomad recipes for various open source projects designed for use on a Nomad, Consul, and Vault-enabled Intel Nuc cluster.
- [assareh/tfc-agent](https://github.com/assareh/tfc-agent) - This repository provides examples for using the Terraform Cloud Agent, a remote runner designed for Terraform Cloud Business and Enterprise, with specific implementations for Nomad.
- [cosmonic-labs/netreap](https://github.com/cosmonic-labs/netreap) - Netreap is a non-Kubernetes tool for managing Cilium endpoints across a Nomad cluster.
- [davidsbond/homad](https://github.com/davidsbond/homad) - This project manages a HashiCorp Nomad deployment for a personal home lab using Terraform, Vault, and Consul for high availability.
- [kencx/homelab](https://github.com/kencx/homelab) - This project automates the deployment and management of a Hashicorp cluster including Nomad, Consul, and Vault on Proxmox.
- [nomad-ops/nomad-ops](https://github.com/nomad-ops/nomad-ops) - Nomad-Ops is an operator for Nomad that reconciles running jobs with Git repositories.
- [sepulworld/deadman-check](https://github.com/sepulworld/deadman-check) - Deadman Check is a monitoring tool for ensuring Nomad periodic jobs and Cron tasks run at expected intervals.

## DevOps tools

- [dokku/dokku](https://github.com/dokku/dokku) - Dokku is a Docker-powered platform-as-a-service that simplifies the process of building and managing app lifecycles.

## CI / CD


## Integrations

- [crazy-max/diun](https://github.com/crazy-max/diun) - Diun is a CLI application that notifies users when a Docker image is updated on a registry.

## Plugins

- [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) - This project is a Nomad task driver that enables the launching of containers using containerd directly.
- [bbopt/NOMAD.jl](https://github.com/bbopt/NOMAD.jl) - NOMAD.jl is a Julia interface for the NOMAD blackbox optimization software.
- [cneira/firecracker-task-driver](https://github.com/cneira/firecracker-task-driver) - A Nomad task driver for managing micro-vms using Firecracker.
- [cneira/jail-task-driver](https://github.com/cneira/jail-task-driver) - This project is a Nomad task driver that leverages FreeBSD jails for container-like environments.
- [hashicorp/nomad-driver-podman](https://github.com/hashicorp/nomad-driver-podman) - A Nomad task driver plugin that helps in sandboxing workloads in Podman containers.
- [hashicorp/terraform-provider-nomad](https://github.com/hashicorp/terraform-provider-nomad) - The HashiCorp Terraform provider for Nomad enables management of Nomad resources using Terraform.
- [jvirtanen/vim-hcl](https://github.com/jvirtanen/vim-hcl) - This project provides syntax highlighting for the HashiCorp Configuration Language (HCL) used in various HashiCorp tools, including Nomad.
- [mayuresh82/gocast](https://github.com/mayuresh82/gocast) - GoCast is a tool for managing controlled BGP route announcements from a host.

## SDK

- [jrxFive/python-nomad](https://github.com/jrxFive/python-nomad) - A Python client library for Hashicorp Nomad that enables easy interaction with the Nomad API.


## License

https://creativecommons.org/publicdomain/zero/1.0/[image:http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg[CC0]]
