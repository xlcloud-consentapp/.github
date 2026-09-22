<div align="center">

<img src="https://raw.githubusercontent.com/xlcloud-consentapp/.github/main/images/consent-app-logo.svg" alt="consent.app logo" width="120" />

# consent.app

**Consent, built for agents.**

[Website](https://consent.app/en/) · [Start for Free](https://consent.app/portal/auth/signup) · [FAQ](https://consent.app/en/resources/faq) · [Contact](mailto:info@consent.app)

</div>

---

## What we build

consent.app is the API and skill layer for verifiable consent — designed so any agent, workflow, or third-party system can request, collect, and confirm consent without building compliance infrastructure from scratch.

Give any agentic workflow a drop-in way to ask for permission and get a verifiable "yes": parental permissions, liability waivers, photo & video releases, age confirmation, emergency & health info, confidentiality agreements, and more — all triggerable programmatically, all auditable.

- **Agent-native by design** — this repo starts with a SKILL.md so any agent (Claude, GPT, or your own) can create and manage consent requests as part of a larger workflow
- **No account required to sign** — recipients approve via a link or QR code on any phone, so agents can request consent from people outside your system
- **Audit-ready by default** — every consent is timestamped, and kept as a full audit trail your agent (or a human) can query
- **GDPR by design** — EU accounts on European infrastructure, US accounts in the US

## Get started

- [iOS App](https://apps.apple.com/app/id6766571378) · [Android App](https://play.google.com/store/apps/details?id=com.xlcloud.consent)
- Questions? Reach us at [info@consent.app](mailto:info@consent.app)

This org holds everything for integrating consent creation into agentic and third-party workflows — starting with the skill definition that lets an agent request, track, and act on consent as a first-class capability.

## Repositories

| Repo | Description |
|------|-------------|
| `skills` | Skill that gates critical or irreversible actions (payments, bookings, emails, sign-ups, checkouts) behind human approval via consent.app. The agent creates a consent request with a user-provided API key; the user approves or rejects it in the consent.app mobile app — a human-in-the-loop safeguard for autonomous agents. |

---

<div align="center">
<sub>© 2026 XLCloud GmbH</sub>
</div>
