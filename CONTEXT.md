# Peopleforce AI Prototypes — Context

## Platform
HRM SaaS. Modules: Time, Attendance, Recruitment, Payroll (upcoming).

## Design System
Vue component library located in /peopleforce-ds
- Use tokens, components and naming conventions from /peopleforce-ds
- Do not invent new patterns — extend existing ones

## User Roles
- Admin: full access, sees Time Codes, payroll data, policy config
- Employee: sees human-readable categories only, no code IDs
- Manager: approves timesheets, no Settings access

## Active Module: Time
Key sections: Time Codes (Settings), Attendance Policy, Timesheet

## Country Contexts
- Poland (pl): Polish Labour Code — OT-WD, OT-SUN, NIGHT, TOIL-EMP
- Ukraine (ua): Ukrainian Labour Code — OT, OT-REST, NIGHT, TOIL

## Prototype Stack
- React JSX (for CEO presentations and stakeholder review)
- Vue (for DS-aligned components, references /peopleforce-ds)
- Design tokens defined in /peopleforce-ds/src/tokens

## Key Conventions
- Badges: status, tier, base type variants
- Drawer: right-anchored 400px, used for create/edit flows
- Tables: always overflow:auto with locked scroll
- Compliance labels are audit trail — never decorative
