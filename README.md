# iSpring Learn

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

iSpring Learn is a cloud-based eLearning platform and Learning Management System (LMS) that provides a REST API for managing courses, users, groups, departments, enrollments, learning paths, and accessing detailed learner progress reports. The API supports content management, assignment grading, 360-degree performance reviews, on-the-job training, and event-driven webhooks.

## API Access

REST API access is available exclusively on the **Business subscription** tier ($3.14/user/month, billed annually). The platform also provides a SOAP API and webhook support on the Business plan.

**API Hosts:**
- Global (US): `https://api-learn.ispringlearn.com`
- EU Region: `https://api-learn.ispringlearn.eu`

**Authentication:** OAuth 2.0 Client Credentials Grant (POST `/api/v3/token` with `client_id` and `client_secret`)

**API Specification:** OpenAPI 3.0.0 — https://api-learn.ispringlearn.com/docs/rest-api

## Key Capabilities

- User, group, and department management
- Course and content management (SCORM, HTML5)
- Enrollment creation and tracking
- Learner progress statistics and analytics reporting
- Assignment grading and ungraded submission retrieval
- 360-degree performance reviews and appraisal sessions
- On-the-job training management
- Webhook event notifications (SHA-256 signed via X-Hub-Signature header)

## Links

- **Documentation:** https://ispringhelpdocs.com/ispring-learn/api-documentation-10685383.html
- **REST API Docs:** https://ispringhelpdocs.com/ispring-learn/rest-api-10684924.html
- **Webhook Docs:** https://ispringhelpdocs.com/ispring-learn/webhook-62863671.html
- **Integration Guide:** https://www.ispringsolutions.com/articles/integration-of-ispring-learn-with-your-system
- **Pricing:** https://www.ispring.com/pricing
- **Changelog:** https://www.ispring.com/whats-new
- **Support:** https://www.ispringsolutions.com/support

## Contact

- **Support Phone:** +1 800 640 0868
- **Sales Phone:** +1 844 347 7764
