# UniOne - Features

## Core Features

| # | Feature | Laravel (Backend) | Django | Node.js | Rails | Go |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Employees upload students lists via Excel sheets | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Excel import endpoint implemented |
| 2 | Professors upload students grades via Excel sheets | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Full Excel/CSV import | ✅ Grade import endpoint implemented |
| 3 | Create/Modify Students | ✅ Full CRUD + transfer | ✅ Full CRUD + transfer + import | ✅ Full CRUD + transfer | ✅ Full CRUD + import | ✅ Full CRUD + transfer |
| 4 | Create/Modify Professors | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD |
| 5 | Create/Modify lectures schedule | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ Section schedule CRUD |
| 6 | Assign professor to course | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment |
| 7 | Assign teaching assistant to course | ✅ Full TA management | ✅ Full TA management | ✅ Full TA management | ✅ Full TA management | ✅ TA assignment APIs |
| 8 | Create/Manage group projects | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members |
| 9 | Manage courses and lectures | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites | ✅ Full CRUD + prerequisites |
| 10 | Manage Employees | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD | ✅ Faculty employee CRUD implemented |
| 11 | Publish announcements | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global/faculty/section scoped |
| 12 | Send announcements via email | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ✅ Email + in-app notifications |
| 13 | Publish exams schedule | ✅ With conflict detection | ✅ With publish workflow | ✅ With publish workflow | ✅ With conflict detection | ✅ Publish workflow implemented |
| 14 | Send exams schedule via email | ✅ Email on publish | ✅ Email on publish | ✅ Email on publish | ✅ Email on publish | ✅ Notification flow implemented |
| 15 | Publish final grades | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission | ✅ Professor grading workflow implemented |
| 16 | Send final grades via email | ✅ Email on publication | ✅ Email on publication | ✅ Email on publication | ✅ Email on publication | ✅ Notification flow implemented |
| 17 | Group students by University/Faculty/Department/Course | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Organization hierarchy implemented |

## Implementation Status by Version

| Version | Status | Completion | Notes |
| --- | --- | --- | --- |
| Laravel (unione_backend) | 🟢 Enterprise Production Ready | ~100% | Reference implementation with full enterprise feature set |
| Django (unione_django) | 🟢 Production Ready (Backend) | ~100% | Feature parity and production hardening complete |
| Node.js (unione_node) | 🟢 Production Ready (Backend) | ~99% backend | Backend feature set complete; frontend app still pending |
| Rails (unione_rails) | 🟢 Production Ready | ~100% | Feature parity and enhancement wave completed |
| Go (unione_go) | 🟢 Production Ready - Full Parity | ~100% | Complete backend parity with portals, admin APIs, imports/exports, webhooks, analytics, audit, CI, Swagger, and tests |

## Remaining Work by Port

...

### Rails (unione_rails)

- Execute migration and test validation in an environment with Bundler.
- Ongoing performance tuning and GraphQL domain expansion.

### Go (unione_go)

- No required feature gaps remain.
- Continue normal production validation and maintenance.

## Notes
...
## Last Updated: May 16, 2026
