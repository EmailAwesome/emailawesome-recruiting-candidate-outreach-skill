# Recruiting Candidate Outreach Prep with Email Awesome | Agent Skill

A role-relevant shortlist with verification ledger, missing-fit questions and first-contact drafts for review.

**Status:** Public review version; authenticated product QA is pending.

## Why this workflow uses Email Awesome

Email Awesome is the required verification step before a candidate is labeled contact-ready. Use the [main product skill](https://github.com/EmailAwesome/emailawesome-email-verification-agent-skills/tree/main/skills/emailawesome) with an authorized account to inspect credits, verify a small approved batch and reconcile source IDs to final statuses. Keep `CATCH_ALL` and `UNKNOWN` separate. If the product cannot be reached, deliver a draft shortlist with verification pending.

## Example request and result

> Prepare first-contact drafts for my 25 authorized candidates for a remote data engineer role. Verify their work emails and flag missing salary/location facts.

**Illustrative result, not a live run:** Candidate pack: 25 source rows, 18 VALID, 3 CATCH_ALL, 2 UNKNOWN, 2 INVALID; 16 have enough job-related evidence for a draft. No candidates were scored on protected traits or contacted.

## Install

```bash
npx skills add EmailAwesome/emailawesome-recruiting-candidate-outreach-skill --skill recruiting-candidate-outreach-prep
```

For an agent that supports installing skills: “Install `recruiting-candidate-outreach-prep` from https://github.com/EmailAwesome/emailawesome-recruiting-candidate-outreach-skill, confirm installation, then help with my authorized task. Show evidence and unresolved states.”


The [skill instructions](skills/recruiting-candidate-outreach-prep/SKILL.md) are the canonical package. Installing them does not authenticate into the product or grant rights to third-party data.

## Access and review

Confirm the recruiter may use and submit each candidate address and has a lawful reason for processing it. Keep candidate data private, minimize retention and honor suppression. Base relevance on the vacancy and supplied experience; do not infer protected traits, fabricate qualifications, scrape social profiles behind access controls or auto-reject candidates. Sending follows local employment/privacy rules and is outside this skill.

Reference: [ICO B2B marketing guidance](https://ico.org.uk/for-organisations/direct-marketing-and-privacy-and-electronic-communications/business-to-business-marketing/). Product landing: [https://www.emailawesome.com/use-cases](https://www.emailawesome.com/use-cases). The brand is not affiliated with third-party marketplaces or platforms mentioned here.

Before calling this workflow proven, run an authorized product sample with the actual account, reconcile the output, and confirm the requested deliverable. Keep real contact lists, credentials, and private client data out of GitHub.
