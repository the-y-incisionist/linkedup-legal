[README.md](https://github.com/user-attachments/files/22057119/README.md)
# LinkedUp Legal (Privacy)

This is a minimal static site meant to be deployed on **Cloudflare Pages** and sourced from **GitHub**.
It provides a single route:

- `/privacy` → `privacy/index.html`

## Quick Deploy (Cloudflare Pages)
1. Create a new GitHub repo and push this folder.
2. In Cloudflare → **Pages** → **Create a project** → **Connect to Git** → pick this repo.
3. Framework: **None**. Build command: *(leave empty)*. Output directory: `/` *(or `.`)*.
4. Deploy. Then add a **Custom domain**: `privacy.alexjohnboyle.com`.
5. In Cloudflare → **Rules → Redirect Rules** add:
   - If URL path **equals** `/privacy*` on `alexjohnboyle.com`, **301 Redirect** to `https://privacy.alexjohnboyle.com/{path}{query}'
6. The GPT “Privacy Policy URL” can be set to `https://alexjohnboyle.com/privacy` (which redirects), or directly to `https://privacy.alexjohnboyle.com/privacy/`.

**Effective date:** August 30, 2025
