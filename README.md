# 🧱 CiSkeleton Applications

This repository is the central index of applications built with **CiSkeleton (CSK) framework**.

It maintains references to individual application repositories as Git submodules, alongside the metadata used to identify and discover available applications.

## 📂 Repository Structure

```text
apps/
├── allowlist.json
├── registry.json
├── apps/default/ # Application submodule
├── apps/example/ # Application submodule
└── ...
```

Each application is maintained in its own Git repository and included here as a submodule. The application repositories have independent source code, versioning, releases, and access permissions.

The actual submodule directories depend on the applications registered in this repository.

## ✅ Registry and Allowlist

- **`registry.json`** — The index of registered applications and their associated metadata.
- **`allowlist.json`** — The allowlist used by the application's discovery or access workflow.

The files serve distinct purposes. Their exact schemas and validation requirements are defined by the tooling that consumes them.

## 📦 Application Repositories

Applications are independently maintained and may be public, private, proprietary, or client-specific.

A submodule reference identifies a repository and a particular commit. It does not automatically synchronize repositories, deploy applications, or guarantee that the referenced commit is accessible to every user.

Access to an application depends on the permissions granted by its own repository.

## 📄 Licensing and Access

This repository serves as an index of CiSkeleton applications. Its public visibility does not grant rights to use, deploy, modify, redistribute, or commercially exploit the applications it references.

Each application is governed by its own applicable license, agreement, access policy, or repository permissions. Third-party dependencies and bundled assets remain subject to their respective licenses.

The presence of an application in this index does not imply that its source code is publicly available or that it is licensed for redistribution.

For licensing or usage-rights inquiries, contact [legal@ianhub.net](mailto:legal@ianhub.net).

## Related Repositories

- [CiSkeleton](https://github.com/ciskeleton) — The framework organization.
- [CiSkeleton Packages](https://github.com/ciskeleton/packages) — The index for modules, plugins, themes, and languages.

---

Maintained by **[Kader Bouyakoub](https://github.com/bkader)**, trading as **[Ianhub](https://www.ianhub.dz)** as part of the CiSkeleton ecosystem.
