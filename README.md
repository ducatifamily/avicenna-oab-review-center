# Avicenna Occupational Advisory Board Review Center

**Leadership presentation prototype — ALL DATA ARE ILLUSTRATIVE.**

This is a separate, GitHub/Render-ready dashboard for Avicenna Allied Health Institute (AAHI). It is not the student Learning & Simulation Center and is not a production compliance record.

## Branding and logo

The dashboard uses an Avicenna-inspired navy, teal, warm terracotta/orange and white theme. The included `assets/logo-preview.svg` is a **temporary branded approximation**, not an exact official logo.

**To use Avicenna's exact official logo:** save an authorized, high-resolution transparent PNG as:

    assets/avicenna-logo.png

The page tries that file first and falls back to the included preview mark if missing. No code change is required. A PNG around 800 pixels wide or greater is recommended. Please supply the official file from your brand owner; the live website link alone does not supply a reusable original logo file.

## What's in the demo

- Program selector: Medical Assisting (MAC), Dental Assisting (Dental), Medical Billing & Coding (MBC), Behavioral Health Technician (BHT)
- Campus selector: Houston — Main Campus
- Overview with four live, sample-data summary cards
- Recommendation tracker with filters/search, decision trail, editable demo status and local CSV export
- Meeting workspace with proposed agenda, missing documentation flags, and prior-item links
- Separate program review matrix, illustrative outcomes charts and membership seat layout for each program
- Evidence library and optional HTTPS demo links (metadata only)
- Right panel with sample next meeting and evidence gaps
- Print-friendly overview for a leadership presentation
- Browser-only demo changes; Reset Demo restores the original samples

No real member names, emails or protected information are included. Do not enter real confidential data into the static/public demo. All dates and results, including any “Completed” sample item, are illustrative and **do not establish that a meeting or action occurred**.

## GitHub setup

1. Create a **new repository** named `avicenna-oab-review-center`.
2. Download/unzip the package.
3. Upload everything **inside** the folder to the root of the new repository.
4. Check that GitHub root immediately shows `index.html`, `styles.css`, `app.js`, `data/`, `assets/`, `render.yaml`, and this `README.md`.
5. Add `assets/avicenna-logo.png` when you have the approved exact logo.

## Render setup

Create a **Static Site** connected to this new repository.

- Root directory: blank
- Build command: blank
- Publish directory: `.`

The included `render.yaml` can be used as a blueprint instead. After upload changes, deploy the latest commit. If changes do not appear, use Render's **Manual Deploy → Clear build cache & deploy**.

## Technology and security

- HTML, CSS, vanilla JavaScript. No Python, Java, API or backend is necessary for the executive demo.
- Data reside in `data/demo.js`; demo edits are saved to the browser with `localStorage`.
- No authentication, cross-device sync, controlled document storage, digital signatures or audit log.
- For a real board workflow, introduce staff authentication/role permissions, protected storage, audit trail, document versioning, retention policy and backup; do not store private member contacts on this public static site.

## Accreditation-use caution

COE advises institutions to maintain program occupational advisory committees and to document their meetings. The exact required record fields, membership and meeting format must be checked against the handbook and policies **applicable to AAHI's current accreditation stage**, not inferred from the prototype.

- COE: https://council.org/maintaining-accrediation/
- Avicenna: https://avicennaallied.org/

## Demo walkthrough for the boss

1. Open Medical Assisting in Overview: show the four top cards and the Recommendations and Actions table.
2. Click “View trail” for MAC-01: discuss employer input → AAHI decision → owner/action → evidence gap.
3. Switch to Dental, MBC and BHT: show separate committee views and distinct review topics.
4. Open Meeting Workspace and Evidence Library: show how missing agenda/attendance/minutes remain visible, rather than being implied as completed.
5. Open Tracker, change a sample status, then Export CSV; finish with Reset Demo.
