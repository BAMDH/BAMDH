# Hi, I'm Brandon Mora 👋

Computer Engineering student at **Tecnológico de Costa Rica**, focused on **database design, distributed systems, and cloud infrastructure**. I have experience designing data models, developing microservice-based systems, and deploying applications on Kubernetes using Helm. I've also worked on full-stack web applications and native Android projects.

My main interests are **infrastructure design and process automation**.

## Tech Stack
| Area | Tools |
|---|---|
| **Data modeling & databases** | Relational design, PostgreSQL (Supabase, Row Level Security), MariaDB, Firebase (Firestore) |
| **Infrastructure & DevOps** | Kubernetes, Helm, Docker, docker-compose, Ingress, StatefulSets, nftables |
| **Observability** | Prometheus, Grafana |
| **Messaging** | RabbitMQ |
| **Backend** | Python (Flask), Node.js (Express), C, Java, SQL |
| **Frontend & mobile** | React, TypeScript, Angular, Tailwind CSS, Bootstrap, Android (Java) |
| **Networking** | DNS (RFC 1035), SIP/VoIP, NGINX, Apache |


## Featured Projects

### [Data Migration Platform](https://github.com/BAMDH/Data-Migration-Platform)
A microservice-based pipeline for data migration and enrichment, deployed on Kubernetes. Services communicate through RabbitMQ, with Prometheus and Grafana providing monitoring and observability.

**Contributions:** Developed the regex-processing service, including its RabbitMQ consumer, metrics, and unit tests; implemented Helm charts and contributed to architecture decisions.

`Python` `RabbitMQ` `Kubernetes` `Helm` `Prometheus` `Grafana`

### [DNS Server](https://github.com/BAMDH/DNS-server)
A distributed DNS system featuring a C-based interceptor implementing DNS protocol handling, a Python API, a health-checker deployed as a StatefulSet, and a React administration interface. Supports single-target, multi-value, weighted, round-trip, and geolocation-based routing.

**Contributions:** Developed the API and Firebase data layer and implemented Helm charts.

`C` `Python` `React` `Firebase` `Kubernetes`

### [Geo-aware Caching](https://github.com/BAMDH/Geo-aware-caching)
A geolocation-aware DNS and caching system designed to route users to the nearest regional cache.

**Contributions:** Developed the C cache-management module, implementing LRU, LFU, FIFO, MRU, and Random eviction policies.

`C` `DNS` `Caching` `Kubernetes`

### [Kubernetes Network Infrastructure](https://github.com/BAMDH/Kubernetes-network-infrastructure)
Infrastructure as code using Helm, featuring public and private namespaces, a custom nftables router, an Apache-based ingress controller, NGINX backends, and a FreeSWITCH SIP server.

**Contributions:** Implemented the router, developed Helm charts, and created functional tests.

`Kubernetes` `Helm` `nftables` `NGINX` `FreeSWITCH`

### [CrowdSpark Web](https://github.com/BAMDH/CrowdSparkWeb) · [CrowdSpark Android](https://github.com/BAMDH/CrowdSpark-Android)
A crowdfunding platform with an Angular web application and a native Android client sharing a Firebase backend.

`Angular` `Java` `Firebase`

## Client work 

**Course-management platform for a training center** (academic project for a real client). I designed the PostgreSQL database (16 tables, role-based Row Level Security policies, audit log) and built the complete administrator module in React and TypeScript on Supabase, integrated with the student and teacher modules.
