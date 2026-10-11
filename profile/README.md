<div align="center">

# SethuCMS

**A security-first content management system that works with the database you already have.**

MIT licensed · Open source · Version 0.1.0

</div>

---

## What it is

SethuCMS is a headless CMS with a gateway in front of your data. You connect a database, and the gateway gives you one consistent API, roles, an audit log and a content editor. Your data stays in your own database.

- **Bring your database.** PostgreSQL, MySQL, MongoDB-compatible and Firestore adapters, plus an adapter SDK for writing your own in TypeScript, Go or Python.
- **Secure by default.** Role-based access (admin, editor, viewer), hashed API tokens, sign-in with an authenticator app, rate limits and a tamper-evident audit log.
- **Drafts and review.** Edit safely, preview, then publish.
- **Move data between databases.** Plan, preview and run a migration from one connection to another.

## Repositories

| Repository | What it holds |
| --- | --- |
| [sethucms](https://github.com/SethuCMS/sethucms) | The gateway and core packages |
| [sethucms-admin](https://github.com/SethuCMS/sethucms-admin) | The admin app |
| [sethucms-adapters](https://github.com/SethuCMS/sethucms-adapters) | Database adapters |
| [sethucms-adapter-sdk](https://github.com/SethuCMS/sethucms-adapter-sdk) | Toolkit for writing an adapter |
| [sethucms-sdk-ts](https://github.com/SethuCMS/sethucms-sdk-ts) · [python](https://github.com/SethuCMS/sethucms-sdk-python) · [dart](https://github.com/SethuCMS/sethucms-sdk-dart) | Client libraries |
| [sethucms-docs](https://github.com/SethuCMS/sethucms-docs) | Documentation and the technical blueprint |
| [sethucms-examples](https://github.com/SethuCMS/sethucms-examples) | Example projects |

## Install

```bash
npm install @sethucms/sdk
```

The packages are published under [`@sethucms`](https://www.npmjs.com/org/sethucms) on npm.

## Where it stands

SethuCMS is early. Version 0.1.0 is public and under active development.

- Verified: the gateway, the admin app, access control and the audit log.
- Not yet verified against the real products: the MongoDB (tested with FerretDB only) and Firestore adapters.
- Planned, not built: hosted plans, the schema writer and dashboards.

We would rather tell you what is not finished than have you find out.

## Security

Found a vulnerability? Please report it privately and do not open a public issue. See the `SECURITY.md` in each repository.

## Contribute

Issues and pull requests are welcome. Read `CONTRIBUTING.md` in the repository you want to change, and open an issue first for anything large.

## License

[MIT](https://opensource.org/licenses/MIT)
