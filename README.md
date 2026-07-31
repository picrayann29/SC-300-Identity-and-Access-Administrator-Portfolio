# SC-300: Identity and Access Administrator — Hands-On Portfolio

This repository documents my hands-on preparation for the **Microsoft Certified: Identity and Access Administrator Associate (SC-300)** certification. Every entry represents a task I performed myself in a live Microsoft Entra ID / Azure tenant, captured with the objective, the exact steps I took, screenshots, and what I learned. It is meant to show prospective employers not just that I studied the material, but that I can actually operate the portal.

## About the Certification

SC-300 validates the ability to design, implement, and operate an organization's identity and access management systems using Microsoft Entra ID. Core domains include implementing identities, authentication and access management (Conditional Access, MFA), access management for applications, and identity governance (PIM, access reviews, entitlement management).

## How This Portfolio Is Organized

The work is grouped into four priorities, ordered by exam weight and real-world job value. As I complete each task in my own tenant, I add a dedicated write-up under the matching priority folder and check it off below.

### Priority 1 — Conditional Access & Identity Governance foundations

- [x] Create a Conditional Access policy (require MFA for a group) — [write-up](priority-1/01-conditional-access-mfa-for-a-group.md)
- [x] Create a CA policy with named locations (block by country) — [write-up](priority-1/02-conditional-access-named-locations-block-country.md)
- [x] Use the What-If tool to test a CA policy — [write-up](priority-1/03-conditional-access-whatif-tool-validation.md)
- [x] Configure CA session controls (sign-in frequency) — [write-up](priority-1/04-conditional-access-session-controls-signin-frequency.md)
- [x] Enable and configure PIM for a directory role — [write-up](priority-1/05-privileged-identity-management-directory-role.md)
- [x] Make a user eligible for a role, test activation — [write-up](priority-1/06-pim-eligibility-assignment-and-activation.md)
- [ ] Create an Access Review on a group
- [ ] Create an Access Package with a policy

### Priority 2 — Application access management

- [ ] Register an application (App Registration)
- [ ] Configure SAML SSO for an Enterprise App
- [ ] Add users and groups to an Enterprise App
- [ ] Configure the three gates (Enabled, Assignment Required, Users & Groups)
- [ ] Grant and manage API permissions (delegated vs application)
- [ ] Grant admin consent for an app
- [ ] Configure user consent settings
- [ ] Create a user, a group (assigned + dynamic), assign licenses

### Priority 3 — Identity Protection, authentication & monitoring

- [ ] Configure MFA registration policy in Identity Protection
- [ ] Configure sign-in risk and user risk policies
- [ ] Investigate risky users and risky sign-ins reports
- [ ] Configure SSPR (Self-Service Password Reset)
- [ ] Configure authentication methods policy
- [ ] Create a Temporary Access Pass for a user
- [ ] Set up diagnostic settings to Log Analytics
- [ ] Run a basic KQL query on SigninLogs

### Priority 4 — Completing the picture

- [ ] Create an Administrative Unit, scope a role to it
- [ ] Configure B2B external collaboration settings
- [ ] Create a connected organization
- [ ] Configure cross-tenant access settings
- [ ] Set up Entra Connect (hybrid identity lab)
- [ ] Configure Password Protection (custom banned password list)
- [ ] Create a Lifecycle Workflow

## Repository Structure

```
priority-1/ Conditional Access & governance write-ups
priority-2/ Application access management write-ups
priority-3/ Identity Protection, auth & monitoring write-ups
priority-4/ Advanced / hybrid identity write-ups
```

Each write-up follows the same template: **Objective -> Steps performed -> Screenshots -> Validation -> Key takeaways.**

---

*This is an active portfolio and is updated as I complete each lab. All configurations were performed in a personal, non-production tenant.*# SC-300: Identity and Access Administrator — Hands-On Portfolio

This repository documents my hands-on preparation for the **Microsoft Certified: Identity and Access Administrator Associate (SC-300)** certification. Every entry represents a task I performed myself in a live Microsoft Entra ID / Azure tenant, captured with the objective, the exact steps I took, screenshots, and what I learned. It is meant to show prospective employers not just that I studied the material, but that I can actually operate the portal.

## About the Certification

SC-300 validates the ability to design, implement, and operate an organization's identity and access management systems using Microsoft Entra ID. Core domains include implementing identities, authentication and access management (Conditional Access, MFA), access management for applications, and identity governance (PIM, access reviews, entitlement management).

## How This Portfolio Is Organized

The work is grouped into four priorities, ordered by exam weight and real-world job value. As I complete each task in my own tenant, I add a dedicated write-up under the matching priority folder and check it off below.

### Priority 1 — Conditional Access & Identity Governance foundations

- [x] Create a Conditional Access policy (require MFA for a group) — [write-up](priority-1/01-conditional-access-mfa-for-a-group.md)
- [x] Create a CA policy with named locations (block by country) — [write-up](priority-1/02-conditional-access-named-locations-block-country.md)
- [x] Use the What-If tool to test a CA policy — [write-up](priority-1/03-conditional-access-whatif-tool-validation.md)
- [x] Configure CA session controls (sign-in frequency) — [write-up](priority-1/04-conditional-access-session-controls-signin-frequency.md)
- [x] Enable and configure PIM for a directory role — [write-up](priority-1/05-privileged-identity-management-directory-role.md)
- [ ] Make a user eligible for a role, test activation
- [ ] Create an Access Review on a group
- [ ] Create an Access Package with a policy

### Priority 2 — Application access management

- [ ] Register an application (App Registration)
- [ ] Configure SAML SSO for an Enterprise App
- [ ] Add users and groups to an Enterprise App
- [ ] Configure the three gates (Enabled, Assignment Required, Users & Groups)
- [ ] Grant and manage API permissions (delegated vs application)
- [ ] Grant admin consent for an app
- [ ] Configure user consent settings
- [ ] Create a user, a group (assigned + dynamic), assign licenses

### Priority 3 — Identity Protection, authentication & monitoring

- [ ] Configure MFA registration policy in Identity Protection
- [ ] Configure sign-in risk and user risk policies
- [ ] Investigate risky users and risky sign-ins reports
- [ ] Configure SSPR (Self-Service Password Reset)
- [ ] Configure authentication methods policy
- [ ] Create a Temporary Access Pass for a user
- [ ] Set up diagnostic settings to Log Analytics
- [ ] Run a basic KQL query on SigninLogs

### Priority 4 — Completing the picture

- [ ] Create an Administrative Unit, scope a role to it
- [ ] Configure B2B external collaboration settings
- [ ] Create a connected organization
- [ ] Configure cross-tenant access settings
- [ ] Set up Entra Connect (hybrid identity lab)
- [ ] Configure Password Protection (custom banned password list)
- [ ] Create a Lifecycle Workflow

## Repository Structure

```
priority-1/   Conditional Access & governance write-ups
priority-2/   Application access management write-ups
priority-3/   Identity Protection, auth & monitoring write-ups
priority-4/   Advanced / hybrid identity write-ups
```

Each write-up follows the same template: **Objective -> Steps performed -> Screenshots -> Validation -> Key takeaways.**

---

*This is an active portfolio and is updated as I complete each lab. All configurations were performed in a personal, non-production tenant.*
