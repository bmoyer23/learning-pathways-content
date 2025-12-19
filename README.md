# Microsoft 365 Learning Pathways – Power Automate Playlist

This repository hosts a **custom content pack** for Microsoft 365 Learning Pathways. It includes curated training resources for **Power Automate**, organized as a playlist that can be imported into your Learning Pathways SharePoint site.

---

## ✅ Contents
- `docs/metadata.json` – Defines audiences, levels, technologies, and categories.
- `docs/playlists.json` – Contains the playlist definition.
- `docs/assets.json` – Lists all learning assets (articles and videos).
- `docs/images/playlists/power_automate_foundations.png` – Playlist thumbnail image.

---

## ✅ How to Enable GitHub Pages
1. Go to **Settings → Pages** in this repository.
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/docs`
3. Click **Save**.
4. After a few minutes, your content will be available at:
   ```
   https://<your-username>.github.io/<repository-name>/
   ```

---

## ✅ Add to Learning Pathways
1. Navigate to your **Learning Pathways Admin page** (`CustomLearningAdmin.aspx`).
2. Go to **Administration → Content Packs → Add Content Pack**.
3. Enter:
   - **Name**: Power Automate Training
   - **URL**: `https://<your-username>.github.io/<repository-name>/`
4. Save and refresh.

---

## ✅ Verify
- Test by opening:
   ```
   https://<your-username>.github.io/<repository-name>/metadata.json
   ```
- If the JSON loads, your content pack is ready.

---

### Notes
- This repo must be **public** for GitHub Pages to work.
- You can customize the playlist by editing `playlists.json` and `assets.json`.

---

### License
Content links point to Microsoft Learn resources (© Microsoft). This repo structure is provided under MIT License for customization.
