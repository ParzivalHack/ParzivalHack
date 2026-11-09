<div id="header" align="center">
  <img src="https://media.giphy.com/media/YRMb6dd7zprS00JdGZ/giphy.gif" width="100"/>
</div>

# Tommaso Bona
## IT & Security Consultant | AI Security Researcher | ADHD & Autism Advocate
### Welcome <img src="https://raw.githubusercontent.com/aemmadi/aemmadi/master/wave.gif" width="30">

As a passionate cybersecurity professional and researcher, I currently serve as an **IT & Security Consultant at Tralerighe Service** and an **Independent AI Security Researcher**, specializing in LLMs and AI Model vulnerability discovery. My career is built on a foundation of technical leadership and innovation; as the former **Co-Founder and CTO of Voyxa**, I led a cross-functional team of 20+ PhD students, consultants and engineers to develop our AI-driven vocal Helpdesk solution. Under my technical steering, Voyxa was recognized as a finalist at Digithon (Italy's largest pitch event) and, among other things, i also served as the technical spokesperson, bringing Voyxa from 0 to a **500k$ evaluation**, in only **10 months**.

My transition from a **SOC Analyst and Cybersecurity Specialist**, to a CTO, and now a specialized Consultant, has allowed me to blend deep technical expertise with strategic business development. I also worked as a **Business Development Advisor and Marketing Strategist for StationX**, where I proposed and helped guide the creation of their new white papers platform, all of which started, with me working remotely for StationX as a "simple" **Cybersecurity Writer**, for a bit more than a year. Beyond the corporate world, I am a volunteer **OSINT Analyst** for the Guardian Group's PURSUIT® Team, helping fight child exploitation, together with law enforcement, as well as i've had the privilege of contributing to the **Python Software Foundation** in multiple ways, and i'm a proud advocate for **ADHD and Autism awareness**, considering neurodiversity as a vital asset for innovation, in the current cybersecurity landscape.

---

## 🛠️ My Expertise

### **Core Skills**
- **AI Security:** LLM Red Teaming, Adversarial Machine Learning, and AI Safety Assessments.
- **OSS Security:** Independent Python-focused Security Research on Open-Source Software.
- **Offensive Security:** Web Penetration Testing, Vulnerability Research, and OSINT.
- **Leadership & Strategy:** Technical Team Management, Product Management, and Business Development.
- **Programming & Scripting:** Python, Rust, PowerShell, Bash, and Batchfile (even if deprecated).

### **Publications & Research**
- **Whitepaper:** [Anchored Fictional Multilingual Injection (AFMI): A Deterministic Prompt-Based Safety Bypass in Web-Integrated LLM Search-Engine Pipelines](https://www.stationx.net/paper/anchored-fictional-multilingual-injection/) (StationX Ltd. - 2025)
- **Technical Writeup:** [PySpector: how my own SAST Framework, led me to an RCE in a Major AI Library](https://medium.com/securitycertcommunity/pyspector-how-my-own-sast-framework-led-me-to-an-rce-in-a-major-ai-library-c29cdce15f9c) (SecurityCert s.r.l. - 2025), [CVE-2026-31900: How a Permissive Regex Led to RCE in psf/black’s GitHub Action](https://medium.com/securitycertcommunity/cve-2026-31900-50800bafafba) (SecurityCert s.r.l. - 2026)
- **Academic Paper:** [Fragmentation, Encryption, and Redundancy in Data Transmission: A Novel Secure UDP-Based Fragmentation Protocol and Its Applications](https://zenodo.org/records/13895316) (CERN & OpenAIRE - 2024)
- **General Cybersecurity Articles (English):**
[SQLmap Tutorial for Beginners 2024](https://www.stationx.net/sqlmap-tutorial/) (StationX Ltd. - 2024),
[XSS vs CSRF: The Difference Between These Popular Attacks](https://www.stationx.net/xss-vs-csrf/) (StationX Ltd. - 2024),
[Best OS for Hacking](https://www.stationx.net/best-os-for-hacking/) (StationX Ltd. - 2024),
[Top 15+ Cyber Security Tools](https://www.stationx.net/cyber-security-tools/) (StationX Ltd. - 2024),
[Hacking With Python: Unlocking Python's Potential](https://www.stationx.net/hacking-with-python/) (StationX Ltd. - 2023),
[SQL Injection Testing: All You Need to Know!](https://www.stationx.net/sql-injection-testing/) (StationX Ltd. - 2023)
- **General Cybersecurity Articles (Italian):**
[AI Offensive Security per Principianti (EP02)](https://medium.com/securitycertcommunity/ai-offensive-security-per-principianti-ep02-0b897b661a26) (SecurityCert s.r.l. - 2025),
[AI Offensive Security per Principianti (EP01)](https://medium.com/securitycertcommunity/ai-offensive-security-per-principianti-bcd8a8e82f4f) (SecurityCert s.r.l. - 2025)

---

## 🛡️ Core Security Contributions

| Title | Description | CVE ID | Links |
|---|---|---|---|
| **NoSQL injection in Openwhyd `controller(): request.body` leads to Private Information Disclosure** | Discovered and responsibly disclosed a Medium severity NoSQL Injection in Openwhyd, leading to Info Disclosure | CVE-2026-123617 | [CVE.org record](https://www.cve.org/CVERecord?id=CVE-2026-123617)<br>[GitHub Advisory](https://github.com/openwhyd/openwhyd/security/advisories/GHSA-hfg3-vq24-hprp) |
| **Unauthenticated Server-Side Template Injection leading to RCE in LMFDB** | Discovered and responsibly disclosed a Critical (CVSS4: 10.0) unauthenticated SSTI (CWE-94, CWE-1336) in the L-functions and Modular Forms Database (LMFDB). The `/knowledge/render/<ID>` endpoint spliced request data, including every query-string key and value, directly into a Jinja template rendered in an unsandboxed environment. A single unauthenticated GET request was enough to achieve OS-level Remote Code Execution, confirmed against the live lmfdb.org production instance with a non-destructive `id` call. Patched in commit `01829bd`. | CVE-2026-123198 | [CVE.org record](https://www.cve.org/CVERecord?id=CVE-2026-123198)<br>[GitHub Advisory](https://github.com/LMFDB/lmfdb/security/advisories/GHSA-6jw3-pmcx-2xww) |
| **Disabled TLS Certificate Verification in OpenAlgo** | Found by my `pyspector-monitor` pipeline at SatoriCI. OpenAlgo's SMTP code (versions >= 1.0.0.29, < 2.0.3.1) disabled both hostname and certificate verification (CWE-295), allowing Man-in-the-Middle attacks to capture SMTP credentials and intercept password reset links (account takeover primitive). Medium severity (CVSS4: 6.0). Fixed in v2.0.3.1. | CVE-2026-120250 | [Read the full writeup](https://blog.satori.ci/CVE-2026-120250-OpenAlgo)<br>[CVE.org record](https://www.cve.org/CVERecord?id=CVE-2026-120250)<br>[GitHub Advisory](https://github.com/marketcalls/openalgo/security/advisories/GHSA-4vvw-xw2w-38g8) |
| **Argument Injection in Red Hat's Ansible-core leading to RCE** | Found and responsibly disclosed a High severity (CVSS: 7.8) Argument Injection in Red Hat's Ansible-core, leading to Remote Code Execution. | CVE-2026-11332 | [Read the full writeup](https://medium.com/securitycertcommunity/cve-2026-11332-how-i-found-an-argument-injection-in-ansible-leading-to-rce-0050b41b9679)<br>[NIST NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-11332)<br>[Red Hat Advisory](https://access.redhat.com/security/cve/cve-2026-11332) |
| **0-click RCE in psf/black's GitHub Action** | Discovered and responsibly disclosed a High severity (CVSS4: 8.7) RCE in the official psf/black GitHub Action (2.2B downloads). A permissive regex in `action/main.py` allowed direct URL references to bypass version validation, enabling arbitrary code execution on CI runners via a malicious `pyproject.toml`, triggered by the creation of a new pull request with no maintainer interaction required. Patched in v26.3.0. | CVE-2026-31900 | [Read the full writeup](https://medium.com/securitycertcommunity/cve-2026-31900-50800bafafba)<br>[NIST NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-31900)<br>[GitHub Advisory](https://github.com/advisories/GHSA-v53h-f6m7-xcgm) |
| **Remote Code Execution (RCE) in AI Framework** | Identified and responsibly disclosed a critical RCE vulnerability in a widely used AI library, by leveraging my own SAST framework, PySpector. | N/A | [Research & Proof of Concept](https://securitycert.it/pyspector-how-my-own-sast-framework-led-me-to-an-rce-in-a-major-ai-library/) |
| **Public Acknowledgement from the U.S. Department of Commerce** | Discovered and reported a Critical, High-Impact Error-based SQLi, leading to a full database takeover on a US Department of Commerce subdomain. | N/A | [Official acknowledgement](https://doc.responsibledisclosure.com/hc/en-us/articles/10801394414227-Acknowledgments) |
| **Requests (Python Software Foundation)** | Reported what was initially thought to be a minor security flaw in the Requests library, which was ultimately classified as a bug and fixed upstream. | N/A | [PR #7308](https://github.com/psf/requests/pull/7308) |
| **CPython (Python Programming Language)** | Contributed to the CPython core test suite by addressing a Path Traversal vulnerability (minor impact, since it only affected the dev test suite). | N/A | [PR #138158](https://github.com/python/cpython/pull/138158) |
| **Lead Dev and Maintainer of PySpector** | State-of-the-art hybrid Rust/Python graph-based SAST framework, made for CI/CD and large Python codebases. Engineered for high-speed, high-accuracy vulnerability scanning, performing 2.1x faster than Bandit and 3.7x faster than Semgrep. | N/A | [GitHub: PySpector](https://github.com/ParzivalHack/PySpector) |

#### Minor Security Contributions
This list shows the vulnerabilities i found in really small projects, that got fixed and published, though are too small to request a CVE ID for:
- https://github.com/rollopack/MikroTik-Mass-Updater/security/advisories/GHSA-76jf-q6rp-xrqp
- https://github.com/tjcsl/cslbot/security/advisories/GHSA-r2r8-rxr2-5542
- https://github.com/mosandlt/Bosch-Smart-Home-Camera-Tool-HomeAssistant/security/advisories/GHSA-pqpv-xgfh-pmg9

---

## 📜 Relevant Certifications
- **CompTIA:** SecAI+ (in progress).
- **ISC2:** Certified in Cybersecurity (CC), NIST Cybersecurity Framework 2.0.
- **EC-Council:** E|HE, N|DE, D|FE (former Cybersecurity Essentials Series).
- **Security Blue Team:** Blue Team Junior Analyst (BTJA).
- **SkillFront:** ISO/IEC 27001:2022 Associate.
- **Other non-vendor-neutral certifications:** ESET Managed Client Security Specialist, ESET Managed Cloud Security Specialist, Fortinet Certified Associate in Cybersecurity, IBM Roles Processes and Operating System's Security.

---

## 🌐 Connect & Collaborate

[![LinkedIn Badge](https://img.shields.io/badge/-TommasoBona-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tommaso-bona)](https://www.linkedin.com/in/tommaso-bona)
[![Gmail Badge](https://img.shields.io/badge/-tommasobona04@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:tommasobona04@gmail.com)](mailto:tommasobona04@gmail.com)

---

## 📊 GitHub Stats
<div align="left">
  <a href="https://user-badge.committers.top/italy/ParzivalHack">
    <img src="https://user-badge.committers.top/italy/ParzivalHack.svg" alt="committers.top badge">
  </a>
  <br />
  Currently ranked in the <b>Top 250 Developers on Github</b> (in Italy).
</div>

<details>
  <summary><b>📈 View GitHub Metrics</b></summary>
  <p align="center">
    <img alt="GitHub Stats" src="https://github-readme-stats-fast.vercel.app/api?username=ParzivalHack&show_icons=true&hide=issues&icon_color=000000&hide_border=true&title_color=5391FE&text_color=555">
  </p>
</details>
