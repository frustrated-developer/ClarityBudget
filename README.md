# ClarityBudget privacy policy site

A static, dependency-free GitHub Pages page for the policy in `docs/PRIVACY_POLICY.md`.

## Publish from a dedicated public repository

1. Create a public repository for the policy site.
2. Copy `privacy-policy.html` and `styles.css` from this directory to the **root** of that repository.
3. In the new repository, open **Settings → Pages** and choose **Deploy from a branch**, the default branch, and `/(root)`.
4. Wait for the Pages deployment to complete, then open `https://<account>.github.io/<repository>/privacy-policy.html` in a private browser window.
5. Replace the app's `PRIVACY_POLICY_URL` in `app/src/main/java/com/claritybudget/app/presentation/ui/screens/settings/SettingsScreen.kt` with the deployed URL. Enter that same URL in the Play Console listing.

When the policy changes, update both this page and `docs/PRIVACY_POLICY.md`, then redeploy. Confirm the last-updated date and support address before publishing.

The page contains no JavaScript, analytics, external fonts, or other external assets.
