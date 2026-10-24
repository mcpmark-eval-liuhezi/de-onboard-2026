# DE-ONBOARD-2026 Rollout Setup Notes

This document records the rollout infrastructure stood up for the **Data Engineering Onboarding**
program (course code **DE-ONBOARD-2026**).

## Program archive bucket

- **Bucket name:** `de-onboard-2026-archive`
- **Lifecycle / retention rule:** objects are **deleted 365 days after creation**
- **Purpose:** long-term archive of program artifacts (tracker workbooks, syllabus exports,
  handover documentation)

## Rollout checklist

1. Canvas course shell: "Data Engineering Onboarding" (DE-ONBOARD-2026), five-module syllabus
2. Archive bucket `de-onboard-2026-archive` with the 365-day deletion lifecycle rule
3. GitHub tracking issue: "Rollout infrastructure setup for DE-ONBOARD-2026"
4. Tracker workbook with a `SyllabusModules` table and a weeks-per-module chart
5. Final go/no-go status report
