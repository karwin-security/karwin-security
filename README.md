<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img src="./assets/banner-light.svg" alt="Karwin — Systems Administration · Automation · Offensive Security" width="100%">
</picture>

<p align="center">
  <img src="https://img.shields.io/badge/IT_Systems-hospitality-000000?style=flat-square&labelColor=404040" alt="IT Systems">
  <img src="https://img.shields.io/badge/HTB_CPTS-in_progress-000000?style=flat-square&labelColor=404040&logo=hackthebox&logoColor=white" alt="HTB CPTS in progress">
  <img src="https://img.shields.io/badge/CFGS_ASIX-2nd_year-000000?style=flat-square&labelColor=404040" alt="CFGS ASIX">
  <img src="https://komarev.com/ghpvc/?username=karwin-security&label=profile+views&color=000000&style=flat-square" alt="Profile views">
</p>

IT systems professional based in Catalunya, Spain. I administer production infrastructure in the hospitality
sector — identity, endpoints, perimeter security and the automation around them — and I am building an
offensive security skill set to move into penetration testing and red team work.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/terminal-dark.svg">
  <img src="./assets/terminal-light.svg" alt="Terminal: whoami, role and focus areas" width="100%">
</picture>

<br><br>

## Selected work

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/card-incident-dark.svg">
        <img src="./assets/card-incident-light.svg" alt="IT Incident Workflow" width="100%">
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/card-server-dark.svg">
        <img src="./assets/card-server-light.svg" alt="Self-hosted n8n" width="100%">
      </picture>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/card-inventory-dark.svg">
        <img src="./assets/card-inventory-light.svg" alt="Network Inventory" width="100%">
      </picture>
    </td>
    <td width="50%">
      <a href="https://krwpulse.com">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/card-pipeline-dark.svg">
          <img src="./assets/card-pipeline-light.svg" alt="KRW Pulse" width="100%">
        </picture>
      </a>
    </td>
  </tr>
</table>

<details>
<summary><b>Architecture — IT incident workflow</b></summary>
<br>

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#0a0a0a", "primaryTextColor": "#fafafa", "primaryBorderColor": "#737373", "lineColor": "#737373", "fontFamily": "ui-monospace, SFMono-Regular, Menlo, monospace"}}}%%
flowchart LR
    A[Incident report] --> B[Power Automate]
    B --> C[AI Builder<br/>classification]
    C --> D[(SharePoint<br/>incident log)]
    C --> E[Teams<br/>responsible channel]
```

</details>

<details>
<summary><b>Architecture — Self-hosted n8n</b></summary>
<br>

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#0a0a0a", "primaryTextColor": "#fafafa", "primaryBorderColor": "#737373", "lineColor": "#737373", "fontFamily": "ui-monospace, SFMono-Regular, Menlo, monospace"}}}%%
flowchart LR
    U[Client] --> CF[Cloudflare<br/>Zero Trust]
    CF --> T[cloudflared<br/>tunnel]
    T --> N[n8n]
    N --> P[(PostgreSQL)]
    P --> BK[Encrypted<br/>backups]
```

</details>

<details>
<summary><b>Architecture — KRW Pulse pipeline</b></summary>
<br>

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#0a0a0a", "primaryTextColor": "#fafafa", "primaryBorderColor": "#737373", "lineColor": "#737373", "fontFamily": "ui-monospace, SFMono-Regular, Menlo, monospace"}}}%%
flowchart LR
    R[RSS feeds] --> N[n8n]
    N --> J[Jina AI<br/>extraction]
    J --> G[Gemini<br/>processing]
    G --> TG[Telegram]
    G --> M[Email]
    KV[(Cloudflare KV<br/>subscribers)] --> M
```

</details>

<br>

## Certification path

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/roadmap-dark.svg">
  <img src="./assets/roadmap-light.svg" alt="Certification path: CPTS in progress, then CRTP, CRTO and AWS Security Specialty" width="100%">
</picture>

<sub><b>Education</b> · Higher Vocational Diploma in Network Systems Administration (CFGS ASIX), in progress · Vocational Diploma in Microcomputer Systems and Networks (CFGM SMX)</sub>

<br><br>

## Stack

<details open>
<summary><b>Systems & infrastructure</b></summary>
<br>
<img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Windows_Server-000000?style=for-the-badge&logo=windows&logoColor=white">
<img src="https://img.shields.io/badge/Active_Directory-000000?style=for-the-badge&logo=microsoft&logoColor=white">
<img src="https://img.shields.io/badge/Microsoft_365-000000?style=for-the-badge&logo=microsoftoffice&logoColor=white">
<img src="https://img.shields.io/badge/SharePoint-000000?style=for-the-badge&logo=microsoftsharepoint&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=white">
</details>

<details open>
<summary><b>Network & security</b></summary>
<br>
<img src="https://img.shields.io/badge/Cloudflare_Zero_Trust-000000?style=for-the-badge&logo=cloudflare&logoColor=white">
<img src="https://img.shields.io/badge/WatchGuard_Firebox-000000?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/Burp_Suite-000000?style=for-the-badge&logo=burpsuite&logoColor=white">
<img src="https://img.shields.io/badge/Kali_Linux-000000?style=for-the-badge&logo=kalilinux&logoColor=white">
<img src="https://img.shields.io/badge/Hack_The_Box-000000?style=for-the-badge&logo=hackthebox&logoColor=white">
</details>

<details open>
<summary><b>Automation & development</b></summary>
<br>
<img src="https://img.shields.io/badge/n8n-000000?style=for-the-badge&logo=n8n&logoColor=white">
<img src="https://img.shields.io/badge/Power_Automate-000000?style=for-the-badge&logo=powerautomate&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=white">
<img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Claude_Code-000000?style=for-the-badge&logo=claude&logoColor=white">
</details>

<br>

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/karwin-security/karwin-security/output/snake-dark.svg">
  <img src="https://raw.githubusercontent.com/karwin-security/karwin-security/output/snake-light.svg" alt="Contribution graph animation" width="100%">
</picture>

<br>

<sub>All security testing is performed in lab environments or on platforms where I am explicitly authorized.</sub>
