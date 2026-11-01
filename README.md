# Awesome-Mobile-Agile-Project-Tracking

# Top Mobile Agile Project Tracking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Native Mobile Sprint Tracking, Offline Kanban & Self-Hosted Agile Backends*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Agile Project Tracking**. These tools enable product teams, scrum masters, and developers to manage sprints, update issues, and review boards directly from their phones—keeping ceremonies and daily standups accessible without a laptop.

**Examples** include Jira Mobile, Linear Mobile, Asana Mobile, Monday.com Mobile, ClickUp Mobile, GitHub Mobile, Trello Mobile, Shortcut Mobile, Wrike Mobile, and Basecamp Mobile (the category leaders).

**Open-source emphasis**: Mobile Agile Tracking is a domain where open-source tooling is **genuinely emerging but the mobile experience is often unofficial or early-stage**. The strongest native mobile options are **Taiga Mobile Nova** (an unofficial Android client for Taiga.io with full Kanban, sprint, and wiki access)  and **Vikunja's cross-platform app** (Android/iOS, though it is in **alpha pre-release** and explicitly warns against production use) . **Plane Mobile** is the official Flutter app for Plane, but the README states it is "still in its early days, not everything will be perfect yet" . The critical caveat: **Focalboard's standalone version has been unmaintained since June 2024**—Mattermost absorbed its functionality, so the mobile app is effectively frozen . **Leantime offers a mobile app** that works with self-hosted or cloud workspaces, but it is a companion for focus rather than a full agile tracker . **No open-source project matches the polish of Linear Mobile or Jira Mobile**—open-source apps are typically unofficial clients or early-stage official releases.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Jira Mobile](https://www.atlassian.com/software/jira)**  
  Atlassian's native mobile app; manage issues, update sprints, view boards, and collaborate on the go.

- **[Linear Mobile](https://linear.app/)**  
  Native mobile app for Linear's issue tracker; known for speed and a polished mobile experience.

- **[Asana Mobile](https://asana.com/)**  
  Native mobile project management; view timelines, update tasks, and collaborate on the go.

- **[Monday.com Mobile](https://monday.com/)**  
  Mobile access to monday.com's work OS; boards, dashboards, and updates on mobile.

- **[ClickUp Mobile](https://clickup.com/)**  
  Mobile access to ClickUp's all-in-one platform; tasks, docs, and goals on the go.

- **[GitHub Mobile](https://github.com/)**  
  Native mobile app for GitHub; manage issues, pull requests, and notifications from your phone.

- **[Trello Mobile](https://trello.com/)**  
  Native mobile kanban boards; cards, lists, and Power-Ups on iOS and Android.

- **[Shortcut Mobile](https://shortcut.com/)**  
  Mobile access to Shortcut's project management; stories, epics, and iterations on the go.

- **[Wrike Mobile](https://www.wrike.com/)**  
  Mobile access to Wrike's work management; tasks, timelines, and collaboration on mobile.

- **[Basecamp Mobile](https://basecamp.com/)**  
  Native mobile app for Basecamp's project management and team communication.

## Open-Source GitHub Projects

### Native Mobile Agile Clients (Taiga, Vikunja, Plane)

- **[Taiga Mobile Nova](https://fdroid.org/en/packages/com.grappim.taigamobile.fdroid/)**  
  An **unofficial Android client for Taiga.io** (open-source agile project management) . Features: **Dashboard** (view projects, working on items, watching items); **Projects** (browse and manage); **Kanban Board** with drag-and-drop cards; **Sprints** (track progress, manage backlogs); **User Stories** (create, edit, track); **Tasks** and **Issues**; **Epics**; and **Wiki** access . Built with Jetpack Compose and Material Design 3; requires Android 7.0+ . **Best for Android users already running Taiga** wanting a native mobile client—but it is **unofficial** and iOS is not supported .

- **[Vikunja Cross-Platform App](https://github.com/go-vikunja/app)**  
  A **cross-platform app for Vikunja** (the open-source, self-hostable to-do and project management app) . Vikunja supports **List, Gantt, Table, and Kanban views**; the app requires the latest stable Vikunja build . **Critical caveat**: the app is in **alpha pre-release**—the README explicitly warns "You must absolutely expect things to not work, and sometimes even break something in the backend. Using this app on important production backends is possible but discouraged" . **Best for Vikunja users wanting mobile access**—but not ready for production reliance .

- **[Plane Mobile](https://github.com/makeplane/plane-mobile)**  
  The **official Flutter mobile app for Plane** (open-source Jira/Linear alternative) . Features: **issue planning and tracking** with rich text editor and file uploads; **List, Kanban, and Calendar layouts**; **Cycles** (sprints) with burn-down charts; **Modules** for breaking down large projects . **Critical caveat**: the README states "Plane Mobile is still in its early days, not everything will be perfect yet, and hiccups may happen" . **Best for Plane users wanting an official mobile app**—but it is early-stage and not feature-complete .

### Mobile-Friendly Web Apps (No Native App)

- **[Scrum Agile Transformation Studio](https://github.com/alfredang/scrum)**  
  A **single-file, mobile-friendly collaborative Scrum studio** (HTML/CSS/JS + Firebase, MIT-style) . Features: **Product Vision, Roadmap, Backlog, Sprint Planning with Planning Poker, Sprint Backlog Kanban, Daily Scrum with timer, Sprint Execution with burndown, Sprint Review, Retrospective (4 formats), Agile Metrics, and Transformation roadmap** . **Mobile-first design**: bottom nav, FAB, touch drag-and-drop, responsive boards; **QR-code workspace joining** to scan and join from any device . **Critical caveat**: it is a **web app, not a native mobile app**—no offline mobile support beyond localStorage demo mode . **Best for small teams wanting a free, collaborative Scrum tool** accessible from mobile browsers—not a native agile tracker .

- **[Leantime Mobile](https://apkpure.com/leantime-tasks-focus/io.leantime.mobile)**  
  A **mobile companion for Leantime** (open-source project management) . Works with existing Cloud or self-hosted Leantime workspaces; designed as a "calm way to focus on what matters today" . The app does not create accounts—your data stays on your Leantime server . **Best for Leantime users wanting a focused mobile companion**—but it is not a full agile tracking app with sprint boards or backlog management .

### Unmaintained / Caution

- **[Focalboard](https://apps.apple.com/de/app/focalboard/id1556908618)**  
  **CAUTION**: Focalboard's standalone version has been **unmaintained since June 2024**—Mattermost absorbed its functionality into Mattermost Boards, and the standalone Docker image is effectively abandoned . The iOS/Mac app exists but **will receive no patches or security fixes** . **Best for Mattermost users** (use the plugin, not standalone)—not for new deployments .

**Frameworks for building custom systems**: For **Android users on Taiga**, Taiga Mobile Nova provides the most complete native client . For **Vikunja users**, the cross-platform app offers mobile access but is alpha . For **Plane users**, Plane Mobile is official but early-stage . For **web-based Scrum on mobile**, Scrum Agile Transformation Studio provides a mobile-first web app . **Avoid Focalboard** for new projects—it is unmaintained . **No open-source project matches the polish of Linear Mobile or Jira Mobile**—open-source apps are typically unofficial clients or early-stage official releases, and the native mobile experience remains a commercial advantage.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile agile tracking platforms handling project and sprint data must comply with organizational data governance policies; **self-hosted solutions place full responsibility for security patches, backups, and mobile sync infrastructure on the operator**.
- **Open-source mobile agile tracking is early-stage and fragmented**—**Taiga Mobile Nova is unofficial but functional** , **Vikunja's app is alpha** with explicit production warnings , and **Plane Mobile is official but early-stage** . **Focalboard is unmaintained since June 2024**—do not deploy for new projects . **No open-source project matches the polish of Linear Mobile or Jira Mobile**—choose based on whether you prioritize native Android (Taiga), cross-platform (Vikunja, Plane), or mobile web (Scrum Studio).
- Verify license terms for commercial use; Taiga Mobile Nova is an unofficial F-Droid client (check Taiga's license), Vikunja's app is open-source (check repository), and Plane Mobile is part of the Plane project (AGPL-3.0 for the core) .

---

**Made for scrum masters, product owners, and developers choosing their on-the-go agile tracking stack.**  
Let's make mobile agile tracking more open, but with clear eyes about the unofficial-client and alpha-stage gaps that separate open-source from the polished commercial apps.
