<div align="center">

# MADLAB

**Custom Software Design, Development & Support**

Building scalable, maintainable, and business-aligned software solutions.

</div>

---

## About Us

MADLAB is a software engineering company specializing in custom software design, development, and long-term technical support for corporate clients. With over 20 years of combined experience in software architecture and delivery, we help organizations build systems that are secure, scalable, and aligned with their business goals.

We work across the full software lifecycle — from architecture and design to deployment and ongoing maintenance — for clients across multiple industries.

## What We Do

- 🏗️ **Custom Software Development** — Web applications, internal tools, and business platforms tailored to client requirements
- ☁️ **Cloud & Infrastructure** — Containerized deployments, CI/CD pipelines, and infrastructure automation
- 🔗 **System Integration** — SSO, document management, third-party APIs, and legacy system integration
- 🏛️ **Enterprise Platforms** — Multi-tenant applications, citizen/customer portals, and mission-critical systems
- 🛠️ **Ongoing Support** — Maintenance, monitoring, and technical support for delivered systems

## Our Stack

| Layer | Technologies |
|---|---|
| **Backend** | PHP (Laravel), Java, C#, REST APIs |
| **Databases** | PostgreSQL, MySQL |
| **Frontend** | JavaScript, Livewire, Alpine.js |
| **Infrastructure** | Docker, Docker Compose, Traefik, Portainer |
| **Practices** | Domain-Driven Design, Event-Driven Architecture, Microservices, Modular Monoliths |

## How We Work

- **API-first design** with clear separation of concerns
- **Docker-based deployments** for consistency across environments
- **Automated CI/CD** where it adds measurable value
- **Documentation-driven decisions** using ADRs for key technical choices
- **Security and scalability** considered from day one, not bolted on later

## Container Images

We publish production-ready, multi-arch (`amd64` / `arm64`) base images on [Docker Hub](https://hub.docker.com/u/madlabcg).

| Image | Description | Tags |
|---|---|---|
| [`madlabcg/laravel-php`](https://hub.docker.com/r/madlabcg/laravel-php) | PHP-FPM + nginx + supervisor runtime for Laravel apps. No app code included. | `8.5`, `8.4`, `8.2`, `7.4`, `latest` |
| [`madlabcg/react-nginx`](https://hub.docker.com/r/madlabcg/react-nginx) | Non-root nginx runtime for React/Vite SPAs with runtime env config. | `1.28`, `latest` |
| [`madlabcg/minio`](https://hub.docker.com/r/madlabcg/minio) | MinIO server + `mc`, unmodified Chainguard image with pinned version tags. | `stable`, `latest` |

```bash
docker pull madlabcg/laravel-php:8.4
```

## Get in Touch

Interested in working with us or learning more about a project? Reach out through this organization or contact us directly.

---

<div align="center">
<sub>© MADLAB. All rights reserved.</sub>
</div>
