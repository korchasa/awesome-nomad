# Awesome Nomad

> **Note:** This repository contains an automatically compiled list of frameworks, tools, and resources related to HashiCorp Nomad.

A curated list of awesome HashiCorp Nomad and HashiCorp Nomad-related software.


Table of Contents:
- [Documentation, examples, demos, and awesome lists](#documentation,-examples,-demos,-and-awesome-lists) (3)

- [Demo and Learning Resources](#demo-and-learning-resources) (5)

- [Infrastructure setup](#infrastructure-setup) 
    - [Automation and Infrastructure Management](#automation-and-infrastructure-management) (14)

    - [Deployment and Cluster Setup](#deployment-and-cluster-setup) (9)

    - [Integrated Solutions and Applications](#integrated-solutions-and-applications) (2)

    - [Monitoring and Logging](#monitoring-and-logging) (7)

    - [Tools and Utilities](#tools-and-utilities) (3)

    - [User Interfaces and Dashboards](#user-interfaces-and-dashboards) (4)


- [DevOps tools](#devops-tools) (4)

- [Integrations](#integrations) (1)

- [Plugins](#plugins) (7)

- [SDK](#sdk) (1)




## Documentation, examples, demos, and awesome lists

- [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) (★68 Go) - Envoy-consul-sds is a service that implements Envoy's Service Discovery Service API on top of Consul's health endpoint API to enable dynamic service discovery and proxying for applications running on HashiCorp Nomad.
- [jippi/awesome-nomad](https://github.com/jippi/awesome-nomad) (★890 ) - A curated list of tools, plugins, utilities, and resources for enhancing and managing HashiCorp Nomad deployments and workflows.
- [thangchung/coffeeshop-modular](https://github.com/thangchung/coffeeshop-modular) (★48 C#) - .NET coffee shop application with a modular architecture, containerized and deployable using HashiCorp Nomad.


## Demo and Learning Resources

- [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) (★131 HCL) - A Vagrant-based demo environment for running and exploring HashiCorp Nomad, Consul, and Vault with integrated service discovery, workload orchestration, and monitoring tools.
- [nairnavin/practical-nomad-consul](https://github.com/nairnavin/practical-nomad-consul) (★59 HCL) - A practical tutorial and guide for deploying a realistic multi-tier Spring Boot Petclinic application using HashiCorp Nomad and Consul with service mesh, ingress and terminating gateways, load balancing, and secure communication.
- [star3am/hashiqube](https://github.com/star3am/hashiqube) (★123 JavaScript) - HashiQube is an all-in-one hands-on DevOps lab that runs all HashiCorp products including Nomad, providing a versatile environment for learning, practicing, and demonstrating infrastructure and security tools in cloud or local setups.
- [thangchung/coffeeshop-on-nomad](https://github.com/thangchung/coffeeshop-on-nomad) (★114 C#) - A .NET microservices coffeeshop application deployed and orchestrated on HashiCorp Nomad with Consul Connect for service mesh and Docker containers.
- [thangchung/go-coffeeshop](https://github.com/thangchung/go-coffeeshop) (★4257 Go) - go-coffeeshop is an event-driven microservices demo application built with Golang, deployed using HashiCorp Nomad, Consul Connect, Vault, and Terraform, demonstrating modern microservices architecture and deployment practices.


## Infrastructure setup


### Automation and Infrastructure Management

- [ansible-community/ansible-nomad](https://github.com/ansible-community/ansible-nomad) (★305 Jinja) - Ansible-Nomad is an Ansible role that automates the installation, configuration, and management of HashiCorp Nomad clusters, supporting both development and production environments.
- [astro/skyflake](https://github.com/astro/skyflake) (★224 Nix) - Skyflake is a NixOS-based hyperconverged infrastructure solution that uses HashiCorp Nomad to manage dynamic virtual machines, enabling GitOps-style deployments and cluster management.
- [bitrockteam/caravan](https://github.com/bitrockteam/caravan) (★49 Shell) - Caravan is a modular platform builder based on the HashiCorp stack, providing Terraform modules and projects for deploying and managing cloud infrastructure and applications, including Nomad configuration.
- [cosmonic-labs/netreap](https://github.com/cosmonic-labs/netreap) (★136 Go) - Netreap is a Cilium controller designed to manage Cilium networking and policies within Nomad clusters, providing Kubernetes-independent cluster management and policy synchronization.
- [davidsbond/homad](https://github.com/davidsbond/homad) (★44 HCL) - Homad is a comprehensive HashiCorp Nomad homelab configuration repository that automates deployment, management, and upgrades of a high-availability Nomad cluster with integrated Vault, Consul, and various popular services using Terraform and CI workflows.
- [dsaidgovsg/terraform-modules](https://github.com/dsaidgovsg/terraform-modules) (★78 HCL) - A collection of reusable Terraform modules to provision and manage HashiCorp Nomad, Consul, and Vault clusters on AWS, enabling secure and scalable cloud infrastructure deployment.
- [hyperbadger/nomad-pipeline](https://github.com/hyperbadger/nomad-pipeline) (★42 Go) - Nomad Pipeline enables pipeline-style workloads with job dependencies in HashiCorp Nomad, allowing sequential and parallel task execution and advanced workflow orchestration.
- [jonasvinther/nomad-gitops-operator](https://github.com/jonasvinther/nomad-gitops-operator) (★86 Go) - Nomoporator is a GitOps operator that automates the deployment and synchronization of HashiCorp Nomad jobs using Git repositories or local file systems, supporting secure and flexible configuration.
- [mr-karan/homelab](https://github.com/mr-karan/homelab) (★270 HTML) - Hydra is an infrastructure-as-code project for managing a personal home server using HashiCorp Nomad, Consul, and other tools to automate and orchestrate various services.
- [ngine-io/chaotic](https://github.com/ngine-io/chaotic) (★70 Python) - Chaotic is a chaos engineering tool for cloud environments with advanced support for HashiCorp Nomad, enabling controlled failure simulations to test infrastructure resilience.
- [nomad-ops/nomad-ops](https://github.com/nomad-ops/nomad-ops) (★91 TypeScript) - Nomad-Ops is a GitOps operator for HashiCorp Nomad that reconciles running jobs with Git repositories to automate and simplify Nomad job management.
- [sagarrakshe/nomad-dtree](https://github.com/sagarrakshe/nomad-dtree) (★50 Go) - nomad-dtree is a tool that manages dependencies and execution order between HashiCorp Nomad jobs, enabling reliable deployment of microservices with pre- and post-hook job support.
- [seatgeek/nomad-helper](https://github.com/seatgeek/nomad-helper) (★156 Go) - nomad-helper is a set of tools designed to simplify and enhance the management and operational tasks of HashiCorp Nomad clusters at scale.
- [tristanpemble/nix-nomad](https://github.com/tristanpemble/nix-nomad) (★71 Nix) - nix-nomad is a tool to generate and manage HashiCorp Nomad job JSON files using NixOS modules, enabling modular and scalable deployment of Nomad jobs across multiple environments.


### Deployment and Cluster Setup

- [aldoborrero/hashi-homelab](https://github.com/aldoborrero/hashi-homelab) (★232 Shell) - Hashi Homelab is a collection of Nomad job recipes and Packer VM images designed to deploy and manage a variety of open-source services on a Nomad + Consul + Vault cluster, optimized for Intel NUC homelab environments.
- [efbar/hashicorp-labs](https://github.com/efbar/hashicorp-labs) (★34 HCL) - A toolkit to deploy and manage a local HashiCorp cluster with Vault, Consul, and Nomad for testing applications, including serverless functions with OpenFaaS integration.
- [eschudt/hashistack-digitalocean](https://github.com/eschudt/hashistack-digitalocean) (★47 HCL) - Terraform project to deploy and manage a secure HashiCorp stack including Nomad, Consul, and Vault clusters on DigitalOcean with automated setup and network security.
- [internetarchive/hind](https://github.com/internetarchive/hind) (★62 Shell) - HinD is a single-container mini cluster combining Nomad, Consul, and Caddyserver to orchestrate containerized workloads with dynamic reverse proxy and automatic HTTPS in a Podman environment.
- [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) (★690 Go) - hashi-up is a lightweight utility that automates the installation and clustering of HashiCorp Consul, Nomad, or Vault on remote Linux hosts over SSH in under one minute.
- [kencx/homelab](https://github.com/kencx/homelab) (★176 YAML) - kencx/homelab is an infrastructure-as-code project for automated deployment and management of a HashiCorp Nomad, Consul, and Vault cluster on Proxmox using Packer, Terraform, and Ansible.
- [multani/docker-nomad](https://github.com/multani/docker-nomad) (★96 Shell) - This project provides a Docker image to run the HashiCorp Nomad scheduler in containerized environments, facilitating easy deployment and testing of Nomad clusters using Docker.
- [picatz/terraform-google-nomad](https://github.com/picatz/terraform-google-nomad) (★78 HCL) - Terraform module for deploying and managing secure Nomad clusters with Consul service mesh on Google Cloud Platform.
- [zerodha/nomad-cluster-setup](https://github.com/zerodha/nomad-cluster-setup) (★153 HCL) - Terraform modules and Packer scripts to deploy and manage scalable HashiCorp Nomad clusters on AWS using Auto Scaling Groups, custom AMIs, and optional load balancing.


### Integrated Solutions and Applications

- [eBayClassifiedsGroup/KomPaaS](https://github.com/eBayClassifiedsGroup/KomPaaS) (★47 ) - KomPaaS is a compact, containerized Platform as a Service proof of concept integrating HashiCorp Nomad, Consul, Fabio, and Nomad-UI to provide a lightweight PaaS environment for workload orchestration and service discovery.
- [kadalu/kadalu](https://github.com/kadalu/kadalu) (★730 Python) - Kadalu is a lightweight persistent storage solution for container orchestration platforms like Kubernetes, OpenShift, and Nomad, using GlusterFS to provide scalable and reliable storage services.


### Monitoring and Logging

- [jrasell/nomad-toast](https://github.com/jrasell/nomad-toast) (★49 Go) - Nomad Toast is an open-source tool that provides real-time notifications based on HashiCorp Nomad events, enhancing observability and operational awareness through Slack integration.
- [kangaroot/rootstack-devfactory](https://github.com/kangaroot/rootstack-devfactory) (★40 Jinja) - Rootstacks Devfactory is a solution that provides a secure, observable, and integrated runtime environment for containers, native applications, and VMs using HashiCorp Nomad and related tools.
- [mr-karan/nomad-events-sink](https://github.com/mr-karan/nomad-events-sink) (★53 Go) - Nomad Events Sink is an event collection agent that processes HashiCorp Nomad events and forwards them to external sink providers like HTTP for monitoring, alerting, and analysis.
- [mr-karan/nomad-monitoring](https://github.com/mr-karan/nomad-monitoring) (★61 HCL) - A collection of jobspecs and Grafana dashboards for comprehensive end-to-end monitoring of HashiCorp Nomad clusters, utilizing Prometheus metrics and VictoriaMetrics for efficient data collection and storage.
- [mr-karan/nomad-vector-logger](https://github.com/mr-karan/nomad-vector-logger) (★57 Go) - Nomad-vector-logger is a daemon that monitors Nomad cluster jobs and generates Vector configuration files to collect logs enriched with Nomad metadata for improved centralized logging and observability.
- [seatgeek/nomad-firehose](https://github.com/seatgeek/nomad-firehose) (★114 Go) - Nomad-firehose is a tool that streams real-time HashiCorp Nomad cluster events such as job, allocation, node, and evaluation changes to various messaging systems and sinks for enhanced observability and automation.
- [sepulworld/deadman-check](https://github.com/sepulworld/deadman-check) (★58 Ruby) - Deadman Check is a monitoring tool for HashiCorp Nomad periodic jobs that alerts users if jobs fail to run at their expected intervals, using Consul for tracking and supporting Slack and AWS SNS for notifications.


### Tools and Utilities

- [42wim/nomadctld](https://github.com/42wim/nomadctld) (★68 Go) - nomadctld is an SSH server that provides controlled user access to manage and monitor HashiCorp Nomad jobs and containers securely.
- [Kamilcuk/nomad-tools](https://github.com/Kamilcuk/nomad-tools) (★35 Python) - Nomad-tools is a set of command-line tools and utilities designed to simplify and enhance interaction with the HashiCorp Nomad scheduling solution, providing features for job deployment, monitoring, node attribute management, and CI/CD integration.
- [franckverrot/trek](https://github.com/franckverrot/trek) (★33 Go) - Trek is a CLI and ncurses-based explorer tool designed to manage and explore HashiCorp Nomad clusters, providing detailed insights into jobs, task groups, allocations, and tasks with customizable output formats.


### User Interfaces and Dashboards

- [FRosner/cluster-broccoli](https://github.com/FRosner/cluster-broccoli) (★60 Scala) - Cluster Broccoli is a self-service web service and UI for managing HashiCorp Nomad jobs through customizable templates and a RESTful API.
- [cvandal/nomad-ui](https://github.com/cvandal/nomad-ui) (★32 JavaScript) - Nomad UI is a cross-platform user interface built with .NET Core and React for managing HashiCorp Nomad clusters, now discontinued after Nomad 0.7 introduced its own built-in UI.
- [hashicorp/damon](https://github.com/hashicorp/damon) (★443 Go) - Damon is a terminal user interface (TUI) that provides an interactive dashboard for managing and monitoring HashiCorp Nomad resources such as Jobs, Deployments, and Allocations.
- [robinovitch61/wander](https://github.com/robinovitch61/wander) (★455 Go) - Wander is a terminal-based TUI application for efficiently managing and monitoring HashiCorp Nomad clusters with features like live log tailing, event monitoring, and administrative controls.



## DevOps tools

- [hashicorp/levant](https://github.com/hashicorp/levant) (★837 Go) - Levant is an open source templating and deployment tool that provides realtime feedback and detailed failure messages for HashiCorp Nomad job deployments.
- [jrasell/nomadfiles](https://github.com/jrasell/nomadfiles) (★124 Groovy) - A collection of HashiCorp Nomad job files and deployment scripts designed for continuous delivery and automated multi-environment deployments using Jenkins and Levant.
- [mr-karan/nomctx](https://github.com/mr-karan/nomctx) (★54 Go) - Nomctx is a command-line tool that simplifies and accelerates switching between multiple HashiCorp Nomad clusters and namespaces by managing environment variables and authentication contexts efficiently.
- [mxab/nacp](https://github.com/mxab/nacp) (★44 Go) - NACP is a proxy for the HashiCorp Nomad API that enables policy-driven validation and mutation of job data using Open Policy Agent and webhooks to enforce organizational policies before job submission.


## Integrations

- [fwkz/dill](https://github.com/fwkz/dill) (★44 Go) - fwkz/dill is a cloud-ready L4 TCP proxy with dynamic listener support, enabling seamless load balancing and routing of dynamic backends, including integration with HashiCorp Nomad for service discovery.


## Plugins

- [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) (★228 Go) - Nomad-driver-containerd is a Nomad task driver that enables launching containers directly using containerd, providing a Docker-free container orchestration solution within Nomad.
- [Roblox/nomad-driver-iis](https://github.com/Roblox/nomad-driver-iis) (★56 Go) - Nomad-driver-iis is a Nomad task driver plugin by Roblox for orchestrating Windows IIS website tasks, enabling automated management of IIS application pools and sites within Nomad clusters.
- [cneira/firecracker-task-driver](https://github.com/cneira/firecracker-task-driver) (★152 Go) - A Nomad task driver that enables the creation and management of Firecracker micro-virtual machines within the Nomad orchestration platform.
- [cneira/jail-task-driver](https://github.com/cneira/jail-task-driver) (★39 Go) - A HashiCorp Nomad task driver plugin that enables running tasks inside FreeBSD jails, providing native containerization and resource control for FreeBSD environments.
- [dokku/dokku-scheduler-nomad](https://github.com/dokku/dokku-scheduler-nomad) (★34 Shell) - dokku-scheduler-nomad is a Dokku plugin that integrates Nomad as a scheduler for deploying applications within a Nomad cluster environment.
- [hashicorp/nomad-driver-podman](https://github.com/hashicorp/nomad-driver-podman) (★247 Go) - A Nomad task driver plugin that enables sandboxing and management of workloads in Podman containers with advanced resource and network configuration features.
- [hashicorp/terraform-provider-nomad](https://github.com/hashicorp/terraform-provider-nomad) (★147 Go) - Terraform Nomad provider plugin maintained by HashiCorp enabling infrastructure as code management of Nomad resources through Terraform.


## SDK

- [jrxFive/python-nomad](https://github.com/jrxFive/python-nomad) (★142 Python) - python-nomad is a Python client library that provides a comprehensive interface to interact with HashiCorp Nomad's API for managing and automating cluster and workload scheduling tasks.



## License

[<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
