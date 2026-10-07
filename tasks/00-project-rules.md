# Project Rules & Baseline

- Project: Home Harmony Hub / Kijani House Plans preview
- Lovable Project ID: `1dcd162f-9241-4274-b669-90147d100f96`
- Approved frontend baseline commit: `d1e971fde007b12f261168621929091478d35219`
- Baseline rule: preserve the approved marketplace and plan-detail visual design unless the user explicitly approves a UI change.
- Architecture goal: production real-estate / architectural-plan business system with customer accounts, admin operations, catalog management, Paystack payments, digital delivery, leads, reporting, monitoring, backups, testing and production deployment.

## Working Rules

1. We complete tasks sequentially.
2. Each task must be tested before moving on.
3. No destructive database change without a migration and rollback path.
4. No secret keys in the frontend.
5. Paystack secret key remains server-side only.
6. Admin/customer permissions must be enforced server-side, not merely hidden in the UI.
7. No production launch until regression, security, payment, backup and restore tests pass.
8. Maintain task status: Not Started / In Progress / Blocked / Complete.
