# CMPM 121 Section Activity starter

## Changes made

6. Replace this README with a short description of **your** project and what you changed. Keep useful setup instructions if you like.

I changed the button counter to increment once per click to demonstrate how many times the button was clicked.

The project uses [Vite 8.3.1](https://vite.dev/) for local preview and building, [Deno](https://docs.deno.com/runtime/) for TypeScript checks and linting, [GitHub Actions](https://docs.github.com/en/actions) for checks and deployment, and [GitHub Pages](https://docs.github.com/en/pages) to make the page public. `deno task ci` runs formatting, lint, type checks, and a production build. The local pre-commit hook runs the same checks.

## Publish the page

In **your repository**, open **Settings → Pages → Build and deployment** and set **Source** to **GitHub Actions**. Push a commit to `main`, then check the **Actions** tab for a successful deployment. The published URL should look like `https://<your-username>.github.io/<your-repository>/`. Open it and check that the button works there too. GitHub Actions may need to be enabled on a new repository before the workflow runs.

For S01, submit the **repository URL**, not just the Pages URL, in the Canvas quiz. The teaching team checks the repository, workflow run, published page, code change, and README before awarding credit. If your computer cannot run the project, talk with your TA during section and describe what you tried in your quiz response.
