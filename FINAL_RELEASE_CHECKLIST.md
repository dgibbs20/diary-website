# diAry — website growth release checklist

## Completed in this ZIP
- Preserved the existing site structure, branding, blog and links.
- Homepage and five starter search-intent pages from the growth review revision.
- Corrected the Free plan description: text journaling only after trial.
- Corrected Intruder CAM alert recipients: only registered emergency contacts, including the owner only if registered.
- Repaired accidental text corruption in embedded privacy copy (device camera).
- Clarified the AI goodbye message at trial expiration.
- Added email-signup consent explanation and analytics event hooks for store/web clicks.

## Before publishing (requires owner testing or external configuration)
1. Test actual app entitlements and whether previously created entries remain accessible after trial.
2. Test Intruder CAM on iOS/Android: permission prompts, threshold, evidence folder, photo/location accuracy, and delivery to each registered contact.
3. Verify the email-list API endpoint and whether it records marketing consent and offers unsubscribe.
4. Confirm all prices, trial eligibility and platform feature differences in live apps.
5. Independently audit privacy/legal claims, especially data processing, encryption and third-party AI providers. Legal copy is not certified.
6. Connect an analytics platform only after consent/privacy review. The included dataLayer hooks do not transmit events by themselves. App installs, first entries, trials and purchases require separate app/backend instrumentation.
7. Check responsive layouts and real browser interactions on mobile/desktop. Static source checks are not live QA.
8. Expand starter SEO pages with genuinely useful original content and verified screenshots before aggressive promotion.
9. Submit sitemap to Search Console and inspect index coverage.

## Zero-budget next actions
- Search Console: baseline search impressions, queries and clicks weekly.
- App Store Connect and Google Play Console: baseline store impressions, product-page views, installs and conversion rates.
- Use existing Python content publisher to distribute one reusable, accurate product demo with trackable campaign links; do not include real journal data.
