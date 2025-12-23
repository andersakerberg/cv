<style>
/* PDF Optimization - Professional Page Breaks */
@page {
  margin: 1.5cm;
  size: A4;
}

body {
  font-size: 11pt;
  line-height: 1.4;
  orphans: 3;
  widows: 3;
}

h1 {
  margin-top: 0.5em;
  margin-bottom: 0.3em;
  page-break-after: avoid;
  orphans: 3;
  widows: 3;
}

h2 {
  page-break-before: auto;
  page-break-after: avoid;
  page-break-inside: avoid;
  margin-top: 0.8em;
  margin-bottom: 0.4em;
  font-size: 1.3em;
  orphans: 3;
  widows: 3;
}

/* Force page break before major sections if less than 3 lines remain */
h2:has(+ h3),
h2:has(+ p) {
  page-break-before: auto;
}

h3 {
  page-break-after: avoid;
  page-break-inside: avoid;
  margin-top: 0.6em;
  margin-bottom: 0.3em;
  font-size: 1.1em;
  orphans: 2;
  widows: 2;
}

/* Experience entry block - keep together (most important) */
h3 + p {
  page-break-inside: avoid;
  page-break-before: avoid;
}

h3 + p + p {
  page-break-inside: avoid;
  page-break-before: avoid;
}

h3 + p + p + p {
  page-break-inside: avoid;
  page-break-before: avoid;
}

/* Keep job descriptions with their headings */
h3 {
  page-break-after: avoid;
}

/* Keep technologies and impact with experience */
p strong:first-child {
  page-break-before: avoid;
}

p {
  margin-top: 0.4em;
  margin-bottom: 0.4em;
  orphans: 2;
  widows: 2;
}

/* Keep lists completely together */
ul, ol {
  page-break-inside: avoid;
  page-break-before: avoid;
  margin-top: 0.3em;
  margin-bottom: 0.3em;
  padding-left: 1.2em;
}

li {
  margin-bottom: 0.2em;
  page-break-inside: avoid;
}

/* Keep Key Achievements list together */
h3 + ul {
  page-break-inside: avoid;
  page-break-after: avoid;
  page-break-before: avoid;
}

/* Horizontal rules - don't break after */
hr {
  page-break-after: avoid;
  page-break-before: auto;
  margin: 0.6em 0;
  border: none;
  border-top: 1px solid #ddd;
}

/* Tables - keep together */
table {
  page-break-inside: avoid;
  page-break-before: auto;
  margin: 0.5em 0;
  font-size: 0.95em;
}

tr {
  page-break-inside: avoid;
}

/* Keep sections with their content */
h2 + h3 {
  page-break-before: avoid;
}

h2 + p {
  page-break-inside: avoid;
}

h3 + table {
  page-break-inside: avoid;
  page-break-before: avoid;
}

/* Prevent single lines at page top/bottom */
p, li {
  orphans: 2;
  widows: 2;
}

/* Better spacing control */
div {
  page-break-inside: avoid;
}

/* Force page break before major sections if needed */
h2:nth-of-type(n+2) {
  page-break-before: auto;
}

/* Keep paragraphs with their preceding elements */
h3 ~ p {
  orphans: 2;
  widows: 2;
}
</style>

<div style="display: flex; align-items: center; gap: 20px;">
<div>

# Anders Åkerberg
## Senior Fullstack Developer and DevOps Engineer

</div>
<img src="image.png" alt="Profile Picture" style="max-width: 90px; height: auto; border-radius: 10px; flex-shrink: 0;" />
</div>

**15+ Years of Experience** | **Bridging Development and Operations**

