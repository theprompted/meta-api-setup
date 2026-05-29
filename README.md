# Meta Ads API Setup — public lead magnet

A handmade, fully-genericized step-by-step guide for generating a Meta Marketing API
access token to use with Claude Code. This is the opt-in asset for the
"Don't use the Meta Ads MCP with Claude — do this instead" video.

**Live page:** the GitHub Pages URL for this repo.

## What this is / isn't

- ✅ Genericized for mass use. No client names, no account IDs, no personal names.
- ✅ Text-complete — the guide reads fully even with zero screenshots.
- ⏳ Screenshots are placeholders until clean ones are dropped in. See below.

## ⚠️ Why the original screenshots were NOT reused

The source guide (built for a client) had screenshots leaking real identifiers:
business names ("Mat & Vic's", "We Scale Brands", "Illwitzer Service & Consulting GmbH"),
an ad-account ID, and personal names. **None of those can appear in a public asset.**
So this version starts clean.

## Re-shooting clean screenshots

Capture from a **throwaway / test Meta Business** with no real data. Before saving any
shot, confirm there's **no** business name, ad-account ID, email, or personal name
visible in any corner. Crop or blank anything that sneaks in.

Drop each file into `screenshots/` using the **exact filename** below. The page
auto-detects the file and swaps the placeholder for the image (with zoom). No code edits.

| Step | Filename | What to capture |
|---|---|---|
| 1 | `01-create-system-user.png` | "Create system user" dialog — name field + Employee role |
| 2 | `02-create-new-app.png` | "Create new app" / "Create new app ID" button |
| 3 | `03-name-the-app.png` | App details — name + contact email |
| 4 | `04-use-case-marketing-api.png` | Use-cases screen, "Create and manage ads with Marketing API" selected |
| 5 | `05-connect-to-business.png` | Business-selection dropdown |
| 6 | `06a-requirements.png` | Requirements screen — "no requirements identified" |
| 6 | `06b-create-app.png` | Overview screen with "Create app" button |
| 7 | `07a-apps-sidebar.png` | Business Settings → Accounts → Apps in sidebar |
| 7 | `07b-app-in-list.png` | The new app appearing in the Apps list |
| 8 | `08-assign-access.png` | "Assign Access" button on the app page |
| 9 | `09-toggle-app-permissions.png` | Assignment dialog — system user + 4 permissions toggled |
| 10 | `10a-system-users-nav.png` | Navigating back to Users → System users |
| 10 | `10b-installed-apps-tab.png` | Installed apps tab — app with Full control |
| 11 | `11-ad-account-assign-access.png` | Ad account → Assign access → add system user |
| 12 | `12-manage-campaigns-toggle.png` | "Manage campaigns (ads)" toggled on (Partial access) |
| 13 | `13a-generate-token-button.png` | "Generate token" button on system user page |
| 13 | `13b-select-app.png` | Select-app modal |
| 13 | `13c-expiration-60-days.png` | Expiration set to 60 days |
| 13 | `13d-permission-picker.png` | Permission picker with the 4 checked |
| 14 | `14-approval-pending.png` | Yellow approval-pending banner (Path B) |

That's 20 image slots across 14 steps.

## Editing the page

Single file: `index.html`. Self-contained (inline CSS + JS), no build, no dependencies.
