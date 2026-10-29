# Waleed Mazhar
### Senior Software Engineer · Backend Systems, APIs & Cloud

I build and improve business software across backend services, APIs, databases and web applications. I bring **8+ years of commercial experience**, hands-on technical leadership, and an **MSc in Artificial Intelligence with Distinction** from the University of the West of Scotland.

**Glasgow, UK · Open to UK relocation · Software, backend and full-stack engineering opportunities**

[Connect on LinkedIn](https://www.linkedin.com/in/waleed-mazhar/)

## Commercial delivery

| Responsibility | Outcome and context |
| --- | --- |
| Technical leadership | Led five developers on Seller Legend, a SaaS analytics platform serving 10,000+ Amazon sellers. |
| Workflow improvement | Redesigned purchasing and warehouse-transfer workflows, reducing processing time by 60%. |
| Maintainability | Refactored 100+ Angular/TypeScript components. |
| End-to-end delivery | Built APIs, database integrations and AWS workflows, and supported releases and production troubleshooting. |

These describe my commercial work at Histone Solutions. The public projects below are separate examples; they are not the proprietary Seller Legend codebase.

## Explore the engineering

### 1. EvenUpEZ — keeping every penny in a shared expense
A group-expense application with a concrete correctness case study: a 10.00 expense split three ways must still total 10.00.

- **Design:** integer minor units, deterministic remainder allocation and a domain service separated from HTTP handling.
- **Verification:** 234 isolated checks and three authenticated HTTP/database tests (12 assertions) per PHP version in the linked passing CI run.
- **Trade-offs:** predictable remainder ordering, input validation and explicit boundaries of test coverage.

[Case study](https://github.com/waleedmazhar64/evenupEZ-backend/blob/main/docs/expense-allocation-case-study.md) · [Code and tests](https://github.com/waleedmazhar64/evenupEZ-backend) · [Merged change](https://github.com/waleedmazhar64/evenupEZ-backend/pull/2) · [Passing CI](https://github.com/waleedmazhar64/evenupEZ-backend/actions/runs/40808061174) · [Frontend](https://github.com/waleedmazhar64/evenupEZ-frontend)

The recent allocation improvement was developed with AI assistance. Its tests cover that change, not the security or production readiness of the whole application.

### 2. HR AI Agent — workflow orchestration across services
An MSc project integrating a Laravel workflow backend with a Python/Flask service. Resume matching uses TF-IDF and cosine similarity; interview-analysis components include academic placeholders.

[Repository and scope](https://github.com/waleedmazhar64/hr-ai-agent) · [Python service](https://github.com/waleedmazhar64/hr-ai-agent/tree/main/python-api)

### 3. MelioHealth — healthcare application integration
An application prototype covering account flows, patient notes, profile management and audio-to-note integration. Read the repository scope and implementation status before running a demo.

[Backend](https://github.com/waleedmazhar64/meliohealth-backend) · [Frontend](https://github.com/waleedmazhar64/meliohealth-frontend)

## Engineering toolkit

- **Backend and data:** PHP, Laravel, REST APIs, MySQL, service integration.
- **Web applications:** TypeScript, JavaScript, Angular, RxJS.
- **Delivery:** AWS, Docker, Git, CI/CD and production troubleshooting.
- **Academic AI work:** Python, Flask, Scikit-learn, TF-IDF and cosine similarity.

I am interested in roles where I can own delivery, improve existing systems and work closely with product and engineering teams.

## Reading the other repositories

The account also contains older exercises, framework starters, an upstream template fork and deployment snapshots. Their READMEs distinguish source projects from generated output. Start with the selected work above for the clearest examples.
