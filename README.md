# LouveesUploads

Public site for the **LouveesUploads** TikTok application: homepage, privacy policy,
terms of service, and the TikTok domain-verification file.

Served by GitHub Pages at <https://lou-wannabe4090.github.io/LouveesUploads/>.

| Path | Purpose |
|---|---|
| `index.html` | Homepage. Tab title must remain exactly `LouveesUploads` — TikTok review checks it against the app name. |
| `privacy-policy/` | Privacy Policy (canonical URL) |
| `terms-of-service/` | Terms of Service (canonical URL) |
| `privacy.html`, `tos.html` | Same pages at their original URLs, kept so existing links do not break |
| `icon.png`, `icon-192.png`, `favicon.ico` | App icon — favicon on every page, shown in the header of both legal pages |
| `tiktok*.txt` | TikTok domain verification. Do not rename or remove. |
| `.nojekyll` | Disables Jekyll. Without it GitHub Pages builds the tab title from the repo description, which is what failed review. |

If the TikTok app name ever changes, update `APP_NAME` and every `<title>`
together — they must match exactly.
