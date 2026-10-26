# Hungry

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

# HUNGRY

HUNGRY (Hungry Marketplace, Inc.) is an Arlington, Virginia workplace food platform that
connects corporate clients to a curated network of independent chefs and local restaurants.
Founded in 2016 by Jeff Grass, Eman Pahlavani and Shy Pahlevani, it runs four product lines —
office catering, Group Order individual meal pre-ordering, live events and chef pop-ups, and
snacks and pantry — plus HUNGRY Last Mile, its own delivery and logistics arm. It operates
across 24 US cities and, following the February 2026 merger with Toronto-based hungerhub,
more than ten Canadian markets. Earlier acquisitions include NatureBox and Garten.

## API surface

**HUNGRY publishes no public API and no developer program.** Contract discovery was run on
2026-08-22 against every host we could find — `api.tryhungry.com`, `tryhungry.com`,
`gamma.tryhungry.com`, `admin.tryhungry.com`, `www.hungrylastmile.com` — and against the
`github.com/tryhungry` organization. No OpenAPI, Swagger, GraphQL SDL, AsyncAPI, JSON Schema,
Postman collection, SDK, MCP server or A2A agent card exists on any of them.

A first-party API host does exist at `https://api.tryhungry.com`. It is a private backend for
HUNGRY's own web and mobile clients: behind Cloudflare, HSTS with `preload`, and a plain-text
`404 page not found` on every publicly probed path. It is undocumented and not offered to
third parties.

The one real technical publication HUNGRY makes public is a dated engineering release-notes
site — captured in `changelog/`.

## What is in this repository

| Path | What it records |
|---|---|
| `changelog/hungry-changelog.yml` | HUNGRY's public, dated Tech Release Notes (v3.28.0 → v3.32.0, Apr–Aug 2026), searched from `tryhungry.github.io/techreleasenotes/` |
| `security/hungry-domain-security.yml` | Probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC across five HUNGRY hosts |
| `well-known/hungry-well-known.yml` | A measured absence — every `/.well-known/` path probed, nothing served (the SPA hosts answer 200 with an HTML shell, which is not a document) |
| `plans/hungry-plans-pricing.yml` | A measured absence — quote-only, no published pricing |
| `llms/hungry-llms.txt` | Generated agent-readable summary, leading with the fact that there is nothing to integrate against |

## Links

- Website: <https://tryhungry.com/>
- Tech Release Notes: <https://tryhungry.github.io/techreleasenotes/>
- GitHub organization: <https://github.com/tryhungry>
- HUNGRY Last Mile: <https://www.hungrylastmile.com/>
- Terms of Use & Privacy Policy: <https://tryhungry.com/terms-and-privacy>
