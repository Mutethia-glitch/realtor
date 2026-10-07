# Realtor — Real Estate Business System

This repository is the working implementation plan for the Realtor real-estate / architectural-plan business system.

## Approved frontend baseline

- Lovable project: `1dcd162f-9241-4274-b669-90147d100f96`
- Approved visual baseline commit: `d1e971fde007b12f261168621929091478d35219`
- Rule: preserve the approved marketplace and plan-detail design unless a UI change is explicitly approved.

## Delivery method

We work sequentially, SentinelX-style:

1. Start one numbered task.
2. Implement only what that task requires.
3. Test and validate it.
4. Fix failures before moving on.
5. Mark the task Complete and record notable changes.
6. Proceed to the next dependency-safe task.

See [`TASK_STATUS.md`](TASK_STATUS.md) for the live checklist and [`ROADMAP.md`](ROADMAP.md) for the full roadmap. Phase-specific task files are under [`tasks/`](tasks/).

## Core rules

- No destructive database changes without migrations and rollback.
- No secrets in frontend code.
- Paystack secret keys are server-side only.
- Admin/customer permissions must be enforced server-side.
- Production launch requires regression, security, payment, backup and restore testing.
