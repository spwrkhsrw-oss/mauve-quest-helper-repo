# Mauve Quest Helper — Revenge repository starter

This folder is a static Revenge plugin repository starter. The ZIP in `pool/` is the plugin artifact; `index.json` is the repository index Revenge reads.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `mauve-quest-helper-repo`.
2. Upload `index.json`, this README, and the `pool/` folder to the repository root (not nested inside an extra folder).
3. Open **Settings → Pages**. Under build/deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
4. In `index.json`, replace `YOUR_GITHUB_USERNAME` with your GitHub username. Keep the artifact path and filename unchanged.
5. Wait for GitHub Pages to publish, then open the index URL in a browser and confirm it displays JSON:
   `https://YOUR_GITHUB_USERNAME.github.io/mauve-quest-helper-repo/index.json`
6. In Discord/Revenge, open **Settings → Revenge → Plugins**. Open the repositories/manage-repositories view, add that exact `index.json` URL, save/refresh, find **Mauve Quest Helper**, then install it.

## Important links

- **Repository URL to paste into Revenge:** `https://YOUR_GITHUB_USERNAME.github.io/mauve-quest-helper-repo/index.json`
- **Plugin artifact URL inside `index.json`:** `https://YOUR_GITHUB_USERNAME.github.io/mauve-quest-helper-repo/pool/com.mauve.quest-helper@1.0.0.zip`

Do not paste the GitHub source-page URL or the ZIP link as the repository URL. The repository URL must serve `index.json` over HTTPS.

## Integrity

The artifact's size and SHA-256 in `index.json` are prefilled for the included version 1.0.0 ZIP. If you modify or re-zip the artifact, recalculate both values and update `index.json`.

## Compatibility note

This is a community plugin package, not an official Revenge plugin. Runtime compatibility with every Discord/Revenge build has not been confirmed. The plugin only provides a manual checklist and opens Discord's official Quest page; it does not fabricate activity or report progress on your behalf.
