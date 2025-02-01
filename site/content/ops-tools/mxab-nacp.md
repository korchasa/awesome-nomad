---
title: "mxab/nacp"
type: page
categories: ["Ops tools"]
tags: [admission-controller, devsecops, nomad, notary, notation, opa]
---

$ cat description.txt
NACP is an Admission Controller that acts as a proxy for the Nomad API, enabling validation and mutation of job data. It intercepts API calls, transforming job data from HCL to JSON and returning errors when they arise. The project supports validation through embedded OPA rules and webhooks, as well as mutation capabilities that modify job data via configured mutators. The NACP server can be customized for various operational needs, facilitating smooth job management within the Nomad environment.

$ cat links.txt
[Repository](https://github.com/mxab/nacp)

$ cat github_stats.txt
![GitHub stars](https://img.shields.io/github/stars/mxab/nacp?style=social)


$ cat summary.txt
NACP is an Admission Controller that acts as a proxy for the Nomad API, enabling validation and mutation of job data.


$ ls tags/
[admission-controller](/tags/admission-controller/)
[devsecops](/tags/devsecops/)
[nomad](/tags/nomad/)
[notary](/tags/notary/)
[notation](/tags/notation/)
[opa](/tags/opa/)
