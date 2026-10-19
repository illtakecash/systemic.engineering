# Confidentiality protocol

**Status: DRAFT — not ratified**

## Baseline

A private GitHub repository is a distribution boundary, not a confidentiality guarantee. Authorized readers can copy material, Git retains history, and third-party AI services may process content.

## Proposed practices

- Share member profiles and CVs only with the subject's explicit permission; make fields optional.
- Do not commit credentials, API keys, financial account data, private correspondence, client records, or sensitive personal information.
- Before posting an opportunity, confirm the originator permits its disclosure to all current collaborators.
- Minimize meeting notes to decisions, context and actions; avoid unnecessary personal details.
- Agents must not send repo contents to external models, tools or websites beyond the approved workflow.
- Do not quote private material publicly or invite new collaborators without authorization.
- If sensitive material is committed, notify affected people promptly. Deleting a file in a later commit does not erase its Git history.

## Sharing checklist

Who owns the information? Who consented? Who can currently read the repo? Does this need to be here? Can a redacted summary accomplish the same purpose?

## Open questions

Retention periods, incident response, and access-review cadence require explicit group agreement.
