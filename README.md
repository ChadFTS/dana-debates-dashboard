# Dana Debates Dashboard

Task tracking dashboard for Dana Debates / Explain Yourself Media deliverables.

**Live:** https://dana-debates-dashboard.vercel.app

## Categories

- **Authenticity Edge Funnel** — Lead magnet, landing pages, PDFs
- **Email Sequences** — Nurture emails, follow-ups
- **YouTube Episodes** — Titles, descriptions, tags, thumbnails
- **Graphics & Assets** — Visual assets, thumbnails, social graphics

## Workflow

1. Create deliverable
2. Upload assets to Google Drive
3. Add task entry to `index.html` with links
4. Commit + push → auto-deploys to Vercel

## Task Format

```html
<li class="task-item">
    <div class="checkbox"></div>
    <div class="task-content">
        <div class="task-title">Task Name</div>
        <div class="task-meta">
            <span class="status ready">Ready</span> • 
            <a href="#">Asset</a> • 
            <a href="#">Copy</a>
        </div>
    </div>
</li>
```

## Status Labels

- `ready` — Complete, ready for use
- `draft` — In progress
- `pending` — Needs review

---

*Maintained by Kiki 🦊*
