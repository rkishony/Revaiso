# Privacy Policy for Revaiso

**Last updated: June 13, 2026**

## What Revaiso Does

Revaiso is a Chrome extension that turns your editing instructions into native Google Docs suggestions using AI. You select text, describe the edit, and Revaiso inserts the result as a suggestion you can accept or reject.

## Data We Collect

### What Revaiso Servers Receive

| | Hosted (default) | Your own API key (BYOK) |
|---|---|---|
| **Document content** (selected text, instructions, AI output) | Sent to our API to fulfill the request; **not stored** | **Never sent** — goes directly from your browser to your AI provider |
| **Usage metadata** (provider, model, character counts, edit mode) | Sent and stored | Sent and stored |
| **Install metadata** (anonymous install ID, IP, country, install/uninstall events) | Sent and stored | Sent and stored |

Your API key is stored locally only and is never sent to Revaiso.

### Local Settings
Revaiso stores the following locally on your device using Chrome's `storage` API:
- Selected AI provider and model
- API keys you enter (stored locally, never transmitted to Revaiso)
- Saved prompts
- Window position and UI preferences
- Anonymous install ID

Local settings are not transmitted to Revaiso except the install ID (above).

## Data We Do Not Collect

- We do not collect your name, email, or any personally identifiable information.
- We do not track your browsing history or activity outside of Google Docs.
- We do not record keystrokes, clicks, or mouse movements.
- We do not access document content you have not explicitly selected and submitted.

## Third-Party AI Providers

When processing a request, your selected text and parts of the document are sent to an AI provider. Which provider receives your data depends on your settings:

| Setting | Data goes to |
|---|---|
| Revaiso hosted (default) | Revaiso API → AI provider |
| Your own API key | Directly to the chosen AI provider |

Each provider has its own privacy policy. Revaiso does not control how providers handle data.

Country lookup from IP uses [ip-api.com](https://ip-api.com/) (IP sent only for that lookup).

## Data Retention

Revaiso does not retain document content — hosted requests are processed in real time and discarded. Usage and install metadata (see table above) is kept for quota and analytics.

## Children's Privacy

Revaiso is not directed at children under 13. We do not knowingly collect any data from children.

## Changes to This Policy

We may update this policy. The "Last updated" date at the top reflects the most recent revision. Continued use of Revaiso after changes constitutes acceptance of the updated policy.

## Contact

Questions? [Open an issue](https://github.com/rkishony/Revaiso/issues) or email us at the address listed on the [Chrome Web Store listing](https://chromewebstore.google.com/detail/revaiso/pgadnhlihdcmplleikbcmippnmfpfbin).
