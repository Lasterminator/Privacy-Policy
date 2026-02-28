# Privacy Policy (site)

Privacy policy pages for apps and games, hosted on GitHub Pages. Each app has its own page so you can give store consoles (e.g. Google Play) a direct URL.

## One-time publish

Do this once to put the site on GitHub and turn on Pages:

1. **Log in to GitHub CLI** (if you use it):
   ```bash
   gh auth login
   ```
   Then create the repo and push:
   ```bash
   cd "/Users/subhash/Documents/GitHub/Privacy Policy"
   gh repo create Lasterminator/Privacy-Policy --public --source=. --push
   ```
   Skip to step 3.

2. **Or create the repo on GitHub manually**
   - Go to https://github.com/new
   - Repository name: `Privacy-Policy`
   - Owner: `Lasterminator`
   - Public, do **not** add a README or .gitignore (repo should be empty)
   - Create repository  
   Then push from this folder:
   ```bash
   cd "/Users/subhash/Documents/GitHub/Privacy Policy"
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - On GitHub open **Lasterminator/Privacy-Policy** → **Settings** → **Pages**
   - Under **Source** choose **Deploy from a branch**
   - **Branch:** `main`, **Folder:** `/ (root)` → Save

4. **Use your URLs**
   - Hub: `https://lasterminator.github.io/Privacy-Policy/`
   - Infinite Labyrinth – Privacy policy (Play Console): `https://lasterminator.github.io/Privacy-Policy/infinite-labyrinth.html`
   - Infinite Labyrinth – Data deletion (Play Console “Delete account URL”): `https://lasterminator.github.io/Privacy-Policy/infinite-labyrinth-deletion.html`

## Publish on GitHub Pages

1. **Push this repo to GitHub**  
   Create a repo (e.g. `Privacy-Policy` or `privacy-policy`) and push this folder.

2. **Turn on GitHub Pages**
   - Open the repo on GitHub → **Settings** → **Pages**.
   - Under **Source**, choose **Deploy from a branch**.
   - **Branch:** `main` (or `master`), **Folder:** `/ (root)`.
   - Save. GitHub will build and serve the site.

3. **Your URLs**
   - Hub (list of all apps):  
     `https://lasterminator.github.io/Privacy-Policy/`
   - Infinite Labyrinth – Privacy policy:  
     `https://lasterminator.github.io/Privacy-Policy/infinite-labyrinth.html`
   - Infinite Labyrinth – Data deletion (Play “Delete account URL”):  
     `https://lasterminator.github.io/Privacy-Policy/infinite-labyrinth-deletion.html`

In **Google Play Console** → your app → **Policy** → **Privacy policy**, use the privacy policy URL. For **Delete account URL**, use the data deletion URL.

## Adding a new app or game

1. **Create a new HTML file**  
   Copy `infinite-labyrinth.html` and rename it (e.g. `my-new-game.html`). Use lowercase and hyphens in the filename.

2. **Edit the content**  
   Replace the app name, effective date, and policy text. Keep the same structure (back link, sections, contact email).

3. **Add a link on the hub**  
   In `index.html`, add a new list item in the `<ul class="app-list">`:
   ```html
   <li><a href="my-new-game.html">My New Game</a></li>
   ```

4. **Use the new URL in stores**  
   For the new app, use:  
   `https://<your-username>.github.io/<repo-name>/my-new-game.html`

## Contact

subhash8111999@gmail.com
