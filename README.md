# Hi, I'm Daan van Gorkum 👋

**Senior Site Reliability Engineer & Systems Architect** based in Singapore 🇸🇬  
Specializing in **bare-metal Linux platforms**, **global traffic engineering (BGP / DNS / Anycast)**, and **infrastructure automation**.

[Website](https://l.dj.vg/home) • [Writing](https://dj.vg/posts/) • [LinkedIn](https://l.dj.vg/linkedin) • [AS209792](https://bgp.tools/as/209792) • [Email](mailto:me@dj.vg)

---

### 🌐 What I Do

Over the past decade across **Cloudflare**, **Adyen**, and **Imperva / Thales Cybersecurity**, I have designed and operated infrastructure spanning the physical layer up to distributed cloud platforms:

- **Global Edge & Traffic Management**: Operating external DNS, Anycast routing, CDNs, and multi-homed BGP meshes handling terabits of transit traffic.
- **Bare-Metal Lifecycle & Automation**: Zero-touch server provisioning, UEFI automation, hardware validation frameworks, and out-of-band management.
- **Resilience & Storage Systems**: Distributed storage at scale with **CEPH**, progressive delivery with **Kubernetes** & **Argo Rollouts**, and time-series anomaly detection with **VictoriaMetrics Anomaly**.
- **Systems Tooling**: Building lightweight, reliable tools and automation in **Go** and **Python**.

Outside of day-to-day engineering, I operate my own autonomous system ([**AS209792**](https://bgp.tools/as/209792)), tinker with ARM64 / RISC-V hardware in my homelab, and volunteer as an electronics repair coach with [**Repair Kopitiam**](https://repairkopitiam.sg/) to divert consumer electronics from Singapore's landfills.

---

### 🛠️ Systems & Technologies

```text
Languages       :: Go, Python (FastAPI, Django), Bash, SQL, PHP, Lua, C
Networking      :: BGP, Anycast, ECMP, WireGuard, DNS (BIND 9, PowerDNS), NGINX, HAProxy, DWDM
Platforms & OS  :: Debian, RHEL, CentOS, Gentoo, Bare-Metal / UEFI, Proxmox VE, CEPH, Kubernetes
Observability   :: Prometheus, VictoriaMetrics (Anomaly Detection), Grafana, ClickHouse
Automation & CI :: SaltStack, Terraform, Puppet, Argo Rollouts, Argo CD, GitLab CI/CD
```

---

### 🚀 Selected Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| [**BCRSTracking**](https://github.com/TheDJVG/BCRSTracking) | Real-time telemetry & bin capacity monitoring for Singapore's Beverage Container Return Scheme. ([Story](https://dj.vg/posts/why-i-built-bcrs-tracking/)) | Go • ClickHouse • K8s • Prometheus |
| [**XYZ.FRL**](https://l.dj.vg/xyz.frl) | Privacy-first, stateless Dynamic DNS service. No account required, simple API. | Go • Anycast DNS |
| [**netbox-more-metrics**](https://github.com/TheDJVG/netbox-more-metrics) | NetBox plugin exposing granular Prometheus metrics from DCIM and IPAM data. | Python • NetBox • Prometheus |
| [**vault-backup**](https://github.com/TheDJVG/vault-backup) | High-performance CLI for streaming HashiCorp Vault Raft snapshots to S3 storage. | Go • HashiCorp Vault • AWS S3 |
| [**netbox-field-permissions**](https://github.com/TheDJVG/netbox-field-permissions) | NetBox plugin enforcing fine-grained user/group object field-level write permissions. | Python • Django • NetBox |
| [**IMGDumper.nl**](https://l.dj.vg/imgd) | Fast direct image hosting platform, running continuously and reliably since 2007. | PHP • Linux Storage |
| [**KopiTool**](https://gitlab.sin.djvg.net/kopitool/kopitool) | Repair ticketing and diagnostics platform built for Repair Kopitiam to track e-waste reduction. | Python • Django • PostgreSQL |

---

### ✍️ Recent Articles & Notes

- [**Why I Built BCRS Tracking**](https://dj.vg/posts/why-i-built-bcrs-tracking/) — *Tracking Singapore's smart recycling machines with Go, ClickHouse, and Prometheus.*
- [**The 'Datacenter at Home': A Multi-Homed BGP & WireGuard Mesh Architecture**](https://dj.vg/posts/datacenter-at-home-bgp-wireguard-saltstack/) — *Applying hyperscale datacenter design principles to AS209792.*
- [**Easy and free Dynamic DNS**](https://dj.vg/posts/free-dynamic-dns/) — *A lightweight, stateless Dynamic DNS service built with FastAPI.*
- [**A Timelapse System: The Start**](https://dj.vg/posts/timelapse-system-a-start/) — *Capturing decades-long construction projects with Ceph, Kubernetes, and Python.*

---

### 📡 Connect & Telemetry

- **Homepage & Blog**: [dj.vg](https://dj.vg)
- **BGP / Autonomous System**: [AS209792 on bgp.tools](https://bgp.tools/as/209792)
- **LinkedIn**: [linkedin.com/in/daan-van-gorkum/](https://l.dj.vg/linkedin)
- **Direct Email**: [me+github@dj.vg](mailto:me+github@dj.vg)
