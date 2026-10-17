# balaaj96.github.io
GitHub Pages portfolio site for Balaaj Ahmad Bhatti
# Technical Training Project Portfolio

A single-page portfolio for Balaaj Ahmad Bhatti, built for the Open Doors Scholarship application in Computer and Data Science. It presents three projects:

1. **Academic Nexus** (student portal and marks management system; Flask, Supabase)
2. **Water Area Calculator — Algorithm Visualization** (React, Flask)
3. **Balaaj Affiliate Electronics** (static product catalog and affiliate website)

The site is one self-contained HTML file. The styles, JavaScript and all three screenshots are built in. It uses no framework, backend, build step or external fonts.

## Files

```
portfolio.html   the whole website (rename to index.html for GitHub Pages)
README.md        this file
```

## Project links used on the site

| Project | Button | Link |
|---|---|---|
| Academic Nexus | Live Demo | https://student-portal-system--bhattipart96.replit.app/ |
| Academic Nexus | View Source Code | https://github.com/Balaaj96/Academic--Nexus-Student-portal |
| Water Area Calculator | View Source Code | https://github.com/Balaaj96/Find-waterArea |
| Balaaj Affiliate Electronics | Visit Website | https://balaajaffiliateelectronics.github.io/ |
| Portfolio | GitHub Profile | https://github.com/Balaaj96 |

The Water Area Calculator has no live demo because it is not currently published. The affiliate website has no source-code button because no repository URL has been supplied.

## How to edit the site

Open the HTML file in any text editor (Notepad, VS Code) and use Find (Ctrl+F).

- **Introduction text:** search for `I am interested in programming`.
- **Change a link:** search for the old URL, or for the project name, and edit the `href="..."` next to it.
- **GitHub profile URL:** search for `https://github.com/Balaaj96`. It appears twice, in the top section and in Contact / Links. Change both.
- **Add the PDF link:** search for `href="PDF_URL_PLACEHOLDER"` and replace only that one with your PDF's public URL, for example `href="https://example.com/portfolio.pdf"`. The name appears in other places too (a comment and the script that hides the link). Do not use "Replace All", or the link will stay hidden. Until you add the URL, the PDF link is hidden and a short note is shown instead.
- **Add the affiliate source-code button:** search for `SOURCE CODE BUTTON`. A commented-out example is right there. Copy it outside the comment and fill in your repository URL.
- **Replace a screenshot:** the images are stored as very long text starting with `data:image/png;base64,`. The easy way is to replace each image's `src="data:image/png;base64,..."` with `src="assets/your-file.png"` and put your PNG files in an `assets` folder next to the HTML file. Upload that folder to GitHub with the site. Alternatively, send the new screenshot back to Claude and ask for a rebuilt file.

## Publish with GitHub Pages

1. Go to github.com and click **New repository**. Name it (for example `portfolio`) and set it to **Public**.
2. Rename `portfolio.html` to `index.html`. GitHub Pages looks for that exact name.
3. In the new repository, click **uploading an existing file**, drag in `index.html` and `README.md`, then click **Commit changes**.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait one or two minutes. The site will appear at `https://Balaaj96.github.io/portfolio/` (using your repository name).

## Test locally

Double-click the HTML file. It opens in your browser and needs no server. Check that:

- all three screenshots appear and open larger when clicked, and Escape closes them;
- every button opens the right page in a new tab;
- the menu works when you make the window narrow.

## Accuracy notes

- The Academic Nexus text describes sessions, session cookies, JWT and Row Level Security as concepts you set out to learn. If your code verifiably implements JWT or RLS, you may say so.
- The site states that AI tools (Google Stitch, Claude AI, ChatGPT) assisted with design and code, and that for the Water Area Calculator you wrote the algorithm yourself.
- The Academic Nexus screenshot shows a sample user name and age. Make sure it is test data before publishing.
