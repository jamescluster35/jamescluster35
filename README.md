markdown
# Hi there, I'm M Haresh Kumar 👋
### Senior Software Architect & Automation Engineer
I design and implement high-performance web applications, serverless microservices, and custom business automation pipelines. Specialize in connecting client-side applications with cloud platforms, Google Workspace APIs, and secure database frameworks.
---
## 🛠️ Core Capabilities
<table>
  <tr>
    <td valign="top" width="50%">
      <h3>💻 Languages & Frontend</h3>
      <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /></a>
      <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>
      <a href="https://html.spec.whatwg.org/"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /></a>
      <a href="https://www.w3.org/Style/CSS/"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" /></a>
      <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /></a>
    </td>
    <td valign="top" width="50%">
      <h3>⚙️ Backend & Infrastructure</h3>
      <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" /></a>
      <a href="https://developers.google.com/apps-script"><img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white" /></a>
      <a href="https://workers.cloudflare.com/"><img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>
      <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /></a>
      <a href="https://git-scm.com/"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /></a>
    </td>
  </tr>
</table>
---

## ⚡ Featured Architecture & Systems
### 1. [Revenue Leakage Calculator & PDF Engine](https://github.com/jamescluster35/revenue-leakage-calculator)
* A high-converting diagnostic calculator that computes operational leakage server-side, protecting IP.
* Generates custom 6-page PDF audits dynamically and routes HTML email delivery pipelines via Google Apps Script.
* Integrates with a secure, passwordless client progress tracking portal.
### 2. [Executive Leads CRM Dashboard](https://github.com/jamescluster35/bdl-leads-pro-crm)
* A React/Vite administration panel for tracking lead acquisition, outbound outreach stages, and conversions.
* Normalizes lead casing and data streams, featuring interactive status-based filtering and instant search.
* Communicates securely with the database via a custom Cloudflare Workers API Proxy.
### 3. [Outlook Sent Campaign Scraper](https://github.com/jamescluster35/revenue-leakage-calculator/tree/main/scripts)
* Automation utility scripts written in Python/PowerShell to parse Outlook sent folders, deduplicate campaigns, sweep email bounces, and synchronize records back to the main Google Sheets CRM.
---
## 📐 System Integration Blueprint
This diagram illustrates the secure, serverless infrastructure I architected to power our lead generation and tracking systems:
```mermaid
graph TD
    Client[Client Browser] -->|1. Submit Calculator Input| Proxy[Cloudflare Workers API Proxy]
    Proxy -->|2. Secure Redirect / Forward| GAS[Google Apps Script Backend]
    GAS -->|3. Save Lead & Checklist State| GSheets[(Google Sheets CRM Database)]
    GAS -->|4. Generate custom PDF & Mail Out| ClientEmail[Client Inbox]
    
    Admin[Admin CRM Portal] -->|1. Request Metrics & Filter Leads| Proxy
    Outlook[Outlook Campaign Script] -->|Sync Outbound Drips & Bounces| GSheets
📊 Github Analytics
Top Languages: JavaScript, HTML, CSS, Python, Apps Script
Core Focus: APIs, Cloud Integration, System Architecture
✉️ Connect With Me
Email: 

jamescluster35@gmail.com
Location: Remote / Worldwide
Specialties: SaaS integrations, REST APIs, Google Workspace automation, Serverless deployments.
