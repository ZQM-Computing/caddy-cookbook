# Caddy Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Caddy cookbook** — automatic-HTTPS reverse proxying from config and API. Queued in wave-11 (Node-3 hub set). Patterns are planned from the design, not yet from fleet runs. It is intended for Engineers who front services with automatic HTTPS and simple configuration. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Caddy patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Engineers who front services with automatic HTTPS and simple configuration.

## Prerequisites

- Caddy via binary or Docker
- A backend service to proxy
- A domain you control for the HTTPS pass

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-proxy` | A first reverse proxy with automatic HTTPS |
| 02 | `02-caddyfile` | Caddyfile patterns for multiple services |
| 03 | `03-json-api` | Driving Caddy through its JSON admin API |
| 04 | `04-authelia-pairing` | Pairing with Authelia for authentication (see authelia-cookbook) |

## Repository layout

```text
caddy-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [authelia-cookbook](https://github.com/ZQM-Computing/authelia-cookbook) — Single sign-on and two-factor authentication for proxied services
- [portainer-cookbook](https://github.com/ZQM-Computing/portainer-cookbook) — Container management with an API and UI
- [grafana-cookbook](https://github.com/ZQM-Computing/grafana-cookbook) — Dashboards, datasources, and alerts for geospatial stacks
