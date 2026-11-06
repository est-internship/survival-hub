# EST Survival Hub

View-only website with first-internship guidance for EST students: roadmap, safety basics, message templates, scenario flashcards and a quick recap.

Files:
- `index.html` is the website (layout and design).
- `content.json` is **all the written content**. Edit this file to change the site.
- `.nojekyll` is an empty helper file for GitHub Pages. Keep it.

## Put it online with GitHub Pages (free)

1. Create a new **public** repository on GitHub, for example `survival-hub`.
2. Upload all four files (`index.html`, `content.json`, `.nojekyll`, `README.md`) and click **Commit changes**.
3. Open **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After 1–2 minutes the site is at `https://YOUR-USERNAME.github.io/survival-hub/`.

## Edit the content

1. Open `content.json` on GitHub and click the pencil icon.
2. Change the text between the quotation marks. To add an item, copy a whole `{ ... }` block (and put a comma between blocks). To remove one, delete its block.
3. In message templates, text in [square brackets] shows as a fill-in-the-blank. A line break inside a message is written as `\n`.
4. Click **Commit changes**. The site updates in about a minute (refresh the page to see it).

Tip: a missing comma or quotation mark breaks the whole file. If the site shows the old text after you edit, paste your JSON into any online JSON validator to find the mistake. If `content.json` is broken or missing, the site falls back to the built-in text inside `index.html`.

## Optional

- Paste your Internship Hub link into `hubUrl` near the top of `index.html` to show a "Back to Internship Hub" button on the home page.
- The "Download .txt" buttons download directly when the site is hosted on GitHub Pages.
