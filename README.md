## Setup
1. Initialise Svelte app using template
```sh
npx degit sveltejs/template svelte-on-github-pages
```
2. Add the GitHub action and deployment script (see: `scripts/ghPagesDeploy.js` and `.github/workflows/gh-pages-deploy.yaml`)
3. Commit and push the changes.
4. Ensure the action runs with no issue, then go into your repository's settings and enable pages for the newly created `gh-pages` branch.
5. __Done.__ Pushes to the `main` branch will now trigger a rebuild of your pages site.

If you're having trouble, refer to this repository's code.
