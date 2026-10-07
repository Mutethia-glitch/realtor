## Phase 1 — Baseline, Scope & Architecture

### Task 1 — Freeze approved frontend baseline
**Status:** Complete  
**Objective:** Preserve the current preview as the visual reference for all future work.  
**Validation:** Baseline commit is recorded and preview remains reproducible.

### Task 2 — Define production architecture
**Status:** Not Started  
**Objective:** Confirm frontend, API/server layer, database, auth, storage, email and payment architecture.  
**Recommended starting point:** Supabase/Postgres + Auth + Storage with server/edge functions for protected operations, unless another backend is explicitly selected.  
**Validation:** Architecture diagram and environment plan approved.

### Task 3 — Define environments
**Status:** Not Started  
**Objective:** Separate local/development, staging and production.  
**Validation:** Environment-variable matrix and deployment targets documented.

### Task 4 — Define user roles and permissions
**Status:** Not Started  
**Roles:** Super Admin, Admin/Staff, Registered Customer, Guest.  
**Validation:** Permission matrix approved before coding authorization rules.

### Task 5 — Define business modules
**Status:** Not Started  
**Modules:** users, products/plans, galleries, search, favorites, cart, checkout, orders, payments, secure downloads, leads/custom requests, admin, audit, settings.  
**Validation:** Scope approved.

### Task 6 — Design database schema
**Status:** Not Started  
**Objective:** Define tables, relationships and lifecycle states.  
**Validation:** ERD/schema reviewed before migrations.

### Task 7 — Define secrets/security policy
**Status:** Not Started  
**Objective:** Separate public frontend keys from server-only secrets.  
**Validation:** No sensitive key is required client-side.

### Task 8 — Define migration, seed, rollback and backup strategy
**Status:** Not Started  
**Validation:** Database can be safely upgraded and rolled back.
