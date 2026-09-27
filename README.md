<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Security Posture Management (ASPM) Banner" width="100%" />
</p>

# 🛡️ Awesome Application Security Posture Management (ASPM) & DevSecOps Ecosystem 🚀

<p align="left">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://awesome.re/badge.svg" alt="Awesome"/></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 💡 A curated list of top Application Security Posture Management (ASPM) SaaS platforms, commercial security vendors, and open-source vulnerability management tools. Focused on security posture aggregation, risk prioritization, code-to-cloud correlation, SBOM intelligence, and automated DevSecOps orchestration.

Application Security Posture Management (ASPM) unifies security findings across Software Composition Analysis (SCA), Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), Infrastructure as Code (IaC), container security, and runtime environments. By analyzing code context and runtime reachability, ASPM tools enable security teams to prioritize real risks and eliminate developer alert fatigue. ⚡

---

## 📌 Table of Contents
- [📊 Market Overview & Ecosystem Dynamics](#-market-overview--ecosystem-dynamics)
- [☁️ SaaS & Commercial ASPM Platforms](#️-saas--commercial-aspm-platforms)
- [🔓 Open-Source ASPM & Security Tools](#-open-source-aspm--security-tools)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Market Overview & Ecosystem Dynamics

> 📈 **Market Size & Dynamics**: The global Application Security Posture Management (ASPM) market is estimated at **$3.8 Billion to $4.5 Billion in 2026** (scaling within the broader **$31.7 Billion** Security Posture Management market) with a projected compound annual growth rate (CAGR) of **~25%–30%**. The sector is **highly fragmented**, driven by extreme enterprise security tool sprawl (organizations typically run 10–30+ disparate scanners). Because ASPM acts as the unifying control plane across heterogeneous security stacks, it is currently in a hyper-competitive, multi-vendor growth phase rather than a single "winner-take-all" market. 🧩

---

## ☁️ SaaS & Commercial ASPM Platforms

The following SaaS and enterprise commercial platforms provide end-to-end posture aggregation, AI-driven risk scoring, developer workflow automation, and runtime context correlation. 🔑

*Sorted by Company Size / Valuation / Funding (Descending)* 📉

| Rank | Platform | Company Size (Valuation / Revenue / Funding) | Starting Tier Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | **[Snyk AppRisk](https://snyk.io/)** 🐶 | **$7.4B Valuation** / $326M+ ARR | $25/dev/month ($149/dev/yr, AppRisk Enterprise min ~$15,000–$25,000/yr) | **Free Forever**: 1 dev, 100 code & 200 open source tests/mo<br>• **14-day Free Trial** | ASPM solution integrated into Snyk's developer security platform, combining developer visibility with asset discovery and security program governance. |
| 2 | **[Aikido Security](https://www.aikido.dev/)** 🥋 | **$1.0B Valuation** / $84.5M Funding | ~$350/month ($3,780/yr for 10 users) | **Free Forever**: Up to 2 users & 10 repos (full 9-in-1 scanner suite)<br>• **14-day Free Trial** | All-in-one AppSec & ASPM platform covering code, cloud, and runtime with auto-triage reducing false positives by ~85% and AI AutoFix. |
| 3 | **[Endor Labs](https://www.endorlabs.com/)** 🛡️ | **~$600M–$800M Valuation** / $188M Funding | ~$250–$500/dev/year ($15,000/yr starting enterprise list price) | **Free Tier**: Unlimited local CLI scans & MCP server integration<br>• **14-to-30 day Free Trial** | ASPM specializing in reachability analysis, dependency governance, and automated VEX generation to drastically reduce CVE noise. |
| 4 | **[Apiiro](https://apiiro.com/)** 🧠 | **$500M–$600M Valuation** / $135M Funding | $50/dev/month (Minimum 50 seats = $30,000/yr) | **Free Tier**: Single repo snapshot assessment<br>• **14-day Free Trial** | Enterprise ASPM platform analyzing code, design, and runtime context with Deep Code Analysis and Risk Graph prioritization. |
| 5 | **[Mend.io](https://www.mend.io/)** 🩹 | **~$400M–$500M Valuation** / $121M Funding | $250–$1,000/dev/year ($10,000/yr enterprise starting commitment) | **Free Tier**: Mend Bolt (5 scans/day/repo) & Renovate Community<br>• **14-day Free Trial** | Unified AppSec and ASPM platform covering open-source dependencies, AI models, and runtime reachability analysis. |
| 6 | **[Cycode](https://cycode.com/)** 🔐 | **~$250M–$350M Valuation** / $81M Funding | $300–$500/dev/year ($25,000/yr starting enterprise package) | **Free Tools**: Cygives CLI Secret Scanner & Raven graph query<br>• **14-day Free Trial** | Complete AI-native application security platform uniting code-to-runtime context for identifying and prioritizing enterprise software risk. |
| 7 | **[ArmorCode](https://www.armorcode.com/)** ⚔️ | **~$150M–$250M Valuation** / $81M Funding | $35,000–$50,000/year minimum starting package | **Free Demo**: Self-guided sandbox environment<br>• **30-day Free Trial** | AI-powered ASPM aggregating 320+ scanner integrations with unified risk scoring and automated remediation workflows. |
| 8 | **[Seemplicity](https://www.seemplicity.io/)** 🔄 | **~$150M–$250M Valuation** / $82.2M Funding | $35,000–$50,000/year starting enterprise package | **Free Demo**: Interactive simulation sandbox<br>• **30-day Free Trial** | Remediation operations platform automating risk reduction workflows and developer task routing across security findings. |
| 9 | **[Legit Security](https://www.legitsecurity.com/)** ⚖️ | **~$150M–$250M Valuation** / $77M Funding | $30,000–$50,000/year enterprise starting package | **Free Trial**: Dedicated 14-day trial for Secrets Scanning<br>• **14-to-30 day Free Trial** | AI-native ASPM securing AI-generated code, software supply chains, and developer environments with automated policy enforcement. |
| 10 | **[OX Security](https://www.ox.security/)** 🐂 | **~$100M–$250M Valuation** / $94M Funding | $400–$800/dev/year ($100,000/yr 100-user AWS package) | **14-day Free Trial**: Full platform code-to-cloud scanning & PBOM | Software supply chain security and ASPM offering Pipeline Bill of Materials (PBOM) and VibeSec AI risk prioritization. |
| 11 | **[Lineaje](https://lineaje.com/)** 📦 | **~$60M–$100M Valuation** / $27M Funding | $10,000–$25,000/year starting project unit commit | **Free Assessment**: One-time Software Supply Chain Risk Report<br>• **14-to-30 day Free Trial** | Software supply chain security and ASPM platform featuring deep SBOM analysis, dependency risk intelligence, and tamper detection. |
| 12 | **[P0 Security](https://p0.dev/)** ⭕ | **~$60M–$90M Valuation** / $20M Funding | ~$2,000/month ($24,000/yr for 100 users block) | **Free Assessment**: Cloud Access & Identity Risk Assessment<br>• **14-to-30 day Free Trial** | ASPM platform focused on governance and posture management for cloud infrastructure and application access controls. |
| 13 | **[Jit](https://www.jit.io/)** ⚡ | **$70M Valuation (Acquired by Torq)** / $38.5M Funding | ~$50/dev/month ($3,000/yr 5-seat AWS starter) | **Free Forever**: Core security stack for small teams & projects<br>• **14-day Free Trial** | Open ASPM platform enabling developers to implement automated security controls with minimal setup and developer-first remediation. |
| 14 | **[Phoenix Security](https://phoenix.security/)** 🔥 | **~$15M–$25M Valuation** / <$1M Seed | £1,495/month (~$1,900/mo / ~$22,800/yr for 5,000 credits) | **Free Forever**: Up to 1,000 assets & 2 users (free for OWASP members)<br>• **14-day Free Trial** | Contextual risk-based exposure and vulnerability management platform using SMART methodology for software, cloud, and infrastructure. |
| 15 | **[Kondukto](https://kondukto.io/)** 🚥 | **Parent Invicti >$1.0B Valuation** / $1.22M Seed | $15,000–$30,000/year starting enterprise package | **14-day Free Trial**: Proof of Concept with 110+ integrated connectors | ASPM platform unifying vulnerability management across scanners with automated triage and DevSecOps pipeline orchestration. |

---

## 🔓 Open-Source ASPM & Security Tools

Open-source projects provide transparency, vendor-neutral vulnerability management, and custom scanner orchestration for DevSecOps pipelines. 🛠️

*Sorted by GitHub Stars (Descending)* ⭐

1. 🐠 **[Trivy](https://github.com/aquasecurity/trivy)** [![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social)](https://github.com/aquasecurity/trivy/stargazers)  
   Comprehensive security scanner for containers, file systems, Git repositories, Kubernetes, AWS infrastructure, and Software Bill of Materials (SBOM).

2. ⚛️ **[Project Discovery Nuclei](https://github.com/projectdiscovery/nuclei)** [![GitHub stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social)](https://github.com/projectdiscovery/nuclei/stargazers)  
   Fast and customizable vulnerability scanner based on simple YAML DSL, widely used for modern application security posture assessment and dynamic scanning.

3. 🔑 **[Gitleaks](https://github.com/gitleaks/gitleaks)** [![GitHub stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=social)](https://github.com/gitleaks/gitleaks/stargazers)  
   SAST tool for detecting and preventing hardcoded secrets like passwords, API keys, and tokens in git repositories.

4. ⚡ **[OWASP ZAP](https://github.com/zaproxy/zaproxy)** [![GitHub stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social)](https://github.com/zaproxy/zaproxy/stargazers)  
   World's most widely used open-source Dynamic Application Security Testing (DAST) tool for finding vulnerabilities in web applications during runtime.

5. 🔍 **[Semgrep](https://github.com/semgrep/semgrep)** [![GitHub stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social)](https://github.com/semgrep/semgrep/stargazers)  
   Fast open-source static analysis (SAST) engine for searching code, enforcing security standards, and preventing bugs at commit time.

6. 📦 **[Grype](https://github.com/anchore/grype)** [![GitHub stars](https://img.shields.io/github/stars/anchore/grype?style=social)](https://github.com/anchore/grype/stargazers)  
   Vulnerability scanner for container images and filesystems from Anchore, designed to work seamlessly with SBOM generators like Syft.

7. 🧪 **[OSS-Fuzz](https://github.com/google/oss-fuzz)** [![GitHub stars](https://img.shields.io/github/stars/google/oss-fuzz?style=social)](https://github.com/google/oss-fuzz/stargazers)  
   Continuous fuzzing service for open-source software maintained by Google, detecting security bugs and memory vulnerabilities at scale.

8. 🏗️ **[Checkov](https://github.com/bridgecrewio/checkov)** [![GitHub stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social)](https://github.com/bridgecrewio/checkov/stargazers)  
   Static code analysis tool for Infrastructure as Code (IaC) supporting Terraform, CloudFormation, Kubernetes, Dockerfile, and ARM templates.

9. 🕵️ **[Faraday](https://github.com/infobyte/faraday)** [![GitHub stars](https://img.shields.io/github/stars/infobyte/faraday?style=social)](https://github.com/infobyte/faraday/stargazers)  
   Open-source vulnerability management platform orchestrating 80+ security tools for offensive security, pentest finding aggregation, and collaborative tracking.

10. 🥷 **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)** [![GitHub stars](https://img.shields.io/github/stars/DefectDojo/django-DefectDojo?style=social)](https://github.com/DefectDojo/django-DefectDojo/stargazers)  
    The flagship open-source vulnerability management and ASPM platform with 200+ scanner integrations. Aggregates findings from SAST, DAST, SCA, container, and IaC tools into a unified dashboard.

11. 🟢 **[Greenbone / OpenVAS](https://github.com/greenbone/openvas-scanner)** [![GitHub stars](https://img.shields.io/github/stars/greenbone/openvas-scanner?style=social)](https://github.com/greenbone/openvas-scanner/stargazers)  
    Full-featured vulnerability scanner providing comprehensive network and application security scanning capabilities.

12. 📜 **[Dependency-Track](https://github.com/DependencyTrack/dependency-track)** [![GitHub stars](https://img.shields.io/github/stars/DependencyTrack/dependency-track?style=social)](https://github.com/DependencyTrack/dependency-track/stargazers)  
    OWASP Flagship Software Composition Analysis (SCA) and SBOM management platform enabling organizations to identify and reduce risk in the supply chain.

13. 📐 **[OWASP ASVS](https://github.com/OWASP/ASVS)** [![GitHub stars](https://img.shields.io/github/stars/OWASP/ASVS?style=social)](https://github.com/OWASP/ASVS/stargazers)  
    Application Security Verification Standard providing a framework of security requirements and controls for testing web application technical security controls.

14. 🧱 **[Checkmarx KICS](https://github.com/Checkmarx/kics)** [![GitHub stars](https://img.shields.io/github/stars/Checkmarx/kics?style=social)](https://github.com/Checkmarx/kics/stargazers)  
    Keeping Infrastructure as Code Secure (KICS) finds security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle.

15. 🎯 **[ArcherySec](https://github.com/archerysec/archerysec)** [![GitHub stars](https://img.shields.io/github/stars/archerysec/archerysec?style=social)](https://github.com/archerysec/archerysec/stargazers)  
    Open-source vulnerability assessment and management platform orchestrating ZAP, OpenVAS, and custom security scans.

16. 🐧 **[OpenSCAP](https://github.com/OpenSCAP/openscap)** [![GitHub stars](https://img.shields.io/github/stars/OpenSCAP/openscap?style=social)](https://github.com/OpenSCAP/openscap/stargazers)  
    NIST-certified security compliance framework providing tools to analyze enterprise infrastructure posture and compliance requirements.

17. 🥑 **[GUAC (Graph for Understanding Artifact Composition)](https://github.com/guacsec/guac)** [![GitHub stars](https://img.shields.io/github/stars/guacsec/guac?style=social)](https://github.com/guacsec/guac/stargazers)  
    CNCF sandbox project aggregating software security metadata into a graph database to correlate SBOMs, attestations, and supply chain security data.

18. 👁️ **[SecObserve](https://github.com/MaibornWolff/SecObserve)** [![GitHub stars](https://img.shields.io/github/stars/MaibornWolff/SecObserve?style=social)](https://github.com/MaibornWolff/SecObserve/stargazers)  
    Open-source vulnerability management system ingesting findings from Trivy, Grype, Bandit, Semgrep, Gitleaks, Checkov, and OWASP ZAP with an integrated SBOM engine.

19. 📘 **[OWASP SAMM](https://github.com/OWASP/samm)** [![GitHub stars](https://img.shields.io/github/stars/OWASP/samm?style=social)](https://github.com/OWASP/samm/stargazers)  
    Software Assurance Maturity Model providing a governance framework to evaluate, formulate, and improve application security posture.

20. 🌲 **[DEPTEX](https://github.com/deptex/deptex)** [![GitHub stars](https://img.shields.io/github/stars/deptex/deptex?style=social)](https://github.com/deptex/deptex/stargazers)  
    Software supply chain platform treating security risk as emergent from organizational graphs, using Execution Path Dominance (EPD) for contextual prioritization.

---

## 🤝 How to Contribute

Contributions are welcome! To add a new platform or update existing information:

1. Fork this repository. 🍴
2. Edit `README.md` following the tabular layout for SaaS products or the star-ranked list for open-source tools. 📝
3. Ensure details (pricing, free tiers, star badges, links) are accurate and factual. 🎯
4. Submit a Pull Request with a short summary of changes. 🚀

---

## 💖 Support & Sponsorship

Thank you for exploring this curated list of Application Security Posture Management (ASPM) resources! If you found this repository useful, please consider:

- ⭐ **Starring** this repository to help others discover it!
- 🍴 **Forking** it to keep a copy or submit your own additions!
- 📢 **Sharing** it with your security engineering and DevSecOps networks!
- ☕ **Sponsoring** or buying a coffee via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007)!

Your support is greatly appreciated and encourages continuous updates to this ecosystem guide. 🙌

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Security-Posture-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Security-Posture-Management&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This list is **community-curated** for educational, evaluation, and research purposes.
- Product valuations, pricing tiers, and trial limits are subject to change by vendors.
- Application Security Posture Management solutions must comply with data protection regulations (GDPR, CCPA) and industry standards (SOC 2, ISO 27001, PCI DSS).
