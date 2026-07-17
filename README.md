# Global Cybersecurity Weekly

> Curated open-source threat intelligence on the most significant cybersecurity events shaping the global landscape. Published weekly.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue)](https://yourusername.github.io/global-cybersecurity-weekly/)

---

## About

**Global Cybersecurity Weekly** is an independent, open-source threat intelligence digest compiled from open-source intelligence (OSINT), vendor threat research, government advisories, and industry reporting.

Each issue covers the most significant cybersecurity events of the preceding seven days, with:

- **Threat Analysis** — Deep dives into active campaigns, vulnerabilities, and attacker TTPs
- **Strategic Context** — Big-picture trends shaping the threat landscape
- **Actionable Recommendations** — Prioritized guidance for security leaders and practitioners
- **Vendor & Government Intel** — Synthesis of CISA KEV, vendor advisories, and law enforcement operations

---

## Latest Issue

| Issue | Date | Title | Key Topics |
|-------|------|-------|------------|
| **29** | July 10–17, 2026 | [The Week That Changed Everything](newsletter-2026-07-17.html) | Autonomous AI ransomware (JADEPUFFER), 2-hour exploit windows, BYOVD attacks, supply chain compromises, Operation First Light |

---

## Repository Structure

```
global-cybersecurity-weekly/
├── index.html                  # Archive landing page
├── newsletter-2026-07-17.html  # Individual issue (full article)
├── README.md                   # This file
└── assets/                     # (Optional) Images, diagrams, etc.
```

### Naming Convention

- **Issue pages:** `newsletter-YYYY-MM-DD.html`
- **Issue numbers:** Incremental, starting from Issue 1
- **Date range:** Each issue covers events from the preceding 7 days (Friday → Friday)

---

## Quick Start

### View Locally

Simply open `index.html` in any modern web browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose the `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/global-cybersecurity-weekly/`

---

## Adding a New Issue

1. Create a new HTML file following the naming convention:
   ```
   newsletter-YYYY-MM-DD.html
   ```

2. Use the existing issue template (copy from `newsletter-2026-07-17.html`) and update:
   - Issue number and date range
   - Title and subtitle
   - All section content
   - Table of contents links
   - Hero metadata

3. Add the new issue card to `index.html` in the "Latest Issues" section:
   ```html
   <article class="issue-card">
       <a href="newsletter-YYYY-MM-DD.html">
           <div class="issue-header">
               <span class="issue-number">Issue N</span>
               <span class="issue-date">Date Range</span>
           </div>
           <h3 class="issue-title">Issue Title</h3>
           <p class="issue-summary">Brief summary...</p>
           <div class="issue-tags">
               <span class="tag tag-critical">Topic</span>
           </div>
       </a>
   </article>
   ```

4. Commit and push — GitHub Pages will auto-deploy.

---

## Content Guidelines

### Sourcing

All content is compiled from publicly available sources, including:

- **Government advisories:** CISA KEV, FBI alerts, NSA/CISA joint advisories
- **Vendor research:** Check Point, Sophos, Sysdig, Fortinet, Microsoft Security Response Center
- **Industry reporting:** BleepingComputer, The Hacker News, SecurityWeek, Dark Reading, Cybersecurity Dive
- **Threat intelligence:** KEVIntel, Recorded Future, Mandiant, CrowdStrike
- **Academic & institutional:** World Economic Forum Global Cybersecurity Outlook, ENISA Threat Landscape

### Attribution

- Facts and claims are attributed to their original sources where possible
- Direct quotes are marked and sourced
- CVE numbers link to official advisories
- No proprietary or classified information is included

### Editorial Standards

- **Accuracy:** Every CVE, date, and statistic is verified against primary sources
- **Context:** Individual events are placed within broader strategic trends
- **Actionability:** Every issue includes prioritized recommendations for security leaders
- **Neutrality:** Analysis is vendor-agnostic and politically neutral

---

## Technology

- **Pure HTML/CSS** — No JavaScript frameworks, no build step, no dependencies
- **GitHub Pages native** — Works out of the box with zero configuration
- **Responsive design** — Optimized for mobile, tablet, and desktop
- **Dark theme** — Easy on the eyes for extended reading
- **Semantic HTML** — Accessible and SEO-friendly

---

## Contributing

Contributions are welcome! Here are ways you can help:

### Report an Error

If you spot a factual error, incorrect CVE, broken link, or typo:

1. Open an [Issue](../../issues/new)
2. Include the issue number, section, and correction
3. Cite the primary source if applicable

### Suggest a Topic

If you believe a significant event was missed or under-covered:

1. Open an [Issue](../../issues/new) with the label `topic-suggestion`
2. Provide the event details, date, and primary source
3. Explain why it warrants coverage

### Submit a Pull Request

For direct contributions (typo fixes, formatting improvements, new issues):

1. Fork the repository
2. Create a feature branch: `git checkout -b fix/typo-or-feature`
3. Make your changes
4. Test locally by opening the HTML files in a browser
5. Submit a pull request with a clear description

---

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

---

## Disclaimer

The content in this publication is provided for **informational and educational purposes only**. It does not constitute professional security advice. Readers should conduct their own risk assessments and consult qualified security professionals before making operational decisions based on this content.

The authors and contributors are not responsible for any damages or losses arising from the use of the information contained herein.

---

## Contact

- **Issues & Suggestions:** [GitHub Issues](../../issues)
- **General Inquiries:** Open a discussion in [GitHub Discussions](../../discussions)

---

<p align="center">
  <sub>Built with &#128274; for the security community.</sub><br>
  <sub>&copy; 2026 Global Cybersecurity Weekly</sub>
</p>
