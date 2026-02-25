![Open Source at OrionRND](https://github.com/OrionRND/.github/blob/main/images/ORION-GITHUB-BANNER-without-logo.jpg) 

We do two things: help manufacturers ship secure connected products, and build tooling that makes vulnerability monitoring less painful for the teams operating them.

---

## OrionRadar

Most CVE monitoring tools solve the wrong problem. They flood you with thousands of advisories that don't apply to your stack, require weeks of configuration, or cost enterprise budget to run. OrionRadar takes a different approach.

A statically linked Rust agent runs on your machines, collects a full software inventory, and cross-references it against public sources. You get an alert when something critical lands in your specific stack — not before.

```
curl -sSL https://get.orionradar.io | sh
```

**What it produces:**
- Per-machine software inventory with versions and licences
- High and critical CVE alerts with plain-language AI summaries grounded in NVD data
- SBOM export in CycloneDX and SPDX formats
- Audit-ready evidence for EU CRA, NIS2, and ETSI EN 303 645

Early access is open at **[orionradar.io](https://orionradar.io)**.

---

## Consulting

We work with hardware and IoT manufacturers on the security problems that show up before and during certification:

- **Penetration testing** — firmware extraction, hardware debug interfaces, network protocol analysis, side-channel and fault injection research
- **Pre-compliance gap analysis** — mapping your product against EU CRA, ETSI EN 303 645 / RED, IEC 62443, and NIS2 before you engage a notified body
- **Audit preparation** — producing the technical documentation, SBOM, and vulnerability management evidence that certification bodies expect

We work primarily with companies building ESP32-based systems, embedded Linux devices, and industrial IoT infrastructure.

Details at **[orionrnd.com](https://orionrnd.com)**.

---

## Repositories

| Repo | What it is |
|------|------------|
| [`orionradar-agent`](https://github.com/orionrnd/orionradar-agent) | Rust agent — inventory collection, CVE matching, SBOM export |
<!--| [`orionradar-landing`](https://github.com/orionrnd/orionradar-landing) | Landing page — Astro, self-hosted font, GDPR-compliant waitlist |-->

---

## Get in touch

**info(at)orionrnd.com**

For consulting enquiries, include a brief description of your product and the regulatory context you're working towards. For OrionRadar licensing (MSSP or Enterprise on-premise), mention your expected deployment scale.
