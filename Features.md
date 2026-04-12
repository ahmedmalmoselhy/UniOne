# UniOne - Features

## Core Features

| # | Feature | Laravel (Backend) | Django | Node.js | Rails |
| --- | --------- | ------------------- | -------- | --------- | ------- |
| 1 | Employees upload students lists via Excel sheets | ✅ Full Excel/CSV import | ⚠️ CSV/JSON only (no Excel) | ⚠️ CSV only (no Excel) | ⚠️ Services exist, endpoints pending |
| 2 | Professors upload students grades via Excel sheets | ✅ Full Excel/CSV import | ⚠️ CSV/JSON only (no Excel) | ⚠️ CSV only (no Excel) | ⚠️ Services exist, endpoints pending |
| 3 | Create/Modify Students | ✅ Full CRUD + transfer | ✅ Full CRUD + admin import | ✅ Full CRUD + transfer | ✅ Full CRUD + import |
| 4 | Create/Modify Professors | ✅ Full CRUD | ✅ Via admin users CRUD | ✅ Full CRUD | ✅ Full CRUD |
| 5 | Create/Modify lectures schedule | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections | ✅ JSON schedule in sections |
| 6 | Assign professor to course | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment | ✅ Via section assignment |
| 7 | Assign teaching assistant to course | ✅ Full TA management | ✅ Full TA management | ✅ Full TA management | ❌ Not implemented |
| 8 | Create/Manage group projects | ✅ Full CRUD + members | ✅ Full CRUD + members | ✅ Full CRUD + members | ⚠️ Model exists, endpoints limited |
| 9 | Manage courses and lectures | ✅ Full CRUD + prerequisites | ✅ Full CRUD | ✅ Full CRUD | ✅ Full CRUD |
| 10 | Manage Employees | ✅ Full CRUD | ❌ No Employee model | ✅ Full CRUD | ✅ Full CRUD |
| 11 | Publish announcements | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped | ✅ Global + section-scoped |
| 12 | Send announcements via email | ✅ Email + in-app notifications | ✅ Email + in-app notifications | ⚠️ In-app only (email pending) | ✅ Email + ActionCable |
| 13 | Publish exams schedule | ✅ With conflict detection | ✅ With publish workflow | ✅ With publish workflow | ✅ With conflict detection |
| 14 | Send exams schedule via email | ✅ Email on publish | ✅ Email on publish | ⚠️ Email pending | ✅ Email on publish |
| 15 | Publish final grades | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission | ✅ Professor submission |
| 16 | Send final grades via email | ✅ Email on publication | ✅ Email on publication | ⚠️ Email pending | ✅ Email on publication |
| 17 | Group students by University/Faculty/Department/Course | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy | ✅ Full hierarchy |

## Additional Implemented Features

### Authentication & Authorization

- ✅ Multi-role RBAC (Laravel: 7 roles, Django: 6 roles, Node: 6 roles, Rails: 6 roles)
- ✅ Session + Token-based auth (Laravel: Sanctum + Session, Django: Custom tokens, Node: JWT, Rails: JWT)
- ✅ Password reset flows with token expiration
- ✅ Scoped admin access (university/faculty/department level)
- ✅ Rate limiting on critical endpoints

### Student Features

- ✅ Course enrollment with prerequisite validation
- ✅ Waitlist management with auto-promotion
- ✅ Grade viewing and academic standing
- ✅ Transcript generation (JSON + PDF)
- ✅ Schedule viewing (JSON + ICS export)
- ✅ Attendance tracking
- ✅ Course ratings and feedback

### Professor Features

- ✅ Section management and student rosters
- ✅ Grade submission (bulk via CSV/Excel)
- ✅ Attendance session management
- ✅ Section announcements
- ✅ Schedule viewing and ICS export

### Admin Features

- ✅ University/Faculty/Department CRUD
- ✅ Course/Section CRUD
- ✅ Student/Professor/Employee management
- ✅ Academic term management
- ✅ Webhook management for integrations
- ✅ Audit logging for compliance
- ✅ Analytics and reporting
- ✅ Import/Export (CSV/Excel) for bulk operations

### Communication

- ✅ Global announcements with scoped visibility
- ✅ Section-specific announcements
- ✅ In-app notification system with read tracking
- ✅ Email delivery for announcements, exams, grades
- ✅ Webhook system for external integrations

### Advanced Features

- ✅ GPA calculation (cumulative and per-term)
- ✅ Course prerequisite enforcement
- ✅ Section capacity management
- ✅ Registration window enforcement
- ✅ Academic standing tracking
- ✅ Student department transfer with history
- ✅ Multilingual support (EN/AR) - Laravel only
- ✅ Real-time notifications via ActionCable - Rails only

## Implementation Status by Version

| Version | Status | Completion | Notes |
| --------- | -------- | ------------ | ------- |
| **Laravel (unione_backend)** | 🟢 Production Ready | ~100% | Most complete implementation, all features working |
| **Django (unione_django)** | 🟡 Active Development | ~90% | Missing Employee model, Excel import, some models |
| **Node.js (unione_node)** | 🟡 Active Development | ~75% | Backend mostly done, no frontend, some features pending |
| **Rails (unione_rails)** | 🟢 Production Ready | ~95% | All major features done, minor gaps in TA management and Excel |

## This was last updated: April 12, 2026
