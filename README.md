# Care.com (carecom)

Care.com is a two-sided online marketplace that connects families with caregivers across childcare, senior care, pet care, housekeeping, tutoring, and special-needs care. It also runs "Care for Business," an enterprise care-benefit program used by employers such as Google, Starbucks, and Best Buy. Founded in 2007 by Sheila Lirio Marcelo, Care.com went public on the NYSE (ticker CRCM) in 2014 and was acquired by **IAC (IAC Inc.)** in **February 2020 for approximately $500 million**, taking it private.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/carecom/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/carecom/refs/heads/main/apis.yml)

## API Status: No Public Developer API

Care.com **does not publish a documented public developer API.** As of this review (2026-07-03):

- There is **no developer portal** (no `developer.care.com`), **no public API reference**, and **no self-service API keys**.
- No public **OpenAPI** or **AsyncAPI** description is published, and no **REST** or **WebSocket** endpoints are documented.
- The Care.com GitHub organization ([github.com/caredotcom](https://github.com/caredotcom)) contains only internal DevOps/infrastructure tooling (PagerDuty scheduling, Ansible inventory scripts, forked Grails plugins) - **not** customer-facing API libraries or SDKs.
- The only partner-facing programmatic surface located is a **private job-import integration** inside **Care.com Recruiting Solutions / Care for Business**, used to sync job postings from an employer or ATS. It is provisioned through a partnership agreement and is **not openly documented**.

Because no live, documented public API surface exists, this entry is an **honest company stub**: `apis.yml` contains **no `apis` array** and **no fabricated endpoints**, and there are no `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` directories with modeled API data.

## Do Not Confuse With Caring.com

Care.com is frequently confused with **Caring.com** - a **separate company** (a senior-care review/directory service) that **does** publish a documented JSON API at [docs.caring.com](https://docs.caring.com/) (authenticated with a `Caring-Partner` header, with a sandbox at `sandbox-dir.caring.com`). That API belongs to Caring.com, **not** Care.com, and is out of scope for this entry.

## Access & Pricing

Access to the Care.com marketplace is through **paid memberships**, not an API:

- **Basic Membership** - covers screening of individual caregivers, including background checks and identity verification.
- **Premium Membership** - adds benefits such as higher search-result rankings, priority job alerts, and waived background-check fees.

Membership is a consumer/enterprise subscription; **there is no published API pricing** because there is no public API product. Care for Business is sold to employers as a benefit program.

## Tags

- Care
- Childcare
- Senior Care
- Pet Care
- Housekeeping
- Marketplace
- Caregivers
- Two-Sided Marketplace
- IAC
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Common Properties

- [Website](https://www.care.com)
- [Corporate Website](https://www.care.com/about/)
- [LinkedIn](https://www.linkedin.com/company/care-com)
- [GitHub Organization](https://github.com/caredotcom)
- [Help Center](https://help.care.com)
- [Plans / Membership](https://www.care.com/hiw/)
- [Parent Company (IAC)](https://www.iac.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
