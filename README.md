# 🚀 Portfolio: Wachirawit (Tan)

Welcome to my project showcase repository. This space is dedicated to documenting my engineering journey, system designs, and Architecture Decision Records (ADRs). Rather than just showing code, this repository focuses on the "Why" behind the "How"—demonstrating strategic technical decisions across enterprise and personal projects.

## 🛠 Tech Stack & Expertise
- **Backend**: Node.js (NestJS), TypeScript, TypeORM, SQL/No-SQL.
- **Frontend**: React (Next.js), Angular, Tailwind CSS, Shadcn UI.
- **Infrastructure**: AWS (VPC, EC2, EBS, S3, ECS), Docker.
- **DevOps**: GitHub Actions (CI/CD Pipelines).

## 📂 Featured Projects

### 1. Claim OS [Details](claim-outsourcing-management/README.md)
- End-to-end Insurance Claim Management System.
- Focus: Cost-aware Architecture & Cloud Automation.
- Key Achievement: Architected a production-ready system on AWS with a strict focus on cost-efficiency.
- Highlights: Implemented EC2 Savings Plans to optimize monthly burn.

### 2. Line Web Chat Hands-on [Details](https://github.com/wachirawitS/webchat-hands-on)
**Live Demo**: [Link](https://webchat-hands-on-idgr.vercel.app/)
- Omni-channel Messaging Integration using Line Messaging API and Next.js.
- Focus: Event-Driven Integration & Serverless Scalability.
- Key Achievement: Designed a seamless Event-Driven Webhook architecture to handle real-time messaging with 0$ idle infrastructure cost.
- Highlights: - Implemented a Full-stack Serverless approach on Vercel, ensuring the system scales instantly with incoming chat traffic.


## 💡 Engineering Philosophy
I believe in building software that is:
- Maintainable: Clean, modular code that is easy for teams to scale.
- Cost-Effective: Leveraging Cloud Native features to provide maximum business value at minimum cost.
- Security-First: Proactive remediation and adherence to compliance standards.

## 🏗 Frontend Architecture & Team Management Playbook
I believe in leading through systems, well-defined boundaries, and documentation rather than micromanagement. A well-architected project should naturally guide the team toward best practices, allowing developers to work autonomously. [Details](https://github.com/wachirawitS/next-feature-base-structure)

**1. Code Structure & Architectural Strategy**
- **Feature-Based Architecture:** Structuring applications by **Domain/Feature** (e.g., Claims, Users) rather than file types. This ensures isolation, prevents bloated folders, and makes onboarding new developers straightforward.
- **Strict Module Boundaries:** Enforcing cross-feature communication via strict contracts (e.g., utilizing `index.ts` barrel files as public APIs). Feature A should never directly mutate the internal state of Feature B.
- **Scalable Ecosystems:** Utilizing Monorepo strategies (where applicable) to share UI components (Shadcn) and core logic seamlessly across different user roles (Admin vs. Customer portals).

**2. Developer Experience (DX) & Team Workflow**
- **Doc-Driven Development:** Relying on Architecture Decision Records (ADRs) and comprehensive READMEs as the team's single source of truth.
- **Automated Guardrails:** Leveraging CI/CD pipelines to enforce code formatting, linting, and basic tests. This keeps Code Reviews focused on logic and architectural impact rather than syntax nitpicking.
- **Git Workflow:** Standardized PR processes with required approvals, ensuring main branches are permanently deployable.

**3. Delivery Strategy**
- **Timeboxing & MVP:** Prioritizing "Minimum Viable Portfolios/Products" to deliver concrete value fast. 
- **Done over Perfect:** Focusing on completing the core engine and demonstrating the overarching structure before optimizing minor details.

## 📫 Contact & Links
- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/wachirawit-sihawong)
- **Email**: wachirawit.ntsi@gmail.com
- **Resume**: [Resume](resume.pdf)