# PBC Mens Squad Training — Website (Jekyll)

This repository is a simple Jekyll site for the Pengwern Boat Club Mens Squad.

Quick summary
- Sessions are stored in `_sessions/` as Markdown files.
- Each session file has an `attendees` YAML array admins can edit via the GitHub web UI.
- Session plans and member documents live in `assets/` (upload PDFs to `assets/plans/` or `assets/docs/`).
- The site is configured for GitHub Pages.

Admin tasks
- Add a session: create a new file in `_sessions/` following the example.
- Upload session plan: add file to `assets/plans/` and set `plan:` in the session front matter.
- Mark attendees: open the session Markdown file in the GitHub web editor and edit the `attendees:` list.
- Enable GitHub Pages: set Pages to build from `main` branch (root). See instructions below.

Local preview
- Install Ruby + Bundler and run:
  ```
  bundle install
  bundle exec jekyll serve
  ```
- Then open http://localhost:4000

GitHub Pages notes
- Repository name: `PBC-Mens-Squad-Training`
- After I push the files I can help with enabling Pages from the repo settings, or you can enable it yourself (Settings → Pages → main branch / root).

If you want me to push these files to `alexh1609/PBC-Mens-Squad-Training` and enable Pages, confirm and I’ll create the repo and push.