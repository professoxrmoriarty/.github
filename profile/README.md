<div align="center">

<img src="assets/yak-logo.png" alt="YAK" width="280" />

# `.github` · Yaklang Organization Meta Repository (English Edition)

<em>Organization-level meta repository for <a href="https://github.com/professoxrmoriarty">@professoxrmoriarty</a></em>

</div>

---

## What is this

This is a special repository provided by GitHub for "Organizations". It does not contain product code, but solely hosts the shared "storefront" and "default configurations" for the entire [@professoxrmoriarty](https://github.com/professoxrmoriarty) organization.

The most important file is [`profile/README.md`](profile/README.md) — it will be directly rendered by GitHub as the introduction (BIO) at the top of the organization's homepage <https://github.com/professoxrmoriarty>.

> A special GitHub repository whose `profile/README.md` is rendered as the public profile of the entire organization.

## Layout

```text
.github/
├── README.md            # This file: explanation of the repository itself (only visible on this repo's page)
└── profile/
    ├── README.md        # Organization homepage BIO (rendered at the top of github.com/professoxrmoriarty)
    └── assets/          # Images used in the BIO (Hero / LOGO / Icons)
        ├── hero.png
        ├── yak-logo.png
        └── yak-icon.png
```

## How to update the org profile

1. Edit [`profile/README.md`](profile/README.md). Place images in `profile/assets/` and reference them using relative paths like `assets/xxx.png`.
2. Commit and push to the default branch.
3. Refresh <https://github.com/professoxrmoriarty> to see the updates (usually takes effect immediately).

## What else this repo can do

Besides the organization profile, this repository also centralizes the hosting of "organization-level default resources". If any member repository does not have a corresponding file, it will fall back to the version in this `.github` repository.

| Capability | Path | Function |
| :--- | :--- | :--- |
| Org Profile BIO | `profile/README.md` | Rendered as the organization profile introduction (core purpose of this repo) |
| Default Issue Templates | `.github/ISSUE_TEMPLATE/*.md` / `*.yml` | Shared Bug / Feature report templates across the org |
| Issue Template Config | `.github/ISSUE_TEMPLATE/config.yml` | Disables blank issues, guides to documentation / community |
| Default PR Template | `.github/PULL_REQUEST_TEMPLATE.md` | Unifies PR description structures and self-checklists |
| Contributing Guide | `CONTRIBUTING.md` | Organization-wide default contribution guidelines |
| Code of Conduct | `CODE_OF_CONDUCT.md` | Community code of conduct |
| Security Policy | `SECURITY.md` | Vulnerability disclosure process and contact info (crucial for security teams) |
| Funding Options | `FUNDING.yml` | Configuration for the Sponsor button on repository pages |
| Support Options | `SUPPORT.md` | Guides users to the correct channels for seeking help |
| Reusable Workflows | `workflow-templates/` | One-click reusable GitHub Actions templates within the org |
| Default Discussions/Notifications | Relevant configs under `.github/` | Default collaboration configurations at the organization level |

> Inheritance Rule: Member repositories will prioritize files with the same name within their own repository; they only fall back to the `.github` repository's version when missing. Therefore, you can define org-wide defaults without forcing every repo to duplicate them.

## Sites

[yaklang.com](https://yaklang.com) · [memfit.ai](https://memfit.ai) · [ssa.to](https://ssa.to) · [rag.yaklang.com](https://rag.yaklang.com) · [skills.yaklang.io](https://skills.yaklang.io) · [hackbenchmark.com](https://skillshackbenchmark.com) · [yaklang.io](https://yaklang.io)

<div align="center">
<sub>Do the hard, right things. — © Professoxrmoriarty Project</sub>
</div>
