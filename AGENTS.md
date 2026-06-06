# AGENTS.md

Security and contribution rules for garuda-audit (conntrack-log audit sidecar image).

- Never commit or use real public IP addresses. Use RFC5737 (TEST-NET) / RFC1918 / CGNAT ranges only.
- Never commit or use domains other than well-known examples or `example.net`.
- Never commit secrets, tokens, private keys, or customer data.
- This repo builds a single container image (`ghcr.io/alexmkx/garuda-conntrack-log`). It has no Terraform module, Helm chart, or FRR-sidecar dependency.
