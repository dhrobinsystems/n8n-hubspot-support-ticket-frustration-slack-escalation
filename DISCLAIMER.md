# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-support-ticket-frustration-slack-escalation`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, missed, late, duplicated or incorrect escalations; frustrated or at-risk customers who were not flagged; customers flagged without reason; churn, lost revenue or contractual disputes; disclosure of support messages or personal data in Slack or other channels; incorrect or overwritten HubSpot ticket properties or priorities; alert fatigue; exposure of tokens or webhook URLs; service interruptions; and API rate-limit or quota exhaustion.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that frustration scores, severity tiers or regression signals reflect a customer's actual sentiment or intent; that keyword, negation, typography or follow-up rules are correct for your customers, languages or industry; that internal notes, auto-replies, bounces or internal senders are always recognised; that redaction removes all personal or confidential data from previews; that cooldowns prevent every duplicate alert; or that HubSpot Conversations, CRM or Slack API responses remain compatible with this workflow.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true`, `SEND_SLACK_ALERTS=false` and `WRITE_TO_HUBSPOT=false` enabled, before you connect live HubSpot or Slack credentials. Tune thresholds and phrases on representative, anonymised replies from your own customers, review escalated, suppressed and low-scored tickets during the first weeks, and send alerts to a test channel before your team channel.

Treat every frustration score as a prioritisation signal that a person must review. It is not a judgement about a customer, and it must not be used on its own to decide how a customer is treated, priced or served.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), and security policies of HubSpot, Slack, your webhook receiver and any connected services. That includes:

- informing customers, in your privacy notice, that support messages are analysed to prioritise responses;
- confirming a lawful basis for processing support messages this way and for sharing previews in Slack;
- limiting the Slack channel to staff who need it, and applying retention that matches your support data policy;
- granting the private app only the scopes listed in the README;
- securing, rotating and restricting access to the HubSpot token, app client secret, Slack webhook URL and alert webhook token;
- limiting access to n8n execution data, which contains message text;
- reviewing every automatically flagged ticket and priority change.

## No Affiliation

HubSpot, Slack and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All people, companies, email addresses, phone numbers, tickets and identifiers in the fixtures, sample payloads and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, privacy, employment, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
