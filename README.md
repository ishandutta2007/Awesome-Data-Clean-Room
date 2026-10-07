# Awesome-Data-Clean-Room

# Awesome-Data-Clean-Room 🔐 🤝

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Data Clean Room Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Clean-Room"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Data-Clean-Room?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Clean-Room/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Data-Clean-Room?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Clean-Room/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Data-Clean-Room?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Data Clean Room Ecosystem

**Curated List of Commercial Data Clean Room Platforms & Open-Source Privacy-Preserving Analytics Tools**  
*Focused on Multiparty Computation, Trusted Execution Environments, Differential Privacy, Private Set Intersection & Self-Hosted Clean Rooms*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **data clean room platforms**, **open-source privacy-enhancing technologies (PETs)**, and **secure multiparty analytics frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS Clean Rooms*, *Snowflake Data Clean Rooms*, and *InfoSum*), or self-hostable open-source alternatives (like *PrivacyGo Data Clean Room* and *Manatee*), this list covers category leaders, confidential computing, and privacy-respecting data collaboration.

**Key Market Context:**
- **Data clean rooms are the fastest-growing segment of the privacy tech market** — driven by the deprecation of third-party cookies and tightening privacy regulations (GDPR, CCPA).
- **PrivacyGo Data Clean Room (PGDCR)** is the **leading open-source TEE-based clean room**, developed by TikTok and contributed to the **Confidential Computing Consortium under the Linux Foundation** .
- **The two-stage approach** (Programming Stage + Secure Execution Stage) balances **usability, accuracy, and privacy** — allowing data scientists to explore synthetic or DP-protected data before running attested code on real data .

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The data clean room market spans **hyperscaler clean room services** (AWS Clean Rooms, Google Ads Data Hub, Azure Confidential Clean Rooms) that provide **managed infrastructure with TEE or differential privacy**, **data platform clean rooms** (Snowflake, Databricks) that embed clean room capabilities **directly into existing data warehouses**, and **specialized identity-based clean rooms** (InfoSum, Habu, LiveRamp) that focus on **secure data collaboration without raw data sharing**. **AWS Clean Rooms** uses **pay-as-you-go pricing** based on queries and data processed. **Snowflake Data Clean Rooms** charges **per-query or subscription-based** pricing. **InfoSum** uses **custom enterprise pricing** with **no data movement** — data stays in each party's environment.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS Clean Rooms](https://aws.amazon.com/clean-rooms/)** ☁️ | Amazon | ~$2.0 Trillion | **Pay-as-you-go** based on queries and data processed | **Free tier available** | **AWS-native clean room** — **Collaborate on combined datasets without sharing raw data** . **Differential privacy** for aggregate queries. **Analysis rules** enforce query restrictions. **Integrates with S3, Athena, and Glue** . |
| **[Snowflake Data Clean Rooms](https://www.snowflake.com/)** ❄️ | Snowflake | ~$50 Billion | **Per-query or subscription-based** | **Free trial available** | **Data cloud clean room** — **Data stays in each party's Snowflake account** — no movement required . **Analysis rules** define allowed queries. **Snowflake Native App framework** for packaging clean room logic . |
| **[Google Ads Data Hub](https://adsdatahub.google.com/)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **Free for Google Ads customers** | **Free with Google Ads account** | **Google Ads clean room** — **Privacy-safe measurement and attribution** for advertising campaigns . **Aggregation thresholds** prevent user-level identification. **Integrates with BigQuery** . **BigQuery Data Clean Rooms** for custom use cases . |
| **[Azure Confidential Clean Rooms](https://azure.microsoft.com/en-us/products/confidential-clean-rooms/)** 🔷 | Microsoft | ~$3.90 Trillion | **Preview: free**; **GA: custom pricing** | **Limited preview** | **Confidential computing clean room** — **Apache Spark SQL in TEE** protects data from collaborators and Azure operators . **Confidential Consortium Framework (CCF)** for governance and audit. **Open-source containers** on mcr.microsoft.com/cleanroom . **Preview not for production or personal data** . |
| **[Azure Databricks Clean Rooms](https://databricks.com/)** 🧱 | Databricks | ~$43 Billion | **Serverless compute pricing** | **Free trial available** | **Lakehouse clean room** — **OpenSharing for secure data exchange** without copying . **No-trust model** — all collaborators have equal privileges and must approve notebooks before execution . **Central clean room** in isolated serverless compute plane. **Limited to 10 collaborators per clean room** . |
| **[InfoSum](https://www.infosum.com/)** 🔵 | InfoSum | Private | **Custom enterprise pricing** | **Demo available** | **Identity-based clean room** — **No data movement** — data stays in each party's environment . **Federated identity infrastructure** for secure matching. **No raw data or PII exchanged** . |
| **[Habu](https://www.habu.com/)** 🟣 | Habu (LiveRamp) | Private | **Custom enterprise pricing** | **Demo available** | **Data collaboration platform** — **Clean room orchestration** across multiple environments. **Acquired by LiveRamp** for deeper integration . |
| **[LiveRamp Safe Haven](https://liveramp.com/)** 🟢 | LiveRamp | ~$3 Billion | **Custom enterprise pricing** | **Demo available** | **Data collaboration platform** — **Secure data clean room** with **RampID identity resolution** . **Measurement, activation, and analytics** in one platform . |
| **[Decentriq](https://www.decentriq.com/)** 🔒 | Decentriq | Private | **Custom enterprise pricing** | **Demo available** | **Confidential computing clean room** — **TEE-based secure analytics** . **No raw data exposure** . **Swiss-based privacy compliance** . |
| **[Samooha](https://samooha.com/)** ☁️ | Samooha (Snowflake) | Private | **Custom pricing** | **Demo available** | **Data collaboration platform** — **Acquired by Snowflake** to accelerate clean room adoption. **No-code clean room creation** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[PrivacyGo Data Clean Room (PGDCR)](https://github.com/tiktok-privacy-innovation/PrivacyGo-DataCleanRoom)** [![Stars](https://img.shields.io/github/stars/tiktok-privacy-innovation/PrivacyGo-DataCleanRoom?style=social&color=white)](https://github.com/tiktok-privacy-innovation/PrivacyGo-DataCleanRoom/stargazers)  
  **Open-source TEE-based data clean room for secure trusted research & AI collaboration**, open-source. **Developed by TikTok** and contributed to the **Confidential Computing Consortium (CCC) under the Linux Foundation** — now maintained as **Manatee** . **Two-stage architecture**: **Programming Stage** allows data scientists to explore **synthetic, DP-protected, or partial public data** in Jupyter Notebook, while **data providers control the protection mechanism** . **Secure Execution Stage** builds the notebook into an image and schedules it to **confidential virtual machines (CVMs)** in the cloud — only **attested programs can fetch data** . **Data providers control which program can access their data** via attestation. **TEE provides JWT-based attestation report** publicly verifiable for authenticity . **Use cases**: Trusted Research Environments (TREs), advertisement lookalike analysis, and **machine learning with private data or models** . **Current limitations**: one-way collaboration, single backend (GCP), manual provisioning/policy/attestation, CPU-only . **The most production-proven open-source data clean room** — powers TikTok's Research Tools Virtual Compute Environment . 🏛️

- **[Manatee (Confidential Computing Consortium)](https://github.com/manatee-project/manatee)** [![Stars](https://img.shields.io/github/stars/manatee-project/manatee?style=social&color=white)](https://github.com/manatee-project/manatee/stargazers)  
  **Open-source multi-party data collaboration platform**, open-source. **The successor to PrivacyGo Data Clean Room** — now maintained by the **Confidential Computing Consortium under Linux Foundation** . **Two-stage architecture**: **Programming Stage** with Jupyter Notebook integration for **interactive exploration of synthetic or DP-protected data**, and **Secure Execution Stage** running **attested code in TEEs** on cloud confidential VMs . **Data providers set policy on which attested programs can access their data** . **TEE provides JWT-based attestation report** for verifiable execution integrity . **Active development** by the CCC community — the future of open-source clean rooms. 🌊

- **[aws-data-wrangler](https://github.com/awslabs/aws-data-wrangler)** [![Stars](https://img.shields.io/github/stars/awslabs/aws-data-wrangler?style=social&color=white)](https://github.com/awslabs/aws-data-wrangler/stargazers)  
  **AWS pandas integration library and data pipeline framework**, Apache-2.0 licensed. **Executes secure queries within a privacy-preserving clean room environment** to retrieve results as dataframes . **Moves and transforms data between local memory and AWS storage/analytics services** . **Distributed compute orchestrator** for EMR clusters. **Specialized clean room integration** for AWS Clean Rooms. **The most practical Python library for AWS clean room workflows**. 🐼

- **[aws-sdk-pandas](https://github.com/aws/aws-sdk-pandas)** [![Stars](https://img.shields.io/github/stars/aws/aws-sdk-pandas?style=social&color=white)](https://github.com/aws/aws-sdk-pandas/stargazers)  
  **Pandas on AWS — unified interface for cloud data**, Apache-2.0 licensed. **Executes protected SQL queries within secure data clean rooms** and returns results as dataframes . **Distributed compute orchestration** via EMR and Ray. **The official AWS SDK for pandas** — the foundation for aws-data-wrangler. ☁️

- **[OpenEnv Data Cleanser](https://huggingface.co/spaces/sairaj2/DataCleanser)** [![Stars](https://img.shields.io/github/stars/...?style=social&color=white)](https://github.com/.../stargazers)  
  **Dockerized FastAPI data cleaning environment**, open-source. **OpenEnv-style data cleaning environment** with `/reset` and `/step` endpoints . **Simulates real-world data engineering workflows** — filling missing values, deduplication, format standardization, and outlier detection. **Dense reward signal** for quality improvement. **The most accessible open-source data preparation environment** — relevant for clean room data readiness. 🧼

- **[Cleanlab](https://github.com/cleanlab/cleanlab)** [![Stars](https://img.shields.io/github/stars/cleanlab/cleanlab?style=social&color=white)](https://github.com/cleanlab/cleanlab/stargazers)  
  **Standard data-centric AI package for data quality and machine learning with messy real-world data and labels**, open-source. **11,000+ GitHub stars** . **Data quality assessment** and **label error detection** — critical for ensuring clean room input data integrity. **The most widely used open-source data quality library** . 🧪

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new data clean room platforms or open-source privacy-preserving analytics software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Data-Clean-Room&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Data-Clean-Room&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this data clean room repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow privacy engineers, data collaboration teams, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Azure Confidential Clean Rooms is in limited preview** and **should not be used to process personal data or data subject to legal/regulatory compliance requirements** . **Preview is for testing, evaluation, and feedback only** .
- **Azure Databricks Clean Rooms uses a "no-trust" model** — all collaborators have equal privileges and **must approve notebooks before execution** . **Clean rooms are locked after creation** — no new collaborators can join. **Limited to 10 collaborators per clean room** .
- **PrivacyGo Data Clean Room (PGDCR) is in alpha** — current limitations include **one-way collaboration, single backend (GCP), manual provisioning/policy/attestation, and CPU-only compute** . **The project has been contributed to the Confidential Computing Consortium** and is now maintained as **Manatee** .
- **Open-source clean room tools are not turnkey** — they require **TEE-enabled hardware (Intel SGX, AMD SEV), cloud infrastructure (GCP, Azure), and attestation infrastructure** . **Always validate privacy guarantees and attestation verification with a proof-of-concept** before production deployment. 🔐

---

<p align="center">
  <b>Made with ❤️ for privacy engineers, data collaboration teams, and open-source clean room advocates.</b>
</p>
