# Lisa-Anne Okolie — Portfolio

## Put it online (GitHub Pages)
1. On github.com create a **public** repo, e.g. `portfolio`.
2. Upload everything in this folder (index.html, data.json, .nojekyll, the assets folder).
3. Repo **Settings > Pages**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. Save.
4. Your site appears at `https://YOUR-USERNAME.github.io/portfolio/` after about a minute.
   Certificate wall: add `#certificates` to that link..

## Manage content (admin)
1. GitHub > Settings > Developer settings > Personal access tokens > **Fine-grained tokens** > Generate.
   Repository access: *Only select repositories* > your portfolio repo. Permission: **Contents: Read and write**. Set an expiry.
2. Open your site, go to `YOUR-SITE-LINK/#admin` (there is no Admin link on the page), enter `username/portfolio` and the token.
3. A **Manage portfolio** button appears: add or edit projects, certificates, experience, CV, links and photo.
   Each save is a commit; the live site updates about a minute later.
Token is stored only in your browser. Use it on your own device and click Sign out when done.
