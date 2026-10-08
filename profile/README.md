<p align="center">
  <img src="logo.png" alt="Bearust logo" width="140" />
</p>

<h1 align="center">Welcome to the Bearust org! 🦀</h1>

<p align="center">
  <strong>Open-source reverse proxy and load balancer with a built-in web dashboard.</strong>
</p>

Bearust routes your HTTP traffic to backend pools with health checks, TLS and ACME automation, a WAF, live analytics, and an authenticated control plane — configured with a small TOML file or entirely from the dashboard.

## Repositories

| Repository | What it is |
| --- | --- |
| [bearust/bearust](https://github.com/bearust/bearust) | The reverse proxy itself: Rust data plane, React dashboard, docs, and releases |
| [bearust/.github](https://github.com/bearust/.github) | This repo: org-wide community health files and this profile |

## Get started

- Read the [bearust README](https://github.com/bearust/bearust#readme) and run `docker compose up -d --build`
- Pull the prebuilt image from `ghcr.io/bearust/bearust`
- Report bugs and request features via [issues](https://github.com/bearust/bearust/issues/new/choose)
- Read the [contributing guidelines](https://github.com/bearust/.github/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/bearust/.github/blob/main/CODE_OF_CONDUCT.md) before contributing

🔒 Found a security issue? Please use [private vulnerability reporting](https://github.com/bearust/bearust/security/advisories/new) instead of a public issue.
