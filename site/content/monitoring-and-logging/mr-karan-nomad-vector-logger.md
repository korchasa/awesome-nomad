---
title: "mr-karan/nomad-vector-logger"
type: page
categories: ["Monitoring and Logging"]
tags: [nomad, vector]
---

$ cat description.txt
Nomad-vector-logger is a daemon that generates Vector configuration files for enriched logging in Nomad clusters. It continuously watches for deployments in a Nomad cluster and modifies logging configuration to include metadata such as job name, allocation ID, and node name. This enables better tracking of logs from different tasks and jobs within a Nomad environment. The tool is particularly useful for tasks using raw_exec and exec drivers where logging configuration is inadequate. By aggregating logs and enriching them with metadata, it facilitates a more efficient logging process for observability and troubleshooting purposes.

$ cat links.txt
[Repository](https://github.com/mr-karan/nomad-vector-logger)

$ cat github_stats.txt
![GitHub stars](https://img.shields.io/github/stars/mr-karan/nomad-vector-logger?style=social)


$ cat summary.txt
Nomad-vector-logger is a daemon that generates Vector configuration files for enriched logging in Nomad clusters.


$ ls tags/
[nomad](/tags/nomad/)
[vector](/tags/vector/)
