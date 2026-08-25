# concord-legal - current status

Updated: 2026-08-24 · regenerated after the default-on sharing change

The one file that answers "where is this right now."

## Now

Nothing in flight. Published and stable.

This repo is **generated output**, not a source. The pages are built from the
Concord app's `src/data/legal.ts` by `scripts/build-legal-pages.ts`. Edit the
source in the app repo and regenerate; do not edit the HTML here. Served at
https://grantmccauley.github.io/concord-legal/

It is the only public repo of the six.

## Shipped recently

- 2026-08-24 - Regenerated for the privacy policy dated August 24, 2026:
  anonymized answer sharing is on by default, disclosed at first run, with a
  full off switch in Account
- 2026-07-30 - Contact address corrected to contact@sideyardstudio.co (#1)
- 2026-07-10 - Publisher set to Side Yard Studio LLC, with a real contact email
- 2026-07-06 - Personal name and email removed; publisher is the project
- 2026-07-05 - Regenerated with minimum age 13, was 17

## Next

Nothing scheduled. This repo changes when the app's legal text changes.

## Open decisions

- **Whether the legal text has been reviewed.** Concord's
  `docs/PRODUCTION_READINESS.md` recorded the legal docs as unreviewed drafts
  as of its 2026-07-01 audit. The placeholders are gone from the app source
  now, but "no longer a draft" and "reviewed by someone qualified" are
  different claims and only you can confirm the second.

## Keeping this current

Regenerate after any change to the app's `src/data/legal.ts`, and update the
header date and commit here when you do.
