# UniOne - Feature Availability by Technology Stack

This file is a verified implementation snapshot across all active UniOne backend ports.

## Legend

| Symbol | Meaning |
| --- | --- |
| ✅ | Implemented and available |
| ⚠️ | Implemented baseline; advanced hardening pending |
| ❌ | Not implemented |

---

## Category-Level Availability

| Category | Laravel | Django | Node.js | Rails | Go | Java | C# |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Authentication and RBAC | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| Organization Management | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| Academic Catalog | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| People Management | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| Student Portal | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Professor Portal | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Communication and Notifications | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Admin CRUD Portal | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| Data Import (CSV/Excel) | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Data Export | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Webhooks and Integrations | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Analytics and Reporting | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Audit and Compliance | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| Performance and Infrastructure | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| CI/CD Pipeline | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Deployment Readiness | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ |

---

## Verified Port Gaps (What Still Needs Implementation)

### Laravel (unione_backend)

- No required implementation gaps.

### Django (unione_django)

- Backend feature parity and production hardening are complete.
- Ready for production deployment.

### Node.js (unione_node)

- Backend feature parity is complete.
- Frontend application remains pending for full-stack delivery.

### Rails (unione_rails)

- Feature parity and enhancement wave completed.
- Remaining work is operational: execution of validation in Bundler-enabled environment.

### Go (unione_go)

- Full feature parity is complete.
- Auth, organization, academic operations, student/professor portals, admin APIs, imports/exports, webhooks, analytics, audit, CI, Swagger, and automated tests are implemented.

### Java (unione_java)

- Project recently initialized.
- Full implementation of all backend modules is pending.

### C# (unione_csharp)

- Foundation, identity/JWT, scoped RBAC, organization CRUD, audit logging, people management baseline, academic catalog, enrollment, waitlist, EF Core persistence, and baseline integration tests are implemented.
- Phase 3/4 validation is still in progress. Import/export remains pending and Phase 5 features such as grades, GPA, transcripts, and schedules have not started.

---

## Scope Clarification

- This document represents active backend repositories only.

## Last Updated: May 16, 2026
