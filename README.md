# Technology Certification Study Guides

Interactive, self-contained HTML study guides for six entry-to-practitioner technology certifications. Designed for someone working full time who wants to move from a non-technical role into a technology manager position within 12 months. No dependencies, no internet connection required — open any file directly in a browser.

---

## Guides

| File | Certifications | Study Weeks |
|------|---------------|-------------|
| `tech_roadmap.html` | All six — master timeline & career guide | Full 52-week plan |
| `tech_foundations.html` | CompTIA ITF+ · CompTIA Network+ | Weeks 1–8, 25–32 |
| `tech_azure_microsoft.html` | Microsoft AZ-900 · AI-900 | Weeks 9–16 |
| `tech_aws_ai.html` | AWS CLF-C02 · AWS AIF-C01 | Weeks 17–24, 33–40 |

Start with `tech_roadmap.html` — it explains the full plan and links to all three study guides.

---

## Certifications

| Certification | Exam Code | Cost | Format | When |
|--------------|-----------|------|--------|------|
| CompTIA IT Fundamentals+ | ITF+ | ~$130 | 75 questions, 60 min | Month 1–2 |
| Microsoft Azure Fundamentals | AZ-900 | $165 | 40–60 questions, 60 min | Month 3 |
| Microsoft Azure AI Fundamentals | AI-900 | $165 | 40–60 questions, 60 min | Month 4 |
| AWS Cloud Practitioner | CLF-C02 | $100 | ~65 questions, 90 min | Month 5–6 |
| CompTIA Network+ | N10-009 | ~$358 | 90 questions, 90 min | Month 7–8 |
| AWS AI Practitioner | AIF-C01 | $100 | ~65 questions, 90 min | Month 9–10 |

---

## 12-Month Study Plan

Designed around ~8–10 hours per week: 45–60 minutes on weekdays, 2 hours on each weekend day.

| Month | Guide | Milestone |
|-------|-------|-----------|
| 1–2 | `tech_foundations.html` | ✅ Earn CompTIA ITF+ |
| 3 | `tech_azure_microsoft.html` | ✅ Earn Microsoft AZ-900 |
| 4 | `tech_azure_microsoft.html` | ✅ Earn Microsoft AI-900 |
| 5–6 | `tech_aws_ai.html` | ✅ Earn AWS Cloud Practitioner |
| 7–8 | `tech_foundations.html` | ✅ Earn CompTIA Network+ |
| 9–10 | `tech_aws_ai.html` | ✅ Earn AWS AI Practitioner |
| 11–12 | `tech_roadmap.html` | Career positioning & job search |

---

## What's Covered

### IT Foundations (`tech_foundations.html`)
- **How Computers Work** — CPU, RAM, storage hierarchy, data units, BIOS/POST
- **Operating Systems** — Windows, macOS, Linux comparison; file systems; virtualization (Type 1 vs Type 2)
- **Networking Fundamentals** — OSI 7-layer model, IPv4/IPv6, key port numbers, network hardware
- **Security Basics** — CIA Triad, threat types (phishing, DDoS, ransomware, MitM, BEC), MFA factors, encryption
- **TCP/IP & Advanced Networking** — TCP vs UDP, subnetting/CIDR, VPN types, wireless security (WEP/WPA/WPA2/WPA3)
- **Troubleshooting & IT Support** — CompTIA 7-step methodology, ITIL concepts, manager-level thinking

### Azure & Microsoft AI (`tech_azure_microsoft.html`)
- **Cloud Concepts** — 5 NIST characteristics, deployment models, IaaS/PaaS/SaaS, CapEx vs OpEx, Shared Responsibility
- **Core Azure Services** — Global infrastructure, compute (VMs, App Service, Functions, AKS), storage, databases, networking
- **Security, Pricing & Governance** — Microsoft Entra ID, RBAC, Key Vault, Defender for Cloud, pricing models (PAYG/Reserved/Spot), Management Groups, Azure Policy
- **AI & ML Foundations** — Supervised/unsupervised/reinforcement learning, ML workflow, key terminology
- **Azure AI Services** — Computer Vision, Language, Speech, Translator, Document Intelligence, Custom Vision, OpenAI Service, Bot Service
- **Generative AI & Responsible AI** — LLMs, tokens, RAG, prompt engineering, Copilot ecosystem, Microsoft's 6 Responsible AI principles (Fairness, Reliability & Safety, Privacy & Security, Inclusiveness, Transparency, Accountability)

### AWS & AI (`tech_aws_ai.html`)
- **Cloud Concepts & AWS Infrastructure** — 6 cloud advantages, deployment models, Regions, Availability Zones, Edge Locations
- **Core AWS Services** — EC2, Lambda, ECS/EKS, S3 (all storage classes), RDS, Aurora, DynamoDB, VPC, CloudFront, Route 53
- **Security, Compliance & Pricing** — Shared Responsibility Model, IAM (users/groups/roles/policies), Shield, WAF, GuardDuty, CloudTrail, pricing models, support plans
- **Well-Architected Framework** — All 6 pillars (Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability), migration strategies (7 Rs)
- **AWS AI/ML Services** — SageMaker (full lifecycle), Rekognition, Textract, Comprehend, Transcribe, Polly, Translate, Lex, Kendra, Personalize, Forecast, Fraud Detector
- **Generative AI on AWS** — Amazon Bedrock, Foundation Models, Knowledge Bases (managed RAG), Guardrails, Agents, prompt engineering techniques, responsible AI risks and mitigations

---

## How to Use

1. **Clone or download** this repository
2. **Open `tech_roadmap.html`** in a browser for the full plan and navigation links
3. **Work through each guide's modules in order** — the final exam unlocks only after all modules are completed
4. **Read every quiz answer explanation** — feedback is written to teach the concept, not just confirm the answer
5. **Use free official resources alongside these guides:**
   - [Microsoft Learn](https://learn.microsoft.com) — free AZ-900 and AI-900 learning paths
   - [AWS Skill Builder](https://skillbuilder.aws) — free CLF-C02 and AIF-C01 courses
   - [CompTIA CertMaster Learn](https://www.comptia.org) — official practice exams

---

## File Structure

```
├── tech_roadmap.html                # 52-week plan, milestones, career guide
├── tech_foundations.html            # CompTIA ITF+ & Network+
├── tech_azure_microsoft.html        # Microsoft AZ-900 & AI-900
├── tech_aws_ai.html                 # AWS CLF-C02 & AIF-C01
└── README.md
```

---

## Technical Notes

- **No external dependencies** — all CSS and JavaScript is inline; no CDN calls, no web fonts, no analytics
- **No data collection** — nothing is stored, transmitted, or tracked; quiz scores exist only in your browser session and reset on page refresh
- **Works offline** — fully functional without an internet connection
- **Tested in** Chrome, Firefox, Edge, and Safari

---

## Disclaimer

These guides are independent study aids and are not affiliated with, endorsed by, or produced by Microsoft, Amazon Web Services, or CompTIA. Exam objectives, domain weightings, and passing scores are subject to change — always verify current requirements on the official certification websites before scheduling your exam.
