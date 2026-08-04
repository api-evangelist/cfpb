# Consumer Financial Protection Bureau (CFPB)

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

The Consumer Financial Protection Bureau (CFPB) provides public REST APIs for searching consumer financial complaint data, accessing Home Mortgage Disclosure Act (HMDA) mortgage lending records, and retrieving regulatory filing data. These APIs support financial researchers, journalists, developers, and the general public in understanding consumer financial markets and lending practices across the United States.

## APIs

### Consumer Complaint Database API
Search and retrieve consumer financial complaints submitted to companies. Contains over 15 million records filterable by product, issue, company, state, and date range.

- **Documentation**: https://cfpb.github.io/api/ccdb/api.html
- **Base URL**: https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1/
- **GitHub**: https://github.com/cfpb/ccdb5-api

### HMDA Data Browser API
Access Home Mortgage Disclosure Act (HMDA) mortgage lending data. Generate aggregation reports and download raw data filtered by geography and financial institution.

- **Documentation**: https://ffiec.cfpb.gov/documentation/api/data-browser/
- **Base URL**: https://ffiec.cfpb.gov/v2/data-browser-api/
- **GitHub**: https://github.com/cfpb/hmda-platform

### HMDA Platform Filing API
Submit HMDA regulatory filings programmatically. For use by covered financial institutions required to report mortgage lending data.

- **Documentation**: https://ffiec.cfpb.gov/documentation/category/developer-apis
- **Base URL**: https://ffiec.cfpb.gov/

## Resources

- **Website**: https://www.consumerfinance.gov/
- **Developer Portal**: https://cfpb.github.io/
- **GitHub Organization**: https://github.com/cfpb
- **Data Research**: https://www.consumerfinance.gov/data-research/
- **X (Twitter)**: https://twitter.com/CFPB

## Contact

- **Technical Support**: tech@consumerfinance.gov

## Licensing

As a U.S. Government agency, CFPB source code and public data are in the public domain within the United States. All public APIs are free to use with no authentication required for public data endpoints.
