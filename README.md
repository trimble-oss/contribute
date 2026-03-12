![Trimble <3 GitHub](/assets/img/trimble-heart-github.svg)

[Help](#need-help) | [Getting Started](#getting-started) | [Publishing](#publishing) | [Policy Compliance](#open--inner-source-policy-compliance) | [Copilot](#github-copilot)

## Need Help?

First, please make sure you have read and followed all of the [instructions below](#getting-started). If you still need help, please request assistance via the [Trimble GitHub Charlie Page](https://charlie.trimble.com/channels/204800003/TrimbleGitHub).

🔍 Already set up? You can **Go straight to the [Trimble GitHub Organization](https://github.com/trimble-oss)**

## Getting Started

**Please be sure you read through the following bullet points and take any necessary action.**

- Add the `GitHub - Trimble` application from your Okta homepage.
- Create a GitHub account if you don't already have one.
  - **Update**: It is now recommended that you create a Trimble specific GitHub account rather than using an existing personal GitHub username. This is particularly important if you want to use GitHub Copilot as using a personal GitHub account risks combining personal data and business data.
- **Replace the default GitHub account avatar with something that uniquely identifies you.**
- **Read the [Contributor Guidelines](/guidelines/index.md). No really, we mean it, read them!**
- Join the [Trimble GitHub Channel on Charlie](https://app.happeo.com/channels/204800003/TrimbleGithub)!

### Request to Join an Organization

The following instructions are sufficient for both adding you as a licensed Trimble GitHub user, and for receiving an invitation to join the **`trimble-oss`** organization.

**If you want to join a different organization**, please continue to follow the instructions below to receive a Trimble license for GitHub. However, you will also need to specifically request access to that organization by finding and contacting an [administrator for that organization](https://trimble.domo.com/page/876535730).

---

Use the following template to prepare and [send an email to the admins mailing list](mailto:trimble-oss-contrib-admins-ug@trimble.com) requesting to join.

**Please include your GitHub username**, *not* your Trimble email address in your message.

```text

Dear Trimble GitHub Administrators,

I have added the GitHub - Trimble application to my Okta account. Please grant access for my GitHub account:

@yourgithubusername (not your Trimble email address!!!)

{ Tell us a bit about yourself and your role at Trimble. }

I am joining because I...

{ why you want to join GitHub }

The accountable person or Trimble division that will pay for a new GitHub user license if needed will be:

{ name of accountable person or name of your division }

Thanks,

{your name}

```

## Publishing

**Ready to publish a project to the public?**

- Read and ensure all requirements are met in the [Trimble OSS - Open Source Publication Policies and Procedures](https://docs.google.com/document/d/1zL_qjgBfECiQ-3KtYRFgVi3zZESPpSYF1mVi755cu_M)
- Contact [trimble-oss-contrib-admins-ug@trimble.com](mailto:trimble-oss-contrib-admins-ug@trimble.com) when you are ready for a pre-publication review and we will work with you to get your project published

## Open & Inner Source Policy Compliance

All repositories in the `trimble-oss` GitHub organization must conform to the [Open and Inner Source Publication Policies and Procedures](https://github.com/trimble-oss/oss-overseer/blob/main/Open%20and%20Inner%20Source%20Publication%20Policies%20and%20Procedures.md), which are maintained in the [oss-overseer](https://github.com/trimble-oss/oss-overseer) repository.

### Key Requirements

- **Security** — Public and internal repos must enable security advisories, Dependabot alerts, and secret scanning. Public repos must also enable code scanning. There must be zero critical or high vulnerabilities at all times.
- **Content** — Public repos must include `SECURITY.md` and a `LICENSE` (from the approved list). All public and internal repos must have at least one maintainer-identity file (`MAINTAINERS.md` or `CODEOWNERS`). Repos should also include `README.md`, `CODE_OF_CONDUCT.md`, and `CONTRIBUTING.md`.
- **Licensing** — Public repo licenses must be on the [approved list](https://docs.google.com/spreadsheets/d/1So3IvPqqb9hEhJEiihWUIreepKsOiv9Ti4ALmHfePi8/edit?usp=drive_link).

### Automated Audits & Enforcement

A weekly automated audit checks every public and internal repository against these policies. Results are published as a [Policy Audit Report](https://github.com/orgs/trimble-oss/discussions/categories/policy-audit-reports) discussion and committed to the [oss-overseer reports](https://github.com/trimble-oss/oss-overseer/tree/main/reports) directory. Repositories with unresolved **MUST** violations may be automatically delisted (public → internal, internal → private). Once all violations are resolved, repositories are automatically relisted.

### Getting Compliant

To bring a repository into compliance, maintainers can use the [oss-compliance Copilot prompt](https://github.com/trimble-oss/oss-overseer/blob/main/.github/prompts/oss-compliance.prompt.md) in VS Code with GitHub Copilot enabled.

For the full policy details, see the [Open and Inner Source Publication Policies and Procedures](https://github.com/trimble-oss/oss-overseer/blob/main/Open%20and%20Inner%20Source%20Publication%20Policies%20and%20Procedures.md).

## Github Copilot

🔍 Looking for **GitHub Copilot**?
  - [Request a License](https://support.trimble.cloud/support/catalog/items/42)
  - Read the [Getting Started Guide](https://docs.google.com/document/d/1qsuPPdbuDQxzii2c9ucvwdWsNRAf09mAwMOpzUjt5UQ/edit#heading=h.kt03vcur1pr9)

