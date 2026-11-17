# Visa readiness check: DRC to South Africa

A mobile-first, single-page checklist to help travelers from the Democratic Republic of the Congo prepare for a South Africa visa application. The page is plain HTML, CSS, and JavaScript with no dependencies, build step, or network requests.

## Run locally

From the repository directory, start a local static file server:

```powershell
python -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/) in a browser. You can also open `index.html` directly.

## What it does

- Checks travel dates and the passport validity buffer.
- Shows a purpose-specific document checklist and application timeline.
- Tracks checklist progress and saves trip answers and checked items in browser local storage.
- Shows submission guidance once all required applicable items are checked.
- Provides a Reset button to clear saved answers and checklist progress.

Study visas are not covered; the page directs study applicants to the South African Embassy in Kinshasa. The checklist is general information, not legal advice. Confirm current requirements with VFS before applying.
