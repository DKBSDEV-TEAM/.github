<p align="center">
  <a href="https://dkbsolutions.com/">
    <img src="https://dkbsolutions.com/storage/images/logo/logo-DKBS-en-vert.png" alt="DKB Solutions" width="280" />
  </a>
</p>

<h1 align="center">DKB Solutions</h1>

<p align="center">
  <strong>We support you in your digitalization transformation.</strong><br />
  Electronic certification, digital signature, and information systems — since 1994.
</p>

<p align="center">
  <a href="https://dkbsolutions.com/">Website</a>
  ·
  <a href="https://dkbsolutions.com/digital-signature">Digital signature</a>
  ·
  <a href="https://dkbsolutions.com/public/solutions">Solutions</a>
  ·
  <a href="mailto:info@dkbsolutions.com">info@dkbsolutions.com</a>
</p>

---

**DKB Solutions** is an Abidjan-based integrator of information systems, telecommunications, and trust services. The company puts the information system at the service of performance and added value: study and advice, deployment, and maintenance across the full life cycle of a customer’s systems.

DKB Solutions is approved by the **Autorité de Régulation des Télécommunications de Côte d’Ivoire (ARTCI)** as a **Prestataire de Services de Certification Électronique (PSCE)**, under Law n°2013-546 of 30 July 2013 on electronic transactions and Decree n°2014-106 of 12 March 2014 on the conditions for creating and keeping electronic writings and signatures. That approval was reviewed on site by ARTCI in 2022.

The engineering work in this organization builds **DKBSign**: the platforms that issue certificates, sign documents, run approval workflows, store evidence, and let companies integrate trust into their own applications.

## Why DKB Solutions

- A multi-skilled practice that stays with a project from design through operation
- Teams that stay involved after go-live
- A network of specialist partners and products, chosen for the job
- Delivery shaped around each customer’s constraints

## What this organization builds

DKBSign is delivered as a **token**, a **web platform for companies**, and an **API**. A single customer gateway hides the internal services. Integrators authenticate once and call signing, workflows, the document vault, contacts, verification, notifications, and document AI from that API. A PHP SDK and a public documentation site sit on top of the same gateway.

| Capability | What it does |
| --- | --- |
| **Qualified & simple signature** | Sign one PDF or a batch, place visible fields, embed a QR verification code, and run multi-signer envelopes |
| **Certificates** | Issue, download, revoke, and check status through an HSM-backed authority, with CRL and OCSP |
| **Company workspace** | Parapheur, inbox, administration, and super-administration for organizations |
| **Workflows** | Multi-tenant approval circuits: validate, sign, stamp, initials, text, date, QR — linear or conditional |
| **Electronic document management** | Folders, typologies, versions, full-text search, legal hold, sealed vault, and time-limited shares |
| **Proof & verification** | PAdES inspection, certificate chain, timestamp, OCSP/CRL, and a JSON proof file |
| **Identity of external signers** | Face match of an ID document against a selfie, active liveness, OCR, and name consistency |
| **Document AI** | Contract analysis, risk review, pre-signature summary, and suggested signature zones |
| **Notifications** | Email, SMS, and WhatsApp for signature and workflow events |
| **Audit & resilience** | Hash-chained audit journal, SIEM/syslog export, supervision, backups, and disaster recovery |

### Certificates

| Certificate | Use |
| --- | --- |
| **Individual** | A person’s digital identity for strong authentication and document signing |
| **Server stamp** | An organization’s seal on documents and transactions |
| **SSL OV** | Organization-validated TLS for sites, banking flows, and data exchange |
| **Extended Validation** | The highest public-web assurance: domain ownership, company verification, then issuance |
| **Wildcard** | One certificate covering a domain and its subdomains |

An electronic signature here is a cryptographic commitment. It identifies the signer, binds that identity to the file, and shows whether the file was altered afterward. The document stays readable; signing does not encrypt it. PDF is the format used in the platforms because it keeps a stable layout and can carry several signatures.

## Repositories

### DKBSign — products customers and integrators use

