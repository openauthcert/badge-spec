![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)

# 🏷️ OpenAuthCert Badge Specifications

This repository contains the official, versioned **badge specifications** issued by the Open Authentication Certification Initiative (**OpenAuthCert**).

## 📜 Purpose
To define machine-readable criteria, formats, and verification rules for public badges awarded to projects, vendors, and tools that meet ethical identity integration standards.

## 📂 Repository Structure
```
.
├── specs/
│   ├── free-ssso-idp-v0.1.json        # First released badge
│   └── ...                             # Future specs and versions
├── schema/
│   └── badge-schema.json              # Reusable JSON Schema definition
├── examples/
│   └── sample-badge.json              # Sample badge issued to a test project
└── README.md
```

## ✅ Current Specification
### `Free SSO/IdP Support Badge v0.1`
**Requirements:**
- Supports at least one of: OIDC, SAML, or LDAP
- Allows enabling IdP functionality without an enterprise-tier license
- Has publicly documented identity integration
- Can be verified via code or documentation without vendor NDA

See [`specs/free-sso-idp-v0.1.json`](specs/free-sso-idp-v0.1.json) for full format.

## 🛠️ Tools
Verification scripts and parsers will live in the [`tools/`](../tools/) repo (TBD).

## 📄 License
Content in this repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## 🤝 Contributing
Want to suggest a new badge? Open an issue or submit a PR with a `specs/<badge-name>-v<version>.json` and proposed schema updates if needed.

---

🔗 Back to project: https://openauthcert.org
