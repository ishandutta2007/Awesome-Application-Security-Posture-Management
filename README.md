# Awesome-Application-Security-Posture-Management

## Top Application Security Posture Management (ASPM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Security Posture Aggregation, Risk Prioritization & DevSecOps Orchestration*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Security Posture Management (ASPM)**. These tools aggregate findings from multiple security scanners, correlate risks across code, dependencies, containers, and cloud infrastructure, and provide unified visibility into an organization's application security posture.



**Examples** include Apiiro, OX Security, ArmorCode, Mend.io, Legit Security, Kondukto, Jit, Phoenix Security, Snyk AppRisk, Seemplicity, Lineaje, Cycode, P0 Security, Aikido Security, and Endor Labs (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom scanner orchestration, and transparent vulnerability management — ideal for security teams, DevSecOps engineers, and developers building vendor-independent ASPM pipelines. Note that while several mature open-source vulnerability management platforms exist, the ASPM category — with true risk correlation and posture scoring — remains largely commercial.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Apiiro](https://apiiro.com/)**  

  Unified application risk visibility platform analyzing code, design, and runtime context with Risk Graph for prioritizing remediation.



- **[OX Security](https://www.ox.security/)**  

  End-to-end software supply chain security with PBOM (Pipeline Bill of Materials) and VibeSec AI for posture management.



- **[ArmorCode](https://www.armorcode.com/)**  

  AI-powered ASPM platform aggregating 320+ scanner integrations with intelligent prioritization and remediation workflows.



- **[Mend.io](https://www.mend.io/)**  

  Unified AppSec platform covering open source dependencies, AI models, and runtime with reachability analysis and compliance evidence.



- **[Legit Security](https://www.legitsecurity.com/)**  

  AI-native ASPM securing AI-generated code and development environments with real-time policy enforcement.



- **[Kondukto](https://kondukto.io/)**  

  ASPM platform unifying vulnerability management across scanners with automated triage and DevSecOps orchestration.



- **[Jit](https://www.jit.io/)**  

  Open ASPM platform enabling developers to implement automated security with minimal configuration and independent remediation.



- **[Phoenix Security](https://phoenix.security/)**  

  Risk-based exposure and vulnerability management with SMART methodology for software, infrastructure, and cloud.



- **[Snyk AppRisk](https://snyk.io/)**  

  ASPM product from Snyk providing visibility and controls across application security programs with developer-friendly workflows.



- **[Seemplicity](https://www.seemplicity.io/)**  

  Remediation operations platform automating risk reduction workflows across security findings.



- **[Lineaje](https://lineaje.com/)**  

  Software supply chain security and management platform with SBOM analysis and dependency risk intelligence.



- **[Cycode](https://cycode.com/)**  

  AI-native application security platform uniting code-to-runtime context for identifying and prioritizing software risk.



- **[P0 Security](https://p0.dev/)**  

  ASPM platform focused on securing cloud and application access with posture-driven controls.



- **[Aikido Security](https://www.aikido.dev/)**  

  All-in-one AppSec platform covering code, cloud, and runtime with auto-triage reducing false positives by ~85% and AI-powered AutoFix.



- **[Endor Labs](https://www.endorlabs.com/)**  

  ASPM with reachability analysis, phantom dependency detection, and automated VEX generation to reduce CVE noise.



## Open-Source GitHub Projects



- **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**  

  The most widely adopted open-source vulnerability management and ASPM platform with 200+ scanner integrations. Aggregates findings from SAST, DAST, SCA, container, and IaC tools into a unified dashboard with deduplication and metrics. Django-based with Docker deployment. Open-source core with commercial Pro features including SLA tracking and RBAC .



- **[SecObserve](https://github.com/MaibornWolff/SecObserve)**  

  Open-source vulnerability and license management system maintained by MaibornWolff. Multi-scanner aggregator ingesting Trivy, Grype, Bandit, Semgrep, Gitleaks, Checkov, KICS, Kubescape, and OWASP ZAP. Lighter operational footprint than DefectDojo with CI/CD-first design. License management and SBOM ingestion are core capabilities, not add-ons .



- **[Faraday](https://github.com/infobyte/faraday)**  

  Open-source vulnerability management platform with 6.2k GitHub stars, orchestrating 80+ security tools. Built for offensive security teams managing pentest findings from Nessus, OpenVAS, Burp Suite, ZAP, Nmap, and Metasploit. Features Agents Dispatcher for remote scanning and collaborative workspaces. GPL-3.0 licensed .



- **[Dependency-Track](https://github.com/DependencyTrack/dependency-track)**  

  OWASP Flagship project for Software Composition Analysis (SCA) and SBOM compliance. Goes deeper than general-purpose ASPM platforms for dependency vulnerabilities, with support for CycloneDX and SPDX formats. Apache 2.0 licensed with 3.6k+ stars .



- **[GUAC (Graph for Understanding Artifact Composition)](https://github.com/guacsec/guac)**  

  Open-source project aggregating software security metadata into a graph database. Correlates SBOMs, attestations, and vulnerability data for supply chain visibility. CNCF sandbox project.



- **[Archery](https://github.com/archerysec/archery)**  

  Open-source vulnerability assessment and management platform orchestrating ZAP and OpenVAS scans with a web interface. Lighter than DefectDojo for teams primarily needing scan orchestration and basic vulnerability tracking .



- **[DEPTEX](https://github.com/deptex/deptex)**  

  Organization-first software supply chain platform treating risk as emergent from organizational graphs. Features Execution Path Dominance (EPD) for contextual prioritization and Security "As Code" engine. Available as open-source web application; roadmap includes evolution into full ASPM with SAST and secrets detection .



- **[OWASP SAMM](https://github.com/OWASP/samm)**  

  Software Assurance Maturity Model providing a framework for analyzing and improving application security posture. While not a tool itself, SAMM's assessment questionnaires and maturity benchmarks are essential for ASPM program governance. Includes Governance, Design, Implementation, Verification, and Operations business functions .



- **[OWASP ASVS](https://github.com/OWASP/ASVS)**  

  Application Security Verification Standard providing a basis for testing web application technical security controls. Referenced by OWASP as the guideline for setting application security requirements in ASPM programs .



### Additional Strong Open-Source Options



- **OSS-Fuzz** — Google's continuous fuzzing service for open-source projects, finding vulnerabilities at scale. Not ASPM per se, but valuable for code-level posture.

- **OpenVAS/Greenbone** — Open-source vulnerability scanner with comprehensive coverage for network and application scanning, often integrated into ASPM pipelines.

- **Trivy** — Aqua Security's open-source scanner for containers, IaC, and SBOM, widely used as a component in open-source ASPM stacks.

- **Gitleaks** — Open-source secrets detection tool for git repositories, commonly aggregated into ASPM dashboards alongside SAST and SCA findings.

- **Semgrep** — Open-source SAST engine with custom rule support, frequently used as a scanning component in open-source ASPM implementations.

- **OpenSCAP** — NIST-certified security compliance scanning for Linux systems, relevant for infrastructure posture components.



**Frameworks for building custom ASPM solutions**: Combine **DefectDojo** or **SecObserve** as the aggregation and management layer, **Trivy** + **Semgrep** + **Gitleaks** for scanning coverage, **Dependency-Track** for deep SCA and SBOM analysis, and **OWASP SAMM** for program maturity governance. For offensive security workflows, **Faraday** provides pentest-focused aggregation. Note that true ASPM risk correlation — linking a code finding to a runtime exposure to a business asset — remains largely commercial territory; open-source stacks provide scanner aggregation and vulnerability management without the full posture scoring and context enrichment of commercial platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- ASPM tools must comply with data privacy regulations (GDPR, CCPA, etc.) and industry-specific compliance requirements (SOC 2, ISO 27001, PCI DSS).

- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance. Scanner integrations require configuration and tuning to reduce false positives.

- The open-source ecosystem provides strong vulnerability management and scanner aggregation capabilities, but true ASPM posture scoring with business-context risk correlation remains primarily a commercial offering.



---



**Made for security engineers, DevSecOps teams, AppSec managers, and platform engineers.**  

Let's make application security posture management more open, transparent, and vendor-neutral.
