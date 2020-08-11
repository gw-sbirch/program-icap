# program-icap
Documentation repository for the Glasswall ICAP program

# Associated Repos

## PoC
[filetrust/c-icap](https://github.com/filetrust/c-icap) : This repo contains the proof of concept implementation. The ICAP solution is deployed within a docker container, with the Glasswall SDK integrated.

## Cloud Deployment
The cloud deployment is implemented through the integration of the services provided by a number of repos.

[filetrust/mvp-icap-service](https://github.com/filetrust/mvp-icap-service) This provides the ICAP Server and Glasswall ICAP Resource. These components are responsible for providing the ICAP interface and submitting the content received in ICAP Requests for processing through the Glasswall products.

[filetrust/mvp-icap-cloud](https://github.com/filetrust/mvp-icap-cloud) This provides the Orchestrator that co-ordinates the processing of content received by the ICAP Server.

## Threat Model
The program's Threat Model is recorded as [ICAP Threat Model Cloud Deployment](https://glasswall.atlassian.net/browse/THREATMODL-3)
The model's diagram is [here](https://app.lucidchart.com/invitations/accept/43e0cb76-052f-486c-8bfd-166f4ad4ea4f)
