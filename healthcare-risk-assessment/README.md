# Healthcare Risk Assessment and Compliance Package

A cybersecurity GRC project for a fictional company, **Maple Grove Family Clinic**. It shows how I find, score, and plan for security risk.

> This is a practice project. The clinic and all data in it are made up.

## The Scenario

Maple Grove Family Clinic is a small medical clinic with 50 staff and one location. It stores patient records in an electronic health record (EHR) system. It uses a cloud billing vendor. Staff use laptops, desktops, and a few shared tablets. The clinic has no full time security person.

## What I Did

1. Listed the clinic's important assets.
2. Identified risks and scored them by likelihood and impact.
3. Compared the clinic's current state to the NIST Cybersecurity Framework 2.0.
4. Mapped fixes to NIST SP 800-53 controls.
5. Wrote two core security policies.
6. Summarized everything for leadership.

## Repo Contents

| Folder or File | What It Is |
|---|---|
| `executive-summary.md` | One page summary for clinic leadership |
| `assessment/asset-inventory.md` | Systems, data, and owners |
| `assessment/nist-csf-gap-assessment.md` | Current state vs target by CSF function |
| `assessment/nist-800-53-mapping.md` | Risks mapped to security controls |
| `risk-register/risk-register.csv` | 12 scored risks with treatment plans |
| `policies/access-control-policy.md` | Who can access what |
| `policies/incident-response-policy.md` | What to do when something goes wrong |

## Method

**Risk score = Likelihood (1 to 5) x Impact (1 to 5)**

| Score | Rating |
|---|---|
| 1 to 5 | Low |
| 6 to 12 | Medium |
| 15 to 25 | High |

Treatment options used: Mitigate, Transfer, Accept, Avoid.

## Frameworks Used

- NIST Cybersecurity Framework (CSF) 2.0
- NIST SP 800-53 Rev. 5
- HIPAA Security Rule (referenced for context only)

## Skills Shown

Risk assessment, asset management, control mapping, gap analysis, policy writing, and executive reporting.

## About Me

Ayomide Oriowo. UAlbany cybersecurity graduate (BS, summa cum laude) and MS student in Cybersecurity and Risk Management. I am focused on GRC and compliance advisory roles.
