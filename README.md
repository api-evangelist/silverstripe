# SilverStripe (silverstripe)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SilverStripe is an open-source PHP content management system and framework with a GraphQL and REST API for managing pages, assets, versioning, and custom data objects. It powers 50,000+ live sites and provides a flexible, extensible platform for developers to build content-driven web applications with enterprise-level security and an intuitive editing experience.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/silverstripe/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/silverstripe/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- CMS
- Content Management
- GraphQL
- REST API
- PHP
- Open Source
- Framework
- Pages
- Assets
- Versioning

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### SilverStripe GraphQL API

SilverStripe's GraphQL API provides a content API layer for getting data in and out of the CMS. It supports schema generation from DataObject models, custom types and queries, and extensible schemas. Authentication is handled via CMS Member sessions or HTTP Basic Auth. Available as an optional module in CMS 6.

- **Human URL:** [https://docs.silverstripe.org/en/6/optional_features/graphql/](https://docs.silverstripe.org/en/6/optional_features/graphql/)
- **Base URL:** `https://www.example.com/graphql`

#### Tags

- GraphQL
- CMS
- Content
- Schema

#### Properties

- [Documentation](https://docs.silverstripe.org/en/6/optional_features/graphql/)
- [Authentication](https://docs.silverstripe.org/en/5/developer_guides/graphql/security_and_best_practices/authentication/)
- [Graph Q L](graphql/silverstripe-graphql.md)

### SilverStripe REST API

SilverStripe provides REST API capabilities via the restfulserver module, allowing CRUD operations on DataObject models over HTTP. Authentication supports API token headers (x-api-token) and session-based auth. Default result pagination limits apply (30 default, 100 max per request).

- **Human URL:** [https://github.com/silverstripe/silverstripe-restfulserver](https://github.com/silverstripe/silverstripe-restfulserver)
- **Base URL:** `https://www.example.com/api/v1`

#### Tags

- REST
- CMS
- CRUD
- DataObject

#### Properties

- [Documentation](https://github.com/silverstripe/silverstripe-restfulserver)
- [GitHub Repository](https://github.com/silverstripe/silverstripe-restfulserver)

## Common Properties

- [Website](https://www.silverstripe.org/)
- [Documentation](https://docs.silverstripe.org/)
- [API Reference](https://api.silverstripe.org/)
- [Git Hub Org](https://github.com/silverstripe)
- [LinkedIn](https://www.linkedin.com/company/silverstripe/)
- [Blog](https://www.silverstripe.org/blog/)
- [Pricing](https://www.silverstripe.org/software/)
- [Status Page](https://github.com/silverstripe/platform-status-page)
- [X (Twitter)](https://twitter.com/silverstripe)
- [Changelog](https://docs.silverstripe.org/en/6/changelogs/)
- [Plans](plans/silverstripe-plans-pricing.yml)
- [Rate Limits](rate-limits/silverstripe-rate-limits.yml)
- [Fin Ops](finops/silverstripe-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
