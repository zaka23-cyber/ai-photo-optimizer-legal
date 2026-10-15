# AI Dating Photo Optimizer — legal pages

Static English Privacy Policy and Terms for **Zakaria El Rrami, individual developer, Denmark**, for an app intended for adults **18+**.

The customer pages are finalized for review in PR #1. The operator's existing address and support email are preserved. The pages have a last-updated date rather than internal development or publication-status notices. Review and publication approval remain separate from the customer-facing text.

This repository contains only legal HTML, local CSS and publishing instructions. Keep app source, credentials, API keys, personal photos, analysis results and private project evidence out of it. No build, dependencies, JavaScript, forms, analytics or external assets are needed.

## Files

- `index.html` — legal-document navigation and support contact.
- `privacy.html` — data flow, providers, retention, controls and rights.
- `terms.html` — eligibility, permitted use, AI limitations and support.
- `styles.css` — shared responsive and print styling.
- `.nojekyll` — serve the static files directly.

## Sharing confirmation

On **15 October 2026**, the owner confirmed that the OpenAI organization's three Sharing controls show **Disabled**:

- Model feedback.
- Evaluation and fine-tuning data.
- API inputs and outputs.

No settings were changed. The customer disclosure records the disabled optional sharing without claiming that provider abuse-monitoring logs, prompt caching or other necessary retention are eliminated. This is owner-confirmed account configuration, not a claim inferred from an API key or an independent dashboard inspection.

The setting is at [Organization → Data controls → Sharing](https://platform.openai.com/settings/organization/data-controls/sharing). Revisit the disclosure if those settings change. Preserve unrelated project settings.

## Review before publishing

Review the final customer wording, contact information, legal bases and provider arrangements. The retention section states the actual implementation: the service database does not store photo bytes or analysis text; security, consent, job and spending metadata have no scheduled general purge. Do not replace this with an unimplemented deletion deadline or a zero-retention claim.

Publication does not enable photo analysis. The app and hosted processing gates are managed separately and remain disabled. Keep operational approvals and testing instructions in the private app handoff rather than the customer documents.

## Enable GitHub Pages after approval

1. Approve and merge PR #1 into `main`.
2. Open [Settings → Pages](https://github.com/zaka23-cyber/ai-photo-optimizer-legal/settings/pages).
3. Under **Build and deployment → Source**, select **Deploy from a branch**.
4. Select branch **main**, folder **/(root)**, then **Save**.
5. Wait for deployment success and keep **Enforce HTTPS** enabled when available.
6. Verify the published policy text and links before using the URLs in the app.

Expected URLs, to verify after publication:

- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/>
- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/privacy.html>
- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/terms.html>

[GitHub's publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## App handoff

After publication and content verification, update the app's policy URLs and publication flag, together with the matching disclosure version/digest on the existing hosted backend. Preserve the unchecked consent default and material-change renewal. No app code or runtime configuration belongs in this public repository.