**Contact**  
📧 Email: [akerberganders@gmail.com](mailto:akerberganders@gmail.com) | 📱 Phone: +46769475405 | 📍 Location: Malmö, Sweden  
🌐 [LinkedIn](https://www.linkedin.com/in/anders-%C3%A5kerberg-79015b40/) | [GitHub](https://github.com/andersakerberg)

## Summary

Senior Fullstack Developer and DevOps Engineer with 15+ years of experience delivering scalable solutions for enterprise clients including IKEA, Apple, and E.ON. Equally proficient in both roles, seamlessly transitioning between building applications and managing infrastructure.

**As a Fullstack Developer:** Strong background using C#, JavaScript, Node.js, React, Vue, and Angular, with extensive experience in database design and optimization across SQL Server, PostgreSQL, Oracle, and BigQuery. Proven track record of architecting high-performance systems handling tens of thousands of requests per minute and modernizing legacy applications with microservices architectures.

**As a DevOps Engineer:** Deep expertise in Infrastructure as Code, CI/CD pipelines, and container orchestration using Kubernetes and Docker. Experienced across AWS, Azure, and GCP, establishing robust DevOps practices that enable seamless deployments and reliable production environments.

The combination of Fullstack Development and DevOps Engineering enables end-to-end ownership of projects—from writing application code to deploying and maintaining infrastructure. This dual expertise eliminates handoff friction, accelerates delivery cycles, and ensures applications are built with production-ready infrastructure from the start.

## Core Technologies

**Languages & Frameworks:** C#, React, Node.js, Vue.js, Angular, TypeScript

**Cloud & Infrastructure:** AWS, Azure, GCP, Kubernetes, Docker

**DevOps & Tools:** Terraform, CI/CD, GitHub Actions, Infrastructure as Code, Ansible, Pulumi

**Databases:** Microsoft SQL Server, PostgreSQL, Oracle

**Methodologies:** Agile, Continuous Delivery, SAFe, Scrum, Kanban


## Experience

### IKEA (B3) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span>   
*August 2024 - April 2025*

As a Fullstack Developer, responsible for delivering the platform that showcases prognosis of all KPIs in the INGKA platform, ranging from sales figures to employee satisfaction.

**Technologies:** Node.js, Vue 3, PostgreSQL, Containerization, BigQuery, Git, GCP, Big Data, Agile

### QuickButik (Fulltime) <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span> 
*May 2024 - August 2024*

DevOps Engineer for an e-commerce platform hosted on AWS, serving approximately 5,000 subscribers annually. Small team of ten: Developers, DevOps, Manager, Product Owner, and UX.

**Technologies:** PHP, Laravel, Bash, Terraform, Containerization, Architect, Cloud, Agile

### E.ON (B3) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span> <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span>
*May 2022 - March 2024*

Responsible for several applications. The team consisted of more than 20 people working with JavaScript and C#, .NET Core. The team followed agile methodologies and implemented DevOps practices using Infrastructure as Code (IaC) with Terraform, managing databases such as MSSQL and Oracle, and infrastructure in Azure. The assignment required a security clearance from SÄPO (Swedish Security Service).

**Technologies:** C#, .NET Core, AngularJS, API, App services, Application Insights, Azure AD, Azure Cache for Redis, Azure DevOps, Azure Key Vault, Azure NAT Gateway, Azure Private Endpoints, Azure SQL, Azure Virtual Network, Cloud Functions, Entra ID, Grafana, Infrastructure, Infrastructure as Code, Internal Routing, Load Balancing, Microsoft SQL Server, MS Azure, Node.js, Oracle, Private Networking, React.js, Role-Based Access Control, Service Bus, Subnets, Terraform, Containerization, Vue.js, Git

**Impact:** Managed multiple applications for a team of 10+ developers, implemented comprehensive DevOps practices with Infrastructure as Code, and maintained systems requiring highest security clearance standards.

### Trygg-Hansa (B3) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span>  
*November 2021 - May 2022, Malmö*

Rebuilt legacy systems to modernize them with C#, .NET Core Microservices and Kubernetes. The team was based in Stockholm, and I worked remotely from Malmö. The team's tasks were continuously managed. This short-term project was completed with excellent results.

**Technologies:** C#, .NET Core, Microservices, Containerization, Kubernetes, Git

### Sharkmob (B3)  <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span> 
*March 2021 - November 2021, Malmö*

Helped Sharkmob deliver their first game under Tencent (https://bloodhunt.com/en-us), collaborating with experts from Google to deliver the most robust Google Kubernetes Engine environment in GCP to date. Handled tens of thousands of requests per minute, managed the load balancing environment, and built everything from scratch using Terraform.

**Technologies:** Scala, Java, Jenkins, Node.js, React, PostgreSQL, MySQL, GitHub (Expert), Terraform, Spinnaker, Ansible, Containerization, Kubernetes

### Apple (B3) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span> <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span>
*November 2020 - March 2021, Malmö*

Helped rebuild their cloud platform to deliver seamless deployments in their private cloud. Built the backbone for the source control build system. Essentially, we built our own GitHub. Worked with experts from the US and Sweden to deliver a seamless experience for developers.

**Technologies:** Scala, Java, Jenkins, Node.js, React, PostgreSQL, MySQL, GitHub (Expert), Terraform, Spinnaker, Ansible, Containerization, Kubernetes

### IKEA IT (Sogeti) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span> <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span>
*March 2019 - November 2020*

**DevOps Engineer:** Delivered code in a seamless end-to-end flow. Monitored multiple systems simultaneously in one dashboard interface, sending notifications on multiple channels when problems occurred. Built content based on the interests of developers and engineers to help everyone achieve more and improve their work in an inspiring way.

**Software Developer:** Developed applications across a wide range of teams, working with a total of six teams over 1.5 years, providing support wherever needed.

**Technologies:** BigQuery, Cloud Functions, Docker, Containerization, Elasticsearch, GCP App Engine, GCP Cloud Build, GCP Cloud Run, GCP Compute Engine, GCP Google Kubernetes Engine, GitHub, GitHub Actions, GitLab, Google Cloud KMS, Google Cloud Platform/GCP, Google Data Studio, Google Looker Studio, Grafana, HTML5, Java, JavaScript, Kubernetes, Node.js, PostgreSQL, Python, React.js, Storage, Terraform, Git

**Impact:** Delivered seamless end-to-end deployments, monitored multiple systems via unified dashboard, and supported 6 different teams over 1.5 years, enabling faster delivery cycles across the organization.

### Itello (Consid)  <span style="display: inline-block; padding: 4px 10px; margin-left: 4px; background: #28a745; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">DevOps Engineer</span> 
*February 2018 - March 2019, Stockholm*

Worked closely with several development and operations teams to bring both parties closer together and identify their needs. Since Itello ran container-based solutions that worked across different customers, it was essential to have simple and easily configurable workflows for solution experts.

**Technologies:** Java, Node.js, Python, Containerization, Git, Jenkins, Insurance-systems, Pensions

### FlygBRA (Consid) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span>   
*January 2010 - February 2019*

Worked in different roles across various projects, including Software Developer, Azure DevOps Engineer, and Azure Architect. Worked with Azure Web Apps in a scaled environment managing redundant information. Used services such as Azure Service Bus and Redis to meet the complex needs of several different platforms. Combined developer knowledge with server mechanics expertise to deliver applications and set up environments that performed well in production.

**Technologies:** C#, .NET, .NET Core, .NET MVC, Amadeus Web Services, Azure DevOps, Docker, Containerization, IATA knowledge, Java, Kubernetes, MS Azure, Node.js, Python, Redis, Service Bus, Sitecore, SOAP, TypeScript, Umbraco CMS, Git

### Sirius International (Consid) <span style="display: inline-block; padding: 4px 10px; margin-left: 8px; background: #007bff; color: white; border-radius: 12px; font-size: 0.75em; font-weight: 600;">Fullstack Developer</span> 
*February 2011 - June 2013, Stockholm*

Worked closely with their reinsurance team to provide a mathematical overview of upcoming fictitious disasters around the world. Used advanced mathematical lab code and translated it into C#. The application could be installed on individual computers, running with their standard data system and displaying information in a graphically intuitive way to provide effective monitoring.

**Technologies:** C#, WPF, Graphs, MATLAB, Git

## Education

### Örebro University
**Computer Science**  
*August 2007 - June 2010*

Studied Computer Science with a focus on software development and system design. 

Graduated with a project that involved creating a mobile interaction system for farmers in Bangladesh. The solution enabled farmers to broadcast their crop yields to local markets via SMS, helping them connect directly with buyers and improve their market access. This project combined mobile technology, data communication, and user-centered design to address real-world agricultural challenges in developing regions.

### Career Timeline

| Company/Institution | Period |
|---------------------|--------|
| B3 | Aug 2024 - Apr 2025 |
| QuickButik | May 2024 - Aug 2024 |
| B3 | Nov 2020 - May 2024 |
| Sogeti | Mar 2019 - Nov 2020 |
| Consid | Jan 2010 - Mar 2019 |
| Örebro University | Aug 2007 - Jun 2010 |

## Notable Projects & Open Source Contributions

### AIXCL - Local AI Development Platform
**Contributor** | [GitHub Repository](https://github.com/xencon/aixcl)

Contributing to AIXCL, an opinionated AI development platform and curated composition of upstream open-source projects. The platform provides a cohesive local and single-node AI development experience, enabling developers to run LLMs locally, orchestrate multiple models, and integrate AI assistance directly into their development workflow.

**Technologies:** Docker, Docker Compose, Ollama, LLM-Council, PostgreSQL, Prometheus, Grafana, Loki, Bash, Python, Shell

**Key Contributions:**
- Containerized architecture with strict separation between runtime core and operational services
- Profile-based deployment system (usr, dev, ops, sys) for different use cases
- Unified CLI for platform management and service orchestration
- Multi-model orchestration and coordination system

### Foo Café - Tech Community Website
**Maintainer & Host** | [Website](https://foocafe.org/)

Maintaining and hosting the Foo Café website, a platform for the Swedish tech community that organizes tech talks, meetups, and events including the DevOps Comedy Club. Responsible for infrastructure management, updates, and ensuring reliable hosting for community events.

**Technologies:** PHP, Drupal, Web Hosting, Infrastructure Management

**Impact:** Enables the tech community to organize and promote events, fostering knowledge sharing and networking within the Swedish developer ecosystem.

## Competences

### Level 5 - Expert
C#, Continuous Delivery, DevOps Engineer, Docker, Entity Framework Core, Fullstack Developer, Google Cloud Platform/GCP, Infrastructure as Code, Kubernetes, Lead Developer, Microsoft SQL Server, MS Azure, Node.js, React.js, Terraform, Vue.js

### Level 4 - Advanced
.NET MVC, Agile, AngularJS, API, AWS, Azure AD, Azure DevOps, Azure Pipelines, Azure SQL, CI/CD, Cloud Functions, DevOps, Entra ID, GCP App Engine, GCP Cloud Build, GCP Cloud Run, GCP Compute Engine, GCP Google Kubernetes Engine, Github Actions, Google Cloud KMS, Gradle, HTML5, Infrastructure, JavaScript, Load Balancing, Maven, Microservices, NuGet, PostgreSQL, SOAP, SQL, TFS, TypeScript

### Level 3 - High Competence
App services, Application Insights, Azure Cache for Redis, Azure Key Vault, Azure NAT Gateway, Azure Private Endpoints, Azure Virtual Network, BigQuery, Google Data Studio, Google Looker Studio, Internal Routing, Private Networking, Redis, Role-Based Access Control, Service Bus, Storage, Subnets

## Languages

| Language | Proficiency |
|----------|-------------|
| Swedish | Native or bilingual proficiency |
| English | Full professional proficiency |

## Additional Information

**Tech Talks & Community:** Active speaker at tech events including [Foo Café's DevOps Comedy Club](https://foocafe.org/event/devops-comedy-club-hear-horror-stories). Uses speaking engagements as a learning methodology to master new technologies through deep-dive sessions. Also maintains and hosts the Foo Café community website.


**Availability:** Available for consulting and full-time opportunities
