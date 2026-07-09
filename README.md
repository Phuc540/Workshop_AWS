# AWS Internship Report Site

A personal internship report website built with **Hugo** and the **FCJ Workshop template**, documenting my internship experience at **Amazon Web Services Vietnam Co., Ltd.** The site is automatically deployed to **GitHub Pages** via GitHub Actions CI/CD.

🌐 **Live Site:** [https://phucle76765.github.io/aws-internship-report-site/](https://phucle76765.github.io/aws-internship-report-site/)

---

## 👤 Author

| Field | Info |
|---|---|
| **Full Name** | Le Minh Phuc |
| **Email** | phucle76765@gmail.com |
| **Phone** | 0938747802 |
| **University** | Ho Chi Minh City University of Technology |
| **Major** | Information Technology |
| **Class** | 22DTHJA2 |
| **Company** | Amazon Web Services Vietnam Co., Ltd. |
| **Position** | Frontend Developer |
| **Project** | GreenLens Kids |
| **Duration** | 18/04/2026 – 10/07/2026 |

---

## 🛠️ Tech Stack

| Tool | Version / Details |
|---|---|
| **Static Site Generator** | [Hugo Extended](https://gohugo.io/) |
| **Theme** | [hugo-theme-learn](https://github.com/matcornic/hugo-theme-learn) / FCJ Workshop template |
| **Hosting** | GitHub Pages |
| **CI/CD** | GitHub Actions |
| **Languages** | English 🇺🇸 / Vietnamese 🇻🇳 (bilingual) |
| **Content Format** | Markdown |

---

## 📁 Project Structure

```txt
aws-internship-report-site/
│
├── .github/
│   └── workflows/
│       └── hugo.yml              # CI/CD: auto-build & deploy to GitHub Pages
│
├── archetypes/
│   └── default.md                # Default front-matter template for new pages
│
├── content/                      # All site content (bilingual: .md & .vi.md)
│   ├── _index.md                 # Homepage (English)
│   ├── _index.vi.md              # Homepage (Vietnamese)
│   │
│   ├── 1-Worklog/                # Weekly activity log (11 weeks)
│   │   ├── _index.md             # Worklog overview (English)
│   │   ├── _index.vi.md          # Worklog overview (Vietnamese)
│   │   ├── 1.1-Week1/
│   │   ├── 1.2-Week2/
│   │   ├── 1.3-Week3/
│   │   ├── 1.4-Week4/
│   │   ├── 1.5-Week5/
│   │   ├── 1.6-Week6/
│   │   ├── 1.7-Week7/
│   │   ├── 1.8-Week8/
│   │   ├── 1.9-Week9/
│   │   ├── 1.10-Week10/
│   │   └── 1.11-Week11/
│   │
│   ├── 2-Proposal/               # Internship proposal / project plan
│   │
│   ├── 3-BlogsTranslated/        # Translated AWS blogs
│   │   ├── 3.1-Blog1/
│   │   ├── 3.2-Blog2/
│   │   ├── 3.3-Blog3/
│   │   ├── 3.4-Blog4/
│   │   ├── 3.5-Blog5/
│   │   └── 3.6-Blog6/
│   │
│   ├── 4-EventParticipated/      # Events attended during internship
│   │   ├── _index.md             # Events overview (English)
│   │   ├── _index.vi.md          # Events overview (Vietnamese)
│   │   ├── 4.1-Event1/           # Weekend Knowledge Sharing Session
│   │   └── 4.2-Event2/           # FCAJ Meetup
│   │
│   ├── 5-Workshop/               # Technical workshop documentation
│   │   ├── 5.1-Workshop-overview/
│   │   ├── 5.2-Prerequiste/
│   │   ├── 5.3-S3-vpc/
│   │   ├── 5.4-S3-onprem/
│   │   ├── 5.5-Policy/
│   │   └── 5.6-Cleanup/
│   │
│   ├── 6-Self-evaluation/        # Intern self-assessment criteria table
│   └── 7-Feedback/               # Sharing and feedback section
│
├── layouts/
│   ├── partials/
│   │   ├── custom-footer.html    # Custom footer override
│   │   ├── logo.html             # Custom logo partial
│   │   └── menu-footer.html      # Menu footer partial
│   └── shortcodes/
│       ├── ghcontributors.html   # GitHub contributors shortcode
│       ├── tab.html              # Tab shortcode
│       └── tabs.html             # Tabs container shortcode
│
├── static/
│   ├── AWS_Logo.svg              # AWS logo asset
│   ├── css/
│   │   ├── theme-mine.css        # Custom theme CSS
│   │   └── theme-workshop.css    # Workshop theme CSS variant
│   ├── fonts/                    # Custom fonts
│   └── images/
│       ├── Avatar.JPG            # Author profile picture
│       ├── avatar.png            # Alternative profile picture
│       ├── favicon.png           # Site favicon
│       ├── favicon-16x16.png
│       ├── 2-Proposal/           # Images for Proposal section
│       ├── 4-EventParticipated/  # Images for Events section
│       └── 5-Workshop/           # Images for Workshop section
│
├── themes/
│   └── hugo-theme-learn/         # Git submodule: FCJ Learn theme
│
├── config.toml                   # Main Hugo site configuration
├── .gitmodules                   # Git submodule reference (theme)
├── .gitignore                    # Ignores public/, logs, editor files
└── README.md                     # This file
```

---

## 📋 Report Contents

The site is organized into 7 main sections:

| # | Section | Description |
|---|---|---|
| 1 | **Worklog** | Weekly activity logs covering 11 weeks of internship |
| 2 | **Proposal** | Internship plan and project proposal |
| 3 | **Translated Blogs** | AWS-related blogs translated between English and Vietnamese |
| 4 | **Events Participated** | Events and meetups attended during the internship period |
| 5 | **Workshop** | Step-by-step technical lab documentation |
| 6 | **Self-evaluation** | Self-assessment across professional and technical criteria |
| 7 | **Sharing & Feedback** | Personal reflections, lessons learned, and feedback |

---

## 🗓️ Worklog Summary

The worklog section summarizes my internship progress over 11 weeks. During this period, I learned AWS cloud fundamentals, practiced with AWS Skill Builder labs, and applied the knowledge to the **GreenLens Kids** project.

| Week | Main Focus |
|---|---|
| **Week 1** | Getting Started with AWS: Accounts, Console & CLI |
| **Week 2** | Core AWS Services in Practice: EC2, S3, IAM, VPC & CloudWatch |
| **Week 3** | Hands-on AWS & Kickstarting GreenLens Kids |
| **Week 4** | AWS Skill Builder Labs & Project Foundation Development |
| **Week 5** | Advanced AWS Architecture & Project Structure Setup |
| **Week 6** | Security Deep Dive & Initial UI / Backend Development |
| **Week 7** | Architecture Review & Core API Development |
| **Week 8** | Full Integration: Backend, Frontend & AI Camera Feature |
| **Week 9** | Mini Game System: API Completion & Frontend Integration |
| **Week 10** | Code Refactoring, Admin Dashboard & Personal Profile Page |
| **Week 11** | Final Polish, GitHub Pages Deployment & Project Wrap-up |

---

## 🧩 Project Contribution: GreenLens Kids

During the internship, I participated in the **GreenLens Kids** project as a **Frontend Developer**.

My main responsibilities included:

- Designing and improving UI screens using **Figma**
- Developing the **Character Creation** screen for children
- Integrating the **Child Profile Creation API**
- Building and improving the **AI Camera Result** interface
- Integrating mascot voice guidance
- Designing and integrating the **Daily Streak UI**
- Working with API responses, loading states, error handling, and client-side data storage
- Adjusting UI/UX for the **GreenLens Admin Dashboard**
- Testing user flows and fixing frontend issues based on feedback

Through these tasks, I improved my frontend development skills, UI/UX thinking, API integration ability, teamwork, and practical understanding of product development.

---

## 🎤 Events Participated

During the internship, I participated in two FCAJ community events:

| Event | Date | Main Topics |
|---|---|---|
| **Weekend Knowledge Sharing Session** | 09/05/2026 | Continuous learning, AI-assisted development, Prompt Engineering, career preparation, BMAD Method |
| **FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture** | 13/06/2026 | DevOps, scalable AWS architecture, AWS community journey, Data Analytics, MNC working culture |

These events helped me gain broader perspectives on the IT industry, career development, cloud computing, DevOps, AI, and professional working culture.

---

## 🔬 Workshop

The workshop section documents a hands-on AWS technical lab. It includes the preparation steps, service configuration, testing process, policy configuration, and cleanup steps.

Main topics covered in the workshop include:

- Preparing the required AWS environment
- Configuring AWS services for the workshop scenario
- Testing the connection and system behavior
- Applying access policies and security configurations
- Cleaning up AWS resources after finishing the lab

This section helped me understand how AWS services can be configured and tested in a practical lab environment.

---

## 🚀 Getting Started (Local Development)

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/)
- Git

### Clone & Run

```bash
# Clone with submodules because the theme is included as a Git submodule
git clone --recurse-submodules https://github.com/phucle76765/aws-internship-report-site.git
cd aws-internship-report-site

# Start local development server
hugo server -D
```

The site will be available at:

```txt
http://localhost:1313/aws-internship-report-site/
```

> If you already cloned without `--recurse-submodules`, run:
>
> ```bash
> git submodule update --init --recursive
> ```

---

## ⚙️ Configuration

The main configuration is in [`config.toml`](./config.toml):

- **`baseURL`** – Set to the GitHub Pages URL
- **`theme`** – `hugo-theme-learn` / FCJ Workshop template
- **`themeVariant`** – Custom AWS-styled workshop theme
- **`defaultContentLanguage`** – `en` as the default language
- **Multilingual** – Configured for English and Vietnamese
- **Menu shortcuts** – Links to GitHub repository and AWS FCJ Study Group

---

## 🔄 CI/CD Deployment

Deployments are automated via **GitHub Actions** (`.github/workflows/hugo.yml`):

1. **Trigger:** Push to the `main` branch or manual `workflow_dispatch`
2. **Build job:**
   - Checks out source code with submodules
   - Installs Hugo Extended
   - Builds the site with Hugo
   - Uploads the build artifact
3. **Deploy job:**
   - Deploys the built artifact to GitHub Pages

---

## 🌏 Multilingual Support

All main content pages are available in both **English** and **Vietnamese**:

- English pages: `_index.md`
- Vietnamese pages: `_index.vi.md`

Language switching is available in the site navigation.

---

## 🔗 Links

- 📁 [GitHub Repository](https://github.com/phucle76765/aws-internship-report-site)
- 🌐 [Live Site](https://phucle76765.github.io/aws-internship-report-site/)
- 👥 [AWS FCJ Study Group](https://www.facebook.com/groups/awsstudygroupfcj/)
- 🎨 [Hugo Theme Learn](https://github.com/matcornic/hugo-theme-learn)