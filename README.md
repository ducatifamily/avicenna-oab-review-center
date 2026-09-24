# Avicenna Occupational Advisory Board Review Center — V2 repaired demo

## What changed
- Fixed the JavaScript global name collision (`top`) that prevented the entire dashboard from rendering.
- All styling, sample data, and application JavaScript are now embedded in **one `index.html`**, eliminating deployment failures from missing subfolders/scripts.
- Replaced the broken external image dependency with an embedded branded SVG preview wordmark. It is **not the exact approved logo artwork**. Supply an official logo file if exact artwork is required.
- Added the **Occupational Advisory Committee Curriculum Review Form** as an editable program-specific digital demo based on the supplied AAHI Word form.
- Bundled the original Word review form for download in `resources/`.
- Existing four-program dashboards, recommendations, illustrative metrics, evidence lists, decisions, and CSV export remain included.

## Demo curriculum review flow
1. Select a program (MAC, Dental, MBC, or BHT).
2. Open Curriculum Review Form.
3. Review the six criteria using Meets need / Revise / Unable to assess.
4. Edit proposed recommendations, overall recommendation, priority, and the AAHI follow-up fields.
5. Save locally in your browser or send an illustrative recommendation to the Tracker.

All fields and example metrics are **illustrative**, not actual advisory board actions or official performance information.

## GitHub / Render
Upload `index.html`, `render.yaml`, `README.md`, and the entire `resources/` folder into the ROOT of your existing `avicenna-oab-review-center` repository. Replace the previous `index.html` and `render.yaml`; older app.js/data/styles files can be removed because this version is self-contained.

On Render choose the existing Static Site; Publish Directory `.`; Root Directory blank; Build Command blank. Commit the new index to trigger deploy, and hard-refresh afterward (Ctrl+Shift+R).

## Security / recordkeeping
This is a public static leadership demonstration. It is not a secure document system, does not verify digital signatures, and only persists edits in browser localStorage. Do not enter real contact details or confidential records. For institutional use, add authentication, persistent storage, permissions, evidence retention/versioning and the appropriate approved policy workflow.
