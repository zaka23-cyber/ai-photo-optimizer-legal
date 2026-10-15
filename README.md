# AI Dating Photo Optimizer — legal pages

English Privacy Policy and Terms for **Zakaria El Rrami, individual developer, Denmark**. The app is intended for adults **18+**.

**Review draft only.** GitHub Pages is not enabled. The postal address and privacy/support email have been populated. OpenAI optional data-sharing settings remain unverified. No effective date or paid-AI approval is implied.

This public repository contains only static legal pages, local CSS and these instructions. Keep app source, credentials, API keys, personal photos, analysis results and private project evidence out of it. The pages have no JavaScript, forms, remote fonts, trackers or dependencies.

## Files

- `index.html` — review status and links.
- `privacy.html` — data flow, providers, retention, controls and rights.
- `terms.html` — eligibility, permitted use and AI limitations.
- `styles.css` — shared responsive and print styling.
- `.nojekyll` — serve the static files directly.

Edit the HTML directly. No build, Node installation, Docker, local Supabase or hosting service is needed.

## Before approving publication

1. Public contact information is populated: Holmbladsgade 63B, st. th., 2300 Copenhagen S, Denmark; z68827163@gmail.com. The support email matches ZELGI's existing support page.
2. Complete the OpenAI setting check below. The current wording deliberately states that sharing is unverified; do not replace it with a disabled claim without confirmation.
3. Review the actual retention statement: photos/results are not saved in the app's database, but security, consent, job and spending metadata have no scheduled general purge. Review necessity, legal bases, processor/transfer arrangements and the handling of valid erasure requests. Do not promise an automatic 30-day backend purge or delete spending history to restart the test allowance.
4. Approve the final wording and effective date. Replace the draft notices/introduction/footer date language and remove the `noindex, nofollow` meta tags only when the pages are final. Keeping a review banner is appropriate for review copies, not a finished policy.
5. Review and merge the legal-page pull request into `main`. This does not enable Pages or authorize paid analysis.

## Exact OpenAI setting to check

Sign in to the organization that owns the API key stored for this app. Open:

**Settings → Organization → Data controls → Sharing**

Direct link: <https://platform.openai.com/settings/organization/data-controls/sharing>

Find **Share inputs and outputs with OpenAI**. Confirm the effective setting for the project that owns this app's key. It must not be opted in for the intended no-optional-sharing disclosure. If the setting is enabled for selected projects, check whether this project's name is selected. An organization default by itself does not establish the project's effective setting.

Also review the optional evaluation/fine-tuning and API feedback sharing controls on that page. They are separate controls; this app's adapter does not submit evaluations, fine-tuning jobs or Playground feedback. Only an organization owner can change these settings.

Report the app project's effective settings in words; do not share the key. Preserve ZELGI's configuration. If both apps use the same OpenAI project, flag that fact before changing project-wide sharing. No settings have been changed by preparing these pages.

Official guide: [Sharing API data with OpenAI](https://help.openai.com/en/articles/10306912-sharing-feedback-evaluation-and-fine-tuning-data-and-api-inputs-and-outputs-with-openai).

## Enable GitHub Pages after review

After the finalized pages are merged:

1. Open this repository's **Settings → Pages**:
   <https://github.com/zaka23-cyber/ai-photo-optimizer-legal/settings/pages>
2. Under **Build and deployment → Source**, select **Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, then **Save**.
4. Wait for GitHub's Pages deployment to succeed. Keep **Enforce HTTPS** enabled when available.
5. Open the published pages below and verify the actual text, working links and absence of placeholders/draft notices before using their URLs in the app.

Expected URLs — **not yet published**:

- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/>
- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/privacy.html>
- <https://zaka23-cyber.github.io/ai-photo-optimizer-legal/terms.html>

GitHub's instructions: [Configure a Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## App handoff

Only after publication and verification should the app use these Privacy Policy/Terms URLs and mark legal publication and the remaining disclosures verified. Update the matching disclosure version/digest in the hosted backend. Keep the existing consent checkbox unchecked by default and preserve renewal when wording changes.

**Publishing a policy does not approve the cumulative $1 test budget.** Paid processing must remain disabled until the owner explicitly approves that separate budget and the remaining device/runtime gates are ready.

The iPhone test should then be one foreground analysis of the saved 3–8 photos, with explicit consent, genuine App Attest, unchanged local photo storage and review of the server's known charges/uncertain holds before any retry. Existing verified TLS, schema, quota and cancellation evidence is reused; no app test suite needs to be rerun merely to publish these static pages.
