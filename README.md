# Solve & Bloom Co — blog site

A simple static blog: one homepage grid (`index.html`) linking to individual
product posts (`posts/*.html`). No build tools, no server — just files.

## Put it online with GitHub Pages (free)

1. Create a free GitHub account at github.com if you don't have one.
2. Create a new repository, e.g. `solve-and-bloom-blog`. Public, no README/license needed (you already have this one).
3. Upload every file in this folder — `index.html`, `style.css`, and the `posts/` folder — keeping the same structure. (On github.com: "Add file" → "Upload files", drag the whole folder in.)
4. In the repo, go to Settings → Pages.
5. Under "Build and deployment", set Source to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
6. Wait a minute, then your site is live at `https://YOUR-USERNAME.github.io/solve-and-bloom-blog/`.

You can later point a custom domain at this if you buy one, under the same Pages settings.

## Adding a new product post

1. Duplicate `posts/post-template.html` and rename it, e.g. `posts/desk-organizer.html`.
2. Open it and replace:
   - the `<title>` and page `<h1>`
   - the product photo placeholder (swap in `<img src="..." alt="...">`)
   - the price
   - the Amazon link in the buy button — this must be your **tagged Associates link** (from SiteStripe once you're approved), not a plain amazon.com link
   - the body paragraphs
3. Open `index.html`, duplicate one `<a class="card">...</a>` block, and update its `href` to point to your new post file, plus its photo, title, excerpt, and price.
4. Upload the changed files back to GitHub (or use GitHub's web editor) — Pages redeploys automatically in under a minute.

## Before you post real product links

- You need to be accepted into Amazon Associates first — this site alone, once live, gives you a "website" to list on your application.
- Every post already includes the required disclosure language near the buy button — keep it on every post, don't remove it.
- Link your Pinterest pins to these blog posts (instead of straight to Amazon) if you want Pinterest traffic to land somewhere with more context — or link pins directly to Amazon if you prefer a simpler funnel. Either works with Associates; just keep disclosure visible in both places.
