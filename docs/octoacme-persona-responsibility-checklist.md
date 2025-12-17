# OctoAcme Persona Responsibility Checklist

This document provides a quick reference table of personas, their primary responsibilities, and key collaboration touchpoints.

## Purpose
- Enable quick identification of who to contact for specific needs
- Clarify handoff points between roles
- Support onboarding and cross-functional alignment

---

## Persona Summary Table

| Persona | Primary Focus | Key Responsibilities | Main Collaborators |
|---------|---------------|---------------------|-------------------|
| **Developers** | Build & deliver features | Implement features, write tests, code reviews | Product Managers, QA Lead, DevOps Engineer, UX Designer |
| **Product Managers** | Define what to build | Product vision, backlog prioritization, success metrics | Developers, Project Managers, Business Analyst, UX Designer |
| **Project Managers** | Coordinate delivery | Schedules, risks, communications, facilitation | All roles - central coordination point |
| **UX Designer** | User experience | User research, interface design, usability testing | Product Managers, Developers, Business Analyst |
| **DevOps Engineer** | Infrastructure & deployment | CI/CD pipelines, monitoring, reliability | Developers, QA Lead, Project Managers |
| **Quality Assurance Lead** | Product quality | Test strategy, validation, quality metrics | Developers, Product Managers, DevOps Engineer |
| **Business Analyst** | Requirements & alignment | Requirements gathering, process analysis, user stories | Product Managers, Developers, QA Lead, UX Designer |

---

## Collaboration Touchpoints

### Daily Standups
**Participants:** Developers, QA Lead, DevOps Engineer, UX Designer  
**Purpose:** Share progress, blockers, and coordination needs  
**Escalation:** Report blockers to Project Manager

### Sprint Planning
**Participants:** All roles  
**Led by:** Project Manager  
**Purpose:** Plan iteration work, clarify requirements, estimate effort  
**Key inputs:** Product Manager (priorities), Business Analyst (requirements), UX Designer (design readiness)

### Weekly Sync (PM + PdM)
**Participants:** Product Manager, Project Manager  
**Purpose:** Align on priorities, risks, and stakeholder needs  
**Outputs:** Updated roadmap, risk mitigations, communication plans

### Design Reviews
**Participants:** UX Designer, Product Manager, Developers  
**Purpose:** Validate designs, ensure feasibility, gather feedback  
**Escalation:** Design dependencies flagged to Project Manager

### Code Reviews
**Participants:** Developers  
**Purpose:** Ensure code quality, share knowledge, catch issues early  
**Observers:** QA Lead may review test coverage

### Test Planning & Validation
**Participants:** QA Lead, Developers, Product Manager  
**Purpose:** Define test strategy, review acceptance criteria  
**Support:** DevOps Engineer provides test environments

### Requirements Workshops
**Participants:** Business Analyst, Product Manager, stakeholders  
**Purpose:** Gather and clarify business requirements  
**Outputs:** User stories, acceptance criteria, impact analyses  
**Next steps:** Shared with Developers and QA Lead for refinement

### Retrospectives
**Participants:** All team members  
**Facilitated by:** Project Manager  
**Purpose:** Reflect on what worked, identify improvements  
**Outputs:** Action items, process changes

### Incident Response
**Led by:** DevOps Engineer  
**Participants:** Developers, QA Lead, Project Manager (escalation)  
**Purpose:** Restore service, identify root cause  
**Follow-up:** Post-mortem with learnings

---

## Escalation and Blocker Reporting

All roles report blockers and escalations to the **Project Manager**, who coordinates resolution across the team.

### Common Blocker Types by Role
- **Developers:** Technical blockers, dependencies on other teams, unclear requirements
- **UX Designer:** Design dependencies, missing research data, design system gaps
- **DevOps Engineer:** Infrastructure issues, tooling gaps, deployment failures
- **QA Lead:** Test environment issues, missing acceptance criteria, critical defects
- **Business Analyst:** Unclear business requirements, stakeholder availability, scope changes
- **Product Manager:** Priority conflicts, stakeholder alignment, roadmap dependencies

---

## How to Use This Checklist

1. **Onboarding:** Review this table to understand who does what
2. **Planning:** Reference collaboration touchpoints when scheduling activities
3. **Escalation:** Use the blocker reporting guidance to route issues appropriately
4. **Communication:** Identify the right persona for specific questions or handoffs

---

*For detailed role definitions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)*
