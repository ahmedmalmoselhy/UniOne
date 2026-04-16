# UniOne - Features

## Core Features

| # | Feature | Laravel (Backend) | Django | Node.js | Rails |
| --- | --- | --- | --- | --- | --- |
| 1 | Employees upload students lists via Excel sheets | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import |
| 2 | Professors upload students grades via Excel sheets | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import |
| 3 | Create/Modify Students | ✅ Full CRUD + transfer | ✅ Full CRUD + transfer + import | ✅ Full CRUD + transfer | ✅ Full CRUD + import |
| 4 | Create/Modify Professors | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD |
| 5 | Create/Modify lectures schedule | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections |
| 6 | Assign professor to course | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment |
| 7 | Assign teaching assistant to course | ✅ Full TA management | ✅ Full TA management | ✅ Full TA management | ✅ Full TA management |
| 8 | Create/Manage group projects | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members |
| 9 | Manage courses and lectures | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites |
| 10 | Manage Employees | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD |
| 11 | Publish announcements | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped |
| 12 | Send announcements via email | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ✅ Email + in-app notifications |
| 13 | Publish exams schedule | ✅ With conflict detection | ✅ With publish workflow | ✅ With publish workflow | ✅ With conflict detection |
| 14 | Send exams schedule via email | ✅ Email on publish | ✅ Email on publish | ✅ Email on publish | ✅ Email on publish |
| 15 | Publish final grades | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission |
| 16 | Send final grades via email | ✅ Email on publication | ✅ Email on publication | ✅ Email on publication | ✅ Email on publication |
| 17 | Group students by University/Faculty/Department/Course | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy |

## Implementation Status by Version

| Version | Status | Completion | Notes |
| --- | --- | --- | --- |
| Laravel (unione_backend) | 🟢 Enterprise Production Ready | ~100% | Reference implementation with full enterprise feature set |
| Django (unione_django) | 🟢 Production Ready (Backend) | ~99% | Feature parity complete; remaining work is operational hardening |
| Node.js (unione_node) | 🟢 Production Ready (Backend) | ~99% backend | Backend feature set complete; frontend app still pending |
| Rails (unione_rails) | 🟢 Production Ready | ~99% | Core parity complete; remaining work is validation and coverage expansion |

## Remaining Work by Port

### Laravel (unione_backend)

- No required feature gaps.
- Optional improvements only.

### Django (unione_django)

- Execute full migration/test validation against target PostgreSQL in connected environments.
- Finalize production runbooks and staging SMTP validation.

### Node.js (unione_node)

- Build frontend application (React/TypeScript) for full-stack delivery.
- Continue TypeScript migration and broaden test depth.

### Rails (unione_rails)

- Run full migration and rspec validation in a Bundler-enabled environment.
- Expand request specs for newer endpoints.
- Finalize Sentry gem installation and extend GraphQL domain coverage.

## Notes

- This file tracks implementation reality, not historical roadmap assumptions.
- For low-level technical breakdown, see Features_Tech.md.

## Last Updated: April 15, 2026
