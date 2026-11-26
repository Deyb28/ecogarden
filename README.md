# Eco Garden of Barangay Ulango – Operations & Crop Growth Monitoring System

Static web app (HTML/CSS/JS, no build step) based on the Software Engineering 1 research proposal.

## Modules
Dashboard & analytics · Crop batches (plot/crop cycle) · Maintenance tasks · Pest & plant health log · Supplies & inputs (with stock on hand) · Harvests · Printable productivity report

## Roles (demo PINs)
| Role | PIN | Access |
|---|---|---|
| Garden Manager (Ms. Maricel Evangelista) | `1234` | Add / edit / delete everything |
| Barangay Ulango Official | `0000` | View + reports only |

PINs are in `index.html` (`const PINS`). This is a front-end demo, not real security.

## Data
Stored in the browser's `localStorage` (manual encoding, per the scope). Clear site data to reset to sample data.

## Publish on GitHub Pages
1. Create a repo (e.g. `eco-garden-ulango`) and upload `index.html` and `README.md` to the root.
2. Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
3. Open `https://<your-username>.github.io/eco-garden-ulango/` after ~1 minute.
