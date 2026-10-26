# Care.com (carecom)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