| Repository | Role |
| --- | --- |
| [`dkbsign-entreprise`](https://github.com/DKBSDEV-TEAM/dkbsign-entreprise) | Company web app (React, TypeScript, Vite): parapheur, inbox, vault, admin |
| [`dkbsign-api-gateway`](https://github.com/DKBSDEV-TEAM/dkbsign-api-gateway) | The only API integrators need (Laravel). OpenAPI, Postman, and an MCP server for agents |
| [`dkbsign-docs`](https://github.com/DKBSDEV-TEAM/dkbsign-docs) | Public documentation site for that gateway |
| [`dkbsign-sdk-php`](https://github.com/DKBSDEV-TEAM/dkbsign-sdk-php) | PHP client: self-sign, envelopes, verification, email, SMS, WhatsApp |
| [`api-dkbsignv4`](https://github.com/DKBSDEV-TEAM/api-dkbsignv4) | PDF signature service: single and batch signing, P12/PFX, verification QR codes |
| [`dkb-workflow-api`](https://github.com/DKBSDEV-TEAM/dkb-workflow-api) | Multi-tenant workflow engine, LDAP/Active Directory, and DKB Sign actions |
| [`dkb-workflow-web`](https://github.com/DKBSDEV-TEAM/dkb-workflow-web) | Web console for launching and treating those workflows |

### DKBSign — platform services

| Repository | Role |
| --- | --- |
| [`dkbsign-auth`](https://github.com/DKBSDEV-TEAM/dkbsign-auth) | Authentication, companies, users, and sessions |
| [`dkbsign-notifications`](https://github.com/DKBSDEV-TEAM/dkbsign-notifications) | Email, SMS, and WhatsApp delivery |
| [`ws-edm`](https://github.com/DKBSDEV-TEAM/ws-edm) | Electronic document management and digital vault |
| [`ws-contatcs`](https://github.com/DKBSDEV-TEAM/ws-contatcs) | Address book with CSV, LDAP, Google, and Microsoft 365 import |
| [`ws-verification-proof`](https://github.com/DKBSDEV-TEAM/ws-verification-proof) | PAdES verification and JSON proof files |
| [`ws-ai-document`](https://github.com/DKBSDEV-TEAM/ws-ai-document) | Contract analysis, risk review, summaries, and signature-zone detection |
| [`dkbs-face-verification-api`](https://github.com/DKBSDEV-TEAM/dkbs-face-verification-api) | KYC of external signers: face match, liveness, OCR |
| [`ws-logs-audit-security`](https://github.com/DKBSDEV-TEAM/ws-logs-audit-security) | Activity logs, hash-chained audit, SIEM, backups, and recovery |
| [`hsm-certificate-management-api`](https://github.com/DKBSDEV-TEAM/hsm-certificate-management-api) | HSM certificate issuance, revocation, CRL, and OCSP |
| [`ws-certificate-issued`](https://github.com/DKBSDEV-TEAM/ws-certificate-issued) | Issued-certificate operations: CSR, single-use certificates, revocation, CRL, and OCSP |

### Sector applications

| Repository | Role |
| --- | --- |
| [`dkb-forms-api`](https://github.com/DKBSDEV-TEAM/dkb-forms-api) | API for bank pre-printed forms |
| [`dkb-forms-ui`](https://github.com/DKBSDEV-TEAM/dkb-forms-ui) | Next.js interface for those forms |
| [`api-inhp`](https://github.com/DKBSDEV-TEAM/api-inhp) | Certificates and inspections for INHP |

## Services for organizations

Beyond the software in these repositories, DKB Solutions designs, deploys, and runs:

- **Electronic signature** — token, DKBSign API, and the DKBSign web platform, so the digital economy rests on an identified signer and an intact document
- **ECM / GED** — one interface for sharing, circulation, collaborative work, access control, and structured documents in real time
- **Dematerialization** — paper processes converted into managed digital records
- **Cybersecurity** — software and hardware that protect servers, workstations, and phones: identity and access, endpoint protection, data-loss prevention, and remote cyber protection (anti-phishing, anti-ransomware, EDR)
- **Offsite backup** — business and strategic data kept off site and reachable, so work can continue after an incident
- **Data loss prevention** — detection and control of sensitive data leaving the organization
- **Robotic process automation** — virtual agents, including Blue Prism, for repetitive operational work
- **Video security and access control** — with partners including Dahua, for sites that need physical and logical protection together

The practice also integrates specialist products where they fit: Ilex (identity), OpenText and Intalio (content), ABBYY and IRIS (capture and OCR), SeeUnity (ECM connectors), Endpoint Protector (DLP), and infrastructure from partners such as Fujitsu.

## Recognition

- **Orange Bank** selected DKB Solutions to electronically sign the terms and conditions of its eCGU project
- **ARTCI** renewed the company’s PSCE approval after an on-site review of the PKI, technical architecture, and physical controls (2022)

## Leadership

| | |
| --- | --- |
| **Djaha Bertin** | Chief Executive Officer |
| **Wilfried Djaha** | Deputy Chief Executive Officer |
| **Kassi Jammes** | Project Director |
| **Cophey Myreille** | Personal data manager |

## Contact

**DKB Solutions**  
Abidjan-Cocody, Riviera Golf 4, Lot 92B, Ilot 6, Rue E127  
Côte d’Ivoire

[info@dkbsolutions.com](mailto:info@dkbsolutions.com)  
[+225 27 22 46 47 24](tel:+2252722464724)

[dkbsolutions.com](https://dkbsolutions.com/) · [Français](https://dkbsolutions.com/fr)
