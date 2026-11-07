# Prof. Lalit Kumar — academic profile website

A lightweight, responsive, single-page academic profile. Built with plain HTML, CSS and JavaScript: no framework, build command, database or paid service required.

## Preview locally
Open `index.html` in a browser, or run a local static server from this folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to Vercel through GitHub
1. Create a new GitHub repository, e.g. `lalit-kumar-academic-profile`.
2. Upload all files in this folder to the repository root (not the containing ZIP folder).
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Framework preset: **Other**. Build command: leave empty. Output directory: leave as `.` / default. No environment variables are needed.
6. Deploy. Future pushes to the connected branch will redeploy automatically.

## Important content checks before publishing
The current draft uses only the basic information visible on the previous public site. Please verify the professor's preferred title, credentials, office number, department and institutional affiliation before publishing. Add verified biography, course names, publication list, project details, facilities and official email. The ORCID link currently points to the ORCID homepage because a specific profile URL was not confirmed.

## Edit content
Open `index.html` in VS Code. Search for the section IDs `about`, `research`, `teaching`, `projects`, `facilities`, and `contact`. Update the text while keeping each `id` unchanged so the menu continues to scroll to the correct section.

## Design behavior
- One continuous page with smooth in-page navigation.
- No popups, modals or detail overlays.
- Minimal typography, restrained colors and no decorative icon library.
- Responsive navigation that scrolls horizontally on narrow screens.
