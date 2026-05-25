# Privacy Policy for Revaiso

**Last updated: May 25, 2026**

## What Revaiso Does

Revaiso is a Chrome extension that turns your editing instructions into native Google Docs suggestions using AI. You select text, describe the edit, and Revaiso inserts the result as a suggestion you can accept or reject.

## Data We Collect

### Selected Document Text
When you submit a revision request, Revaiso sends the text you selected and your instruction to an AI model. This is the only content transmitted, and it is used solely to generate the requested suggestion.

- **If you use the Revaiso hosted service:** your text is sent to our API, which forwards it to an AI provider to fulfill the request. We do not log or store your document content beyond the duration of the request.
- **If you use your own API key:** your text is sent directly from your browser to the AI provider you configured (e.g. OpenAI, Anthropic, Google). Your key is stored locally on your device and is never sent to Revaiso servers.

### Local Settings
Revaiso stores the following locally on your device using Chrome's `storage` API:
- Selected AI provider and model
- API keys you enter (stored locally, never transmitted to Revaiso)
- Saved prompts
- Window position and UI preferences
- Anonymous install ID for quota tracking

None of this data is transmitted to Revaiso except the anonymous install ID for rate-limiting purposes.

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

## Data Retention

Revaiso does not retain your document content. Requests are processed in real time and discarded. Local settings remain on your device until you uninstall the extension or clear them in Settings.

## Children's Privacy

Revaiso is not directed at children under 13. We do not knowingly collect any data from children.

## Changes to This Policy

We may update this policy. The "Last updated" date at the top reflects the most recent revision. Continued use of Revaiso after changes constitutes acceptance of the updated policy.

## Contact

Questions? [Open an issue](https://github.com/rkishony/Revaiso/issues) or email us at the address listed on the [Chrome Web Store listing](https://chromewebstore.google.com/detail/revaiso/pgadnhlihdcmplleikbcmippnmfpfbin).
