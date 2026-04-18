# career-ops

A lightweight, agentic-driven career operations system for tracking, managing, and automating job applications and career development.

## The Problem
Managing multiple job applications, networking efforts, and professional development tracking is complex. Manual tracking tools are inefficient and lack the necessary automation for modern career management.

## The Solution
`career-ops` provides a streamlined, automation-first system designed to manage the entire application pipeline, from discovery to offer. It leverages agentic workflows to track progress, normalize data, and provide intelligent insights.

**Key Features:**
- **Agentic Pipeline Tracking:** Automated status normalization and progress tracking.
- **Data Contract Driven:** Structured data management for job applications and company research.
- **Cross-Platform Compatibility:** Designed to be lightweight and portable.
- **Intelligent Scanning:** Automated job description analysis and pattern matching.
- **Observability:** Built-in dashboarding and reporting for career trajectory analysis.

---

## Tech Stack
- **TypeScript & JavaScript (MJS)** for core logic and automation.
- **Go** for the performance-critical dashboarding backend.
- **Vite** for the dashboard frontend.
- **Supabase/Git-based storage** for flexible data management.

---

## Project Structure
```
├── batch/           # Batch processing scripts and URL tracking
├── config/          # Configuration profiles
├── dashboard/       # Go-based LLMOps-lite dashboard
├── data/            # Local data storage
├── docs/            # Architecture and setup documentation
├── modes/           # Automated operational modes (apply, scan, track, etc.)
├── reports/         # Generated job application reports
├── templates/       # CV and portal templates
└── tmp/             # Temporary processing directory
```

---

## Quick Start
1. Clone the repository.
2. Initialize environment:
   ```bash
   source .init
   ```
3. Run maintenance/updates:
   ```bash
   node update-system.mjs
   ```

---

## License
MIT
