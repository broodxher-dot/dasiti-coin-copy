# Dacity Coin — static HTML copy

This project packages the HTML snapshot supplied in the conversation as a deployable static page.

## Deploy to Vercel for free

1. Create a new GitHub repository and upload the files in this folder.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Leave the framework preset as **Other**.
4. Leave the build command and output directory empty/default (the root contains `index.html`).
5. Click **Deploy**.

You can also use Vercel's CLI from this directory:

```bash
npx vercel
```

## Important limitation

The supplied file is a rendered HTML snapshot, not the original source repository. To preserve the closest appearance from the available material, the page keeps the original markup and loads its existing CSS, JavaScript chunks, and media from `https://dacitycoins.com`. Therefore this is **not yet a fully independent copy**: if the original site removes or changes those assets, some or all of the deployed page may change or stop working.

For a self-contained replica, obtain the original site's asset files (images, fonts, CSS, JavaScript) and the rights/permission needed to reuse them, then serve those assets from this project. This project does not include private source code or recover the original React/Next.js components.

## Notes

- The content and external links remain those present in the provided HTML snapshot.
- Review any wallet, token, or contract-related links carefully before using the site publicly.
