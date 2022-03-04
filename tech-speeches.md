# Available Speeches

| Status | Title |  Code Sample Folder | Presentation Folder | Speakers | Events |
| :---: |  ------------- | ------------- | ------------- | ------------- | ------------- |
| 🟢 | [Actor Model: Concurrency made simple](#actor-model-concurrency-made-simple) | [Akka.NET Triathlon Race](https://github.com/fbasco81/triathlon-race-demo) | [Presentations](https://github.com/msc-technology/actor-model-concurrency) | [Cristiano Degiorgis](https://linkedin.com/in/cristianodegiorgis), [Francesco Basco](https://linkedin.com/in/francesco-basco-6a827387) | |
| 🟡 | [Async and System Threading Channels](#async-and-system-threading-channels) | [Async](https://github.com/msc-technology/async-await), [Channels](https://github.com/msc-technology/system-threading-channels) |  [Presentations](#tbd) | [Giacomo Agostini](https://linkedin.com/in/giacomo-agostini-4976b717), [Federico Bellia](https://linkedin.com/in/federico-bellia-64a72799) | |
| 🟢 | [Azure App Configuration and Azure Key Vault](#azure-app-configuration-and-azure-key-vault) | [app-configuration-key-vault](https://github.com/sabbadino/app-configuration-key-vault) | [Presentations](https://github.com/sabbadino/app-configuration-key-vault/tree/main/files) | [Enrico Sabbadin](https://linkedin.com/in/enrico-sabbadin-537150) | [Torino .NET Meetup (16/03/2022)](https://www.meetup.com/it-IT/Torino-NET-User-Group/events/284528269/) |
| 🟡 | [How to write SOLID code](#how-to-write-solid-code) | [solid-playground](https://github.com/msc-technology/solid-playground) | [Presentations](https://github.com/msc-technology/solid-playground/tree/main/Presentations) | [Luca Legora](https://linkedin.com/in/lucalegora), [Giuseppe Velocci](https://linkedin.com/in/giuseppe-velocci-92a69969) | |
| 🟡 | [Pub/Sub and Transaction outbox pattern](#pubsub-and-transaction-outbox-pattern) | [transaction-outbox-pattern](https://github.com/msc-technology/transaction-outbox-pattern) | [Presentations](https://github.com/msc-technology/transaction-outbox-pattern) | [Andrea Dutto](https://linkedin.com/in/andreaduttoita), [Vito Poeta](https://linkedin.com/in/vitopoeta) | |
| 🟢 | [Twelve-Factor App](#twelve-factor-app) | N/A | [Presentations](https://github.com/msc-technology/12-factor-app) | [Cristiano Degiorgis](https://linkedin.com/in/cristianodegiorgis) | |

Legenda: 🔴 (Not Started), 🟡 (In Progress), 🟢 (Available), 🔵 (Suggested)

## Actor Model: Concurrency made simple

How to write highly concurrent, reliable and robust application w/o warring about multithreading complexity and  shared memory access. Actor model patterns become very popular these days with the diffusion of distributed systems that are the foundation of cloud computing.
The presentation will first introduce you to the pattern itself and then will share a way to implement it using one of the most popular framework on the market, akka(.net) through a production-ready use case and a demo app explaining the main capabilities of the framework that simplify a lot the pattern implementation.

## Async and System Threading Channels

- Intro to single threading, multithreading, multitasking
- Tasks don’t imply multithreading
- Tasks vs. Promises
- Async/Await vs Tasks management
- Synchronize Threads and Tasks through Channels

## Azure App Configuration and Azure Key Vault

Azure App Configuration and Azure Key Vault
Azure App Configuration is a PAAS service to manage in a centralized store settings and features.
Azure Key Vault is a PAAS service to store secrets, encryption keys and certificates.
Azure App Configuration and Azure Key Vault can be setup as configuration provider for .NET apps (Core and Net framework).

- Azure App Configuration basics, key prefixes and labels
- Azure App Configuration authentication / authorization
  - Access keys, Users, groups, Service Principals, Managed identity
- Azure App Configuration as .NET configuration provider
  - Detect changes
  - Filters
- Features Flags
- Integration in Azure DevOps pipelines
  - Service connection and Az cli Import

- Azure Key Vault
  - Keys, Secrets and Certificates
- Azure Key Vault authentication / authorization
  - Users, groups, Service Principals, Managed identity
  - RBAC, Access Policies
- Azure Key Vault Keys
  - Asymmetric and symmetric (only for HSM)
- Azure Key Vault Secrets as .NET configuration provider
- Azure Key Vault Secrets references in Azure app configuration .NET configuration provider
- Integration in Azure DevOps pipelines
  - Service connection and Az cli
  - Secrets and Git

## How to write SOLID code

The way to design and write understandable, flexible, and maintainable code is rough. SOLID is the best way to reduce complexity and save ourselves a lot of headaches as our applications grow in size and functionalities.

- The SOLID acronym
- Live and Interactive coding session to write SOLID code

## Pub/Sub and Transaction outbox pattern

- Intro to pattern Pub/Sub
- Theory of Transaction outbox pattern
- Demo

## Twelve-Factor App

Coding is not the only activity of a Software Company: integrity, ubiquitous language, and people collaboration are the key to succeed. The Twelve-Factor App is a methodology for building software-as-a-service apps that harmonizes setup automation, supports modern cloud platforms, ensures and enforces consistency among different environments and are ready to scale up with ease.

- The Twelve-Factor App methodology
- Source code for codebase and deploy lifecycle
- How to code, how to deploy and how to operate a Twelve-Factor App
