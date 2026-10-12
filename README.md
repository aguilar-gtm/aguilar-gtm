### Alejandro Aguilar Alarcon · GTM Engineer · Lima, Peru (UTC-5)

I build the systems behind outbound: signal monitors, lead scoring pipelines, enrichment and LLM-assisted workflows. I write them in Python, Node.js and Claude Code. Before I built them, I ran them: a 2,500-inbox operation reaching 260,000+ prospects a month across 13+ B2B accounts. Spanish and English, both native.

**Open to GTM Engineer roles, remote from LatAm.** [LinkedIn](https://www.linkedin.com/in/alejandro-aguilar-alarcon-548096277)

---

#### Public builds

| Repo | What it does | Stack |
|---|---|---|
| [gtm-signal-engine](https://github.com/aguilar-gtm/gtm-signal-engine) | Reads 12 public sources every morning (SEC Form D, funding news, ATS boards, job APIs), gates each record on eligibility and pay, scores it against a profile and writes a ranked page. About 1,600 records read per run. | Python stdlib, Task Scheduler |
| [localflow](https://github.com/aguilar-gtm/localflow) | Push-to-talk dictation into any Windows app. Whisper and a local LLM run on your machine, so the audio never leaves it. Packaged so a team can use it. | Python, faster-whisper, Ollama |
| [second-brain-template](https://github.com/aguilar-gtm/second-brain-template) | Persistent memory for Claude Code: a one-page state file, a session log and six slash commands. Setup takes 10 minutes and costs $0. | Claude Code, Markdown |

#### Work I can't publish (employer or client code)

- **Canaria (crypto compliance):** signal-based outbound in Python and Node.js. Monitors watch regulatory filings and hiring signals, and the strongest ones arrive hourly with draft emails ready for review. Also built Smartlead sending with SPF/DKIM/DMARC, a lead-scoring pipeline and a pre-send check that catches unapproved claims and do-not-contact domains.
- **Xolvea (xolvea.com, with a partner):** a lead-generation platform for Peru. It builds company lists from the public tax registry, finds each company's team inbox on its own website, and gives each client a console generated from that data.
- **OutlierGTM:** outbound for 13+ global B2B accounts on 2,500+ inboxes and 350+ domains, with bounces under 2.5%. Automated parts of the operation with n8n and Clay.

#### Stack

Python · Node.js · Playwright · REST APIs · webhooks · Git · Claude Code · n8n · Make · Zapier · Clay · Apollo · HubSpot · Salesforce · Smartlead · Instantly · SPF/DKIM/DMARC
