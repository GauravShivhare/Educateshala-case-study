# EducateShala Architecture Overview

EducateShala is a school management SaaS platform with role-based dashboards and school-level access separation.

## Product Type

School management SaaS for schools, admins, teachers, students, and parents.

## Main Roles

- Super Admin
- School Admin
- Principal
- Office Staff
- Teacher
- Student
- Parent

## High-Level Flow

1. Super Admin manages schools.
2. School-level users are created for each school.
3. Principal and Office Staff help manage school operations.
4. Teachers are assigned to specific classes and sections.
5. Teachers manage students only within their assigned class/section.
6. Students and parents access school-related information based on permissions.

## Access Control Direction

The product is designed around:

- Role-based access control
- School-level data separation
- Class-section restrictions for teachers
- Secure authentication
- Private production code

## Public Repository Scope

This public repository only contains:

- Product overview
- Feature documentation
- Roadmap
- Architecture summary
- Hackathon application material
- Safe product screenshots
- Pitch deck

It does not contain:

- Production source code
- Database credentials
- Environment variables
- SMTP credentials
- Admin passwords
- Private business logic
- Database dumps
- Dependency folders

## Future AI Architecture Direction

Planned AI features can be added as separate modules so school staff can generate notices, summarize student records, create reports, and get workflow assistance without exposing private school data publicly.
