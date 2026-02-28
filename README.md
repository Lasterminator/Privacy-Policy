# Privacy Policy (site)

Privacy policy pages for apps and games, hosted on GitHub Pages. Each app has its own page so you can give store consoles (e.g. Google Play) a direct URL.

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
     `https://<your-username>.github.io/<repo-name>/`  
     Example: `https://lasterminator.github.io/Privacy-Policy/`
   - Infinite Labyrinth (for Play Console):  
     `https://<your-username>.github.io/<repo-name>/infinite-labyrinth.html`

In **Google Play Console** → your app → **Policy** → **Privacy policy**, paste the **app-specific** URL (e.g. the `infinite-labyrinth.html` link), not the hub.

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
