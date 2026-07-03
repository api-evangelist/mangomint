# Mangomint (mangomint)

Mangomint is salon and spa business management software covering scheduling, point of sale, payroll, marketing, memberships, and forms. **Mangomint has no public developer API.** There is no self-service developer portal, no published REST/GraphQL API reference, and no OpenAPI specification. The only documented programmatic surface is outbound webhooks - appointment booked/updated/canceled, sale completed, and form submitted - which Mangomint support configures by hand against a customer-supplied endpoint URL. Payload schemas and authentication are not published. A small set of one-off, vendor-built integrations (Shopify, Mailchimp, Docovia, Doxy.me, WaiverForever, Gift Up!) can be toggled on from the Mangomint dashboard, and no official Zapier app exists for Mangomint. This repository is documented as a stub because there is no public API to catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mangomint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mangomint/refs/heads/main/apis.yml)

## Tags

- Salon Software
- Spa Software
- Scheduling
- Point of Sale
- Business Management
- Webhooks
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

None. Mangomint does not publish a public API. See [review.yml](review.yml) for the full findings.

## Webhooks (not a public API)

Mangomint offers outbound webhooks as a paid add-on ($50/month, Standard & Unlimited plans only), covering:

- Appointment booked, updated, or canceled
- Sale completed
- Form submitted

Setup is support-mediated: a customer contacts Mangomint chat support with a receiving endpoint URL, and Mangomint staff wire it up. There is no self-service webhook management UI, no published payload schema, and no documented authentication/signature scheme.

## Common Properties

- [Website](https://www.mangomint.com)
- [LinkedIn](https://www.linkedin.com/company/mangomint)
- [Integrations](https://www.mangomint.com/integrations/)
- [Documentation](https://www.mangomint.com/learn/help-articles/integrations/)
- [Webhooks Help](https://www.mangomint.com/learn/webhooks-integration/)
- [Help Center](https://www.mangomint.com/learn/)
- [GitHub Organization](https://github.com/mangomint)
- [Plans](plans/mangomint-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
