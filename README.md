# Awesome Nomad

A curated list of amazingly awesome Nomad tools and shiny things.

Pull requests with additional tools and projects are more than welcome!

## Tutorials / Examples / Demos

- [aldoborrero/hashi-homelab](https://github.com/aldoborrero/hashi-homelab) - Hashicorp Homelab is a collection of nomad recipes related to several Open Source projects that I use on my own nomad + consul + vault + Intel Nuc cluster.
- [angrycub/nomad_example_jobs](https://github.com/angrycub/nomad_example_jobs) - Jobs and resources that I have used to experiment with Nomad
- [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) - A tutorial on how to get Envoy running on Nomad and using Envoy's SDS(Service Discovery Service) to access Consul API.
- [cyriltovena/observability-nomad](https://github.com/cyriltovena/observability-nomad) - This is a set of examples on how to add Observability to Nomad Applications
- [hashicorp/field-workshops-nomad](https://github.com/hashicorp/field-workshops-nomad) - Slides, Instructor Guides and Instruqt Tracks for Nomad Field Workshops
- [hashicorp/nomad-guides](https://github.com/hashicorp/nomad-guides) - Example usage of HashiCorp Nomad
- [jrasell/nomadfiles](https://github.com/jrasell/nomadfiles) A collection of Nomad job files for deploying applications to a cluster.
- [kelseyhightower/hashiconf-eu-2016](https://github.com/kelseyhightower/hashiconf-eu-2016) - Repo from a talk on building out a deployment with GCE/Consul/Nomad/Fabio loadbalancer. Check out the talk on youtube: https://www.youtube.com/watch?v=Nosa5-xcATw
- [microservices-demo/microservices-demo.github.io](https://github.com/microservices-demo/microservices-demo.github.io) - The Microservices Demo website.
- [mr-karan/hydra](https://github.com/mr-karan/hydra) - Infra-as-code for my personal home server setup
- [perrymanuk/hashi-homelab](https://github.com/perrymanuk/hashi-homelab) Job files for a small lightweight homelab based on nomad and consul from hashicorp.
- [pete0emerson/hashipoc](https://github.com/pete0emerson/hashipoc) - A Vagrant driven example of getting Consul / Vault / Nomad up and running with a sample app deployed

## Provisioning

- [hashicorp/terraform-aws-nomad](https://github.com/hashicorp/terraform-aws-nomad) - A Terraform Module for how to run Nomad on AWS using Terraform and Packer
- [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) - bootstrap HashiCorp Consul, Nomad, or Vault over SSH < 1 minute
- [numkem/nomad-spk](https://github.com/numkem/nomad-spk) - spk (Synology package) to install Hashicorp's nomad scheduler into Synology NAS

## System jobs

- [hashicorp/nomad-autoscaler](https://github.com/hashicorp/nomad-autoscaler) - Nomad Autoscaler brings autoscaling to your Nomad workloads.
- [istio/istio](https://github.com/istio/istio) - Connect, secure, control, and observe services.
- [jippi/hashi-ui](https://github.com/jippi/hashi-ui) - Interface for Consul & Nomad by HashiCorp, live stream of data, fast search and resource visualization per cluster or client.
- [trivago/scalad](https://github.com/trivago/scalad) - Scalad is a nomad horizontal scaler that can be setup from each job Taskgroup meta stanza based on external metrics.

## Ops tools

- [ansible-community/ansible-nomad](https://github.com/ansible-community/ansible-nomad) - :watch: Ansible role for Nomad
- [dsaidgovsg/terraform-modules](https://github.com/dsaidgovsg/terraform-modules) - Reusable Terraform modules
- [hashicorp/terraform-provider-nomad](https://github.com/hashicorp/terraform-provider-nomad) - Terraform Nomad provider
- [input-output-hk/bitte](https://github.com/input-output-hk/bitte) - Nix Ops for Terraform, Consul, Vault, Nomad
- [jrasell/nomad-toast](https://github.com/jrasell/nomad-toast) - A tool for receiving notifications based on HashiCorp Nomad events.
- [picatz/terraform-google-nomad](https://github.com/picatz/terraform-google-nomad) - 📗 Terraform Module for Nomad clusters on GCP
- [seatgeek/nomad-firehose](https://github.com/seatgeek/nomad-firehose) - Go binary that "tails" API endpoints and emit messages for each changed resource to RabbitMQ, AWS kinesis or stdout.
- [seatgeek/nomad-helper](https://github.com/seatgeek/nomad-helper) - Simple helper binary to allow you to reevaluate all jobs, drain an node (and wait for all allocations to stop), force a garbage collection, export / import job task group counts in YAML format.
- [sepulworld/deadman-check](https://github.com/sepulworld/deadman-check) - A monitoring companion for Nomad periodic jobs that alerts if periodic isn't running at the expected interval.

## DevOps tools

- [42wim/nomadctld](https://github.com/42wim/nomadctld) - Ssh server with ability to exec/attach/logs/tail/stop hashicorp nomad containers.
- [ataccama/nomad-deploy](https://github.com/ataccama/nomad-deploy) - Python3 script that renders a Jinja2 template, plans and registers job. Installable as an executable from [pypi.org](https://pypi.org/project/nomad-deploy/).
- [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) - Vagrant based demo setup for running Hashicorp Nomad
- [jvirtanen/vim-hcl](https://github.com/jvirtanen/vim-hcl) - Syntax highlighting for HashiCorp Configuration Language (HCL)
- [smintz/nomadgen](https://github.com/smintz/nomadgen) - Define your Nomad jobspecs using Python.

## CI / CD

- [data-science-platform/cluster-broccoli](https://github.com/data-science-platform/cluster-broccoli) - Cluster Broccoli is a RESTful web service + UI to manage Nomad jobs through a self service application. Jobs are defined based on templates, allowing for a selectable amount of customization.
- [fortress-shell](https://github.com/fortress-shell/fortress-shell) - Self-written CI/CD SaaS based on Hashicorp Nomad
- [getnelson/nelson](https://getnelson.io/) - Lights-out deployment and lifecycle manager for Nomad (and other pluggable schedulers). Fully integrated with Vault and Consul. Optionally can act as a control plane for your traffic routing teir.
- [hashicorp/levant](https://github.com/hashicorp/levant) - An open source templating and deployment tool for HashiCorp Nomad jobs
- [jenkinsci/nomad-plugin](https://github.com/jenkinsci/nomad-plugin) - Jenkins plugin to allow using Nomad Jobs to scale out Jenkins build slaves.
- [screwdrivercd/nomad](http://screwdriver.cd/) - Use nomad to schedule and execute workflows triggered by an scm (github/bitbucket).
- [ValFadeev/rundeck-nomad-plugin](https://github.com/ValFadeev/rundeck-nomad-plugin) - A Rundeck plugin for authoring and running Nomad jobs by operators or in automated deployment pipelines.

## Plugins

- [cneira/firecracker-task-driver](https://github.com/cneira/firecracker-task-driver) - nomad task driver that uses firecracker to start micro-vms
- [cneira/jail-task-driver](https://github.com/cneira/jail-task-driver) - Task driver that uses FreeBSD jails
- [pascomnet/nomad-driver-podman](https://github.com/pascomnet/nomad-driver-podman) - A nomad task driver for [podman containers](https://podman.io)
- [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) - A nomad task driver for [containerd](https://containerd.io). Documentation on [`nomadproject.io`](https://www.nomadproject.io/docs/drivers/external/containerd).
- [Roblox/nomad-driver-iis](https://github.com/Roblox/nomad-driver-iis) - Nomad task driver for running windows IIS services.
- [trivago/nomad-pot-driver](https://github.com/trivago/nomad-pot-driver) - Plugin for managing FreeBSD Jails with Hashicorp's Nomad

## SDK

- [hashicorp/nomad-java-sdk](https://github.com/hashicorp/nomad-java-sdk) - A Java SDK for interfacing with HashiCorp's Nomad
- [jrxFive/python-nomad](https://github.com/jrxFive/python-nomad) - Client library Hashicorp Nomad