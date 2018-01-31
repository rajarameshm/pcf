# pcf
pcf lab and docs

virtualization benifits:
1. resource utilization
2. Isolation

Linux Kerner Features:
1. c group - 2 cores, 4 gb etc.,
2. Name Spaces - n/w|file|pid, 

Host > C group > Container > application

Docker
Docker Client, Docker Server, Docker Container, Docker Container Manager,Docker Image, Docker Registry, Kubernetes

Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.

etcd - Distributed reliable key-value store for the most critical data of a distributed system.
CF uses etcd to store image and its definitions


network.pivotal.io
search for manager

Pivotal Cloud Foundry Operations Manager

Pivotal Cloud Foundry Ops Manager for vSphere - 2.0-build.249
2.94 GB2.0-build.249
https://network.pivotal.io/products/ops-manager/


PWS
http://run.pivotal.io/

Apps Manager
https://console.run.pivotal.io/

API
api.run.pivotal.io


Apps Manager
console.run.pivotal.io


https://papertrailapp.com/systems/mahalogs/events

Microservices - 12 Factor App Methodology

Eureka/Consul for discovery

Hystrix > CircuitBreaker - for fall-back mechanism
Service to service GateWay is not required, should go through Clinet Load Balancer (Ribbon)
for external access, it has to go through GateWay (Jule/APIGEE)



