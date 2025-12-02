---
layout: default
title: "Chapter 6: Roles, Responsibilities, and Competency Frameworks"
parent: "Part II: Framework"
nav_order: 6
permalink: /chapters/06-competency-frameworks/
---

# Chapter 6: Roles, Responsibilities, and Competency Frameworks

## Learning Objectives

After completing this chapter, you will be able to:
- Define clear ITSM roles with specific responsibilities
- Create and apply RACI matrices for process governance
- Develop comprehensive competency frameworks
- Build skill taxonomies aligned with business needs
- Design career paths that support retention and development
- Implement job family structures for consistent leveling

---

## Introduction

Clear role definitions and competency frameworks are fundamental to effective workforce management. They establish expectations, enable proper resource allocation, support performance management, guide hiring and development decisions, and create transparency around career progression.

Without well-defined roles and competencies, organizations struggle with unclear accountability, inconsistent hiring standards, subjective performance evaluations, and frustrated employees who lack clear career paths. This chapter provides comprehensive frameworks for defining ITSM roles, establishing accountability through RACI matrices, building competency models, and designing career paths.

These frameworks support multiple organizational needs: talent acquisition uses them for hiring criteria, learning and development uses them for training design, performance management uses them for evaluation, and employees use them to understand career options and development needs.

---

## ITSM Role Definitions

### Core ITSM Roles

**Service Desk Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Service Desk Analyst I** | Entry | - Handle tier 1 incidents and service requests<br>- Provide first-line support via phone, email, chat<br>- Document issues in ticketing system<br>- Escalate complex issues | Customer service, basic troubleshooting, ITSM tools, documentation |
| **Service Desk Analyst II** | Intermediate | - Resolve tier 2 incidents and requests<br>- Mentor tier 1 analysts<br>- Create knowledge articles<br>- Support shift operations | Advanced troubleshooting, technical skills, knowledge management, mentoring |
| **Service Desk Team Lead** | Lead | - Coordinate shift operations<br>- Monitor SLA compliance<br>- Handle escalations<br>- Performance coaching | Leadership, process management, metrics analysis, escalation handling |
| **Service Desk Manager** | Manager | - Overall service desk operations<br>- Continuous improvement<br>- Vendor management<br>- Strategic planning | Management, vendor management, financial planning, stakeholder engagement |

**Incident Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Incident Coordinator** | Intermediate | - Monitor incident queue<br>- Ensure proper routing and escalation<br>- Track incident lifecycle<br>- Generate incident reports | Process knowledge, coordination, communication, analytical thinking |
| **Major Incident Manager** | Senior | - Lead major incident response<br>- Coordinate incident bridges<br>- Facilitate root cause analysis<br>- Drive post-incident reviews | Crisis management, leadership, communication, technical knowledge |
| **Incident Management Process Owner** | Manager | - Define incident process<br>- Set policies and procedures<br>- Monitor process effectiveness<br>- Drive continuous improvement | Process design, governance, metrics management, improvement methodologies |

**Problem Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Problem Analyst** | Intermediate-Senior | - Investigate recurring incidents<br>- Perform root cause analysis<br>- Document known errors<br>- Track workarounds | Analytical thinking, technical depth, investigation techniques, documentation |
| **Problem Manager** | Senior | - Proactive problem identification<br>- Trend analysis<br>- Coordinate problem resolution<br>- Manage known error database | Analysis, technical leadership, process management, communication |

**Change Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Change Coordinator** | Intermediate | - Schedule changes<br>- Coordinate CAB meetings<br>- Track change implementation<br>- Maintain change calendar | Organization, scheduling, process execution, communication |
| **Change Manager** | Senior | - Assess change risk and impact<br>- Chair CAB meetings<br>- Approve standard changes<br>- Ensure change compliance | Risk assessment, decision-making, stakeholder management, governance |
| **Change Advisory Board (CAB) Member** | Various | - Review and approve changes<br>- Provide technical assessment<br>- Represent functional area | Technical expertise, risk assessment, collaborative decision-making |

**Release and Deployment Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Release Coordinator** | Intermediate | - Package release components<br>- Schedule deployments<br>- Coordinate release activities<br>- Track release status | Organization, coordination, technical knowledge, project management |
| **Release Manager** | Senior | - Plan and oversee releases<br>- Manage release risks<br>- Coordinate go-live activities<br>- Conduct release reviews | Project management, risk management, technical leadership, communication |
| **Deployment Engineer** | Intermediate-Senior | - Execute deployment activities<br>- Validate deployment success<br>- Perform rollback if needed<br>- Document deployment steps | Technical execution, scripting, troubleshooting, documentation |

**Configuration and Asset Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Configuration Analyst** | Intermediate | - Maintain CMDB accuracy<br>- Document configuration items<br>- Perform configuration audits<br>- Support discovery activities | Data management, attention to detail, technical knowledge, auditing |
| **Asset Manager** | Senior | - Manage hardware and software assets<br>- Track license compliance<br>- Coordinate asset lifecycle<br>- Optimize asset costs | Asset management, financial analysis, vendor management, compliance |

**Service Level Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Service Level Manager** | Senior | - Define and negotiate SLAs<br>- Monitor service performance<br>- Report on SLA compliance<br>- Drive service improvement | Stakeholder management, metrics analysis, reporting, negotiation |

**Knowledge Management Roles:**

| Role | Level | Primary Responsibilities | Key Skills |
|------|-------|-------------------------|------------|
| **Knowledge Manager** | Intermediate-Senior | - Maintain knowledge base<br>- Review and approve articles<br>- Promote knowledge culture<br>- Measure knowledge effectiveness | Content management, technical writing, quality assurance, metrics analysis |

---

## RACI Matrix Framework

### RACI Definitions

**Responsibility Assignment:**

| Code | Role | Definition | Guidelines |
|------|------|------------|------------|
| **R** | Responsible | Performs the work | Multiple people can be R |
| **A** | Accountable | Ultimately answerable; owns outcome | Only ONE person per activity |
| **C** | Consulted | Provides input; two-way communication | Subject matter experts |
| **I** | Informed | Kept updated; one-way communication | Stakeholders who need awareness |

### Incident Management RACI

| Activity | Service Desk | Incident Coordinator | Major Incident Mgr | Technical Teams | Change Mgr | Problem Mgr |
|----------|--------------|---------------------|-------------------|----------------|------------|-------------|
| Log Incident | R/A | I | I | I | - | - |
| Categorize & Prioritize | R/A | C | C | - | - | - |
| Initial Diagnosis | R | C | - | C | - | - |
| Escalate to Tier 2 | R | A | - | I | - | - |
| Declare Major Incident | C | C | A | I | I | I |
| Coordinate Major Incident | I | I | R/A | R | C | C |
| Implement Workaround | R | I | C | R | C | A |
| Restore Service | R | C | C | R/A | C | I |
| Close Incident | R/A | C | C | I | - | I |
| Create Problem Record | C | R | C | C | - | A |

### Change Management RACI

| Activity | Change Initiator | Change Coordinator | Change Manager | CAB | Technical Teams | Release Manager |
|----------|------------------|-------------------|----------------|-----|----------------|-----------------|
| Submit RFC | R/A | I | I | - | - | - |
| Schedule CAB | - | R/A | C | I | - | - |
| Assess Risk/Impact | C | C | R | C | C | - |
| Review in CAB | I | I | R (Chair) | C | C | C |
| Approve/Reject Change | I | I | A | C | - | - |
| Schedule Implementation | C | R | C | - | C | A |
| Implement Change | I | C | I | - | R/A | C |
| Validate Success | C | C | C | - | R/A | C |
| Close Change | C | R | A | - | I | I |
| PIR for Failed Changes | R | C | A | C | R | C |

### Problem Management RACI

| Activity | Service Desk | Incident Mgr | Problem Analyst | Problem Manager | Technical Teams | Change Mgr |
|----------|--------------|--------------|----------------|----------------|----------------|------------|
| Identify Problem | R | C | C | A | C | - |
| Log Problem | C | C | R/A | C | - | - |
| Categorize & Prioritize | I | C | R | A | - | - |
| Investigate Root Cause | C | C | R | C | R/A | - |
| Document Known Error | - | - | R/A | C | C | - |
| Create Workaround | I | C | R | C | R/A | - |
| Raise RFC for Fix | I | - | R | C | R | A |
| Close Problem | - | I | R | A | I | I |

---

## Competency Framework

### Competency Model Structure

**Competency Categories:**

| Category | Description | Examples |
|----------|-------------|----------|
| **Technical Skills** | Role-specific technical capabilities | ITSM tools, cloud platforms, programming languages, networking |
| **Process Knowledge** | Understanding of ITSM processes | ITIL practices, process workflows, policies, standards |
| **Behavioral Competencies** | Personal and interpersonal skills | Communication, problem-solving, customer focus, adaptability |
| **Leadership** | People and organizational leadership | Team management, strategic thinking, change leadership, coaching |
| **Business Acumen** | Understanding of business context | Industry knowledge, financial literacy, strategic alignment |

### Technical Skills Taxonomy

**IT Infrastructure & Operations:**

| Skill Domain | Skills by Proficiency Level |
|--------------|----------------------------|
| **Operating Systems** | Beginner: Windows/Linux basics → Intermediate: System administration → Advanced: Performance tuning → Expert: Architecture design |
| **Networking** | Beginner: TCP/IP basics → Intermediate: Routing/switching → Advanced: Network architecture → Expert: Complex design |
| **Cloud Platforms** | Beginner: Cloud concepts → Intermediate: AWS/Azure administration → Advanced: Multi-cloud architecture → Expert: Cloud strategy |
| **Virtualization** | Beginner: VM concepts → Intermediate: VMware/Hyper-V admin → Advanced: Virtual infrastructure design → Expert: Virtualization strategy |
| **Storage** | Beginner: Storage basics → Intermediate: SAN/NAS management → Advanced: Storage architecture → Expert: Enterprise storage strategy |

**Application Development:**

| Skill Domain | Skills by Proficiency Level |
|--------------|----------------------------|
| **Programming Languages** | Beginner: Syntax and basics → Intermediate: Application development → Advanced: Design patterns → Expert: Language architecture |
| **Web Development** | Beginner: HTML/CSS basics → Intermediate: Full-stack development → Advanced: Framework expertise → Expert: Web architecture |
| **Databases** | Beginner: SQL queries → Intermediate: Database design → Advanced: Performance optimization → Expert: Database architecture |
| **APIs** | Beginner: API consumption → Intermediate: RESTful design → Advanced: API architecture → Expert: API strategy |

**Security:**

| Skill Domain | Skills by Proficiency Level |
|--------------|----------------------------|
| **Security Operations** | Beginner: Security basics → Intermediate: Security monitoring → Advanced: Threat hunting → Expert: Security architecture |
| **Identity Management** | Beginner: User provisioning → Intermediate: IAM administration → Advanced: IAM architecture → Expert: Identity strategy |
| **Compliance** | Beginner: Policy awareness → Intermediate: Compliance implementation → Advanced: Audit management → Expert: Compliance strategy |

### Process Knowledge Competencies

**ITSM Process Proficiency:**

| Process | Level 1 (Awareness) | Level 2 (Working) | Level 3 (Advanced) | Level 4 (Expert) |
|---------|---------------------|-------------------|-------------------|------------------|
| **Incident Management** | Understands purpose and flow | Executes process activities | Identifies improvements | Designs and optimizes process |
| **Problem Management** | Knows problem vs. incident | Investigates problems | Leads RCA sessions | Establishes problem strategy |
| **Change Management** | Submits RFCs correctly | Assesses change risk | Chairs CAB | Defines change policy |
| **Service Request** | Fulfills basic requests | Handles complex requests | Designs request catalog | Optimizes service delivery |
| **Knowledge Management** | Creates knowledge articles | Reviews and approves content | Manages knowledge base | Develops knowledge strategy |

### Behavioral Competencies

**Core Behavioral Competencies:**

| Competency | Level 1 | Level 2 | Level 3 | Level 4 |
|------------|---------|---------|---------|---------|
| **Communication** | Clear basic communication | Adapts style to audience | Influences stakeholders | Communicates complex strategies |
| **Problem Solving** | Solves routine problems | Analyzes complex issues | Develops innovative solutions | Creates problem-solving frameworks |
| **Customer Focus** | Responsive to customer needs | Anticipates customer needs | Builds customer relationships | Drives customer-centric culture |
| **Collaboration** | Works well in team | Facilitates team collaboration | Leads cross-functional initiatives | Builds collaborative ecosystems |
| **Adaptability** | Accepts change | Adapts quickly to change | Leads change initiatives | Drives organizational transformation |
| **Initiative** | Takes action when asked | Identifies and acts on opportunities | Drives initiatives proactively | Creates strategic initiatives |

### Leadership Competencies

**Leadership Skill Levels:**

| Competency | Individual Contributor | Team Lead | Manager | Director |
|------------|----------------------|-----------|---------|----------|
| **People Leadership** | Mentors peers | Leads small team | Manages team and performance | Leads multiple teams and managers |
| **Strategic Thinking** | Understands team goals | Contributes to strategy | Develops team strategy | Develops organizational strategy |
| **Decision Making** | Makes individual decisions | Makes team-level decisions | Makes functional decisions | Makes strategic decisions |
| **Resource Management** | Manages own time | Coordinates team resources | Manages budget and resources | Manages large budgets and portfolios |
| **Change Leadership** | Adopts change | Helps team adopt change | Leads change initiatives | Drives organizational transformation |

---

## Career Paths and Progression

### Job Family Structure

**IT Operations Job Family:**

```
┌─────────────────────────────────────────────────────────────────┐
│                   IT OPERATIONS CAREER PATH                      │
└─────────────────────────────────────────────────────────────────┘

MANAGEMENT TRACK                    INDIVIDUAL CONTRIBUTOR TRACK

Director of Operations              Distinguished Engineer
       ▲                                   ▲
       │                                   │
Operations Manager                  Principal Engineer
       ▲                                   ▲
       │                                   │
Service Delivery Manager            Senior Engineer III
       ▲                                   ▲
       │                                   │
Team Lead                           Senior Engineer II
       ▲                                   ▲
       │                    ┌──────────────┘
Senior Analyst II          │
       ▲                   │
       │                   │
Senior Analyst I ──────────┘
       ▲
       │
Analyst II
       ▲
       │
Analyst I
       ▲
       │
Associate Analyst
```

### Level Definitions - Service Desk Example

**Service Desk Career Ladder:**

| Level | Title | Experience | Key Characteristics | Compensation |
|-------|-------|------------|---------------------|--------------|
| **1** | Associate Analyst | 0-1 year | Learning fundamentals; requires close supervision | $40K-$50K |
| **2** | Analyst I | 1-2 years | Independent on routine tasks; occasional guidance needed | $50K-$60K |
| **3** | Analyst II | 2-4 years | Fully independent; handles complex issues; mentors juniors | $60K-$75K |
| **4** | Senior Analyst I | 4-6 years | Subject matter expertise; drives improvements; mentors team | $75K-$90K |
| **5** | Senior Analyst II | 6-8 years | Deep expertise; leads initiatives; recognized expert | $90K-$110K |
| **6** | Team Lead | 5+ years | First-line leadership; coordinates team; tactical management | $95K-$115K |
| **7** | Service Desk Manager | 7+ years | Full operational management; strategic planning; P&L responsibility | $110K-$140K |

### Promotion Criteria

**Promotion Framework:**

| Criterion | Weight | Assessment Method |
|-----------|--------|-------------------|
| **Time in Role** | 15% | Minimum tenure requirements met |
| **Performance** | 30% | Meets/exceeds expectations for 2+ cycles |
| **Competency Demonstration** | 35% | Demonstrates next-level competencies |
| **Business Impact** | 15% | Tangible contributions and results |
| **Organizational Need** | 5% | Role availability and business need |

**Competency-Based Promotion:**

| Current Level | To Advance, Must Demonstrate |
|--------------|------------------------------|
| **Analyst I → Analyst II** | - Independent problem resolution<br>- Knowledge article creation<br>- Mentoring of Level 1 analysts<br>- Handling complex technical issues |
| **Analyst II → Senior Analyst I** | - Subject matter expertise in key area<br>- Process improvement contributions<br>- Cross-functional collaboration<br>- Formal mentoring of junior staff |
| **Senior Analyst → Team Lead** | - Leadership of projects or initiatives<br>- Conflict resolution skills<br>- Shift coordination experience<br>- Performance coaching ability |
| **Team Lead → Manager** | - Strategic thinking and planning<br>- Budget management experience<br>- Vendor relationship management<br>- Continuous improvement leadership |

### Lateral Mobility Options

**Cross-Functional Career Moves:**

| From | To | Transferable Skills | Gap Skills |
|------|-----|---------------------|------------|
| **Service Desk Analyst** | Problem Analyst | Troubleshooting, ITSM tools, customer focus | Root cause analysis, investigation techniques |
| **Service Desk Analyst** | Change Coordinator | Process knowledge, communication, documentation | Change management, risk assessment |
| **Incident Coordinator** | Release Coordinator | Coordination, communication, process execution | Release management, deployment knowledge |
| **Problem Analyst** | DevOps Engineer | Troubleshooting, analysis, technical depth | Automation, CI/CD, infrastructure as code |
| **Change Manager** | Service Level Manager | Risk management, stakeholder engagement | SLA design, metrics management, reporting |

---

## Skill Development Planning

### Individual Development Plan (IDP)

**IDP Template:**

| Section | Content |
|---------|---------|
| **Employee Information** | Name, role, level, manager, date |
| **Career Goals** | Short-term (1 year), medium-term (3 years), long-term (5+ years) |
| **Current Competencies** | Assessment of current skills against role requirements |
| **Development Gaps** | Skills needed for current role or career goals |
| **Development Actions** | Specific activities to close gaps (training, projects, mentoring) |
| **Success Metrics** | How progress will be measured |
| **Timeline** | Milestones and target completion dates |
| **Resources Required** | Training budget, time allocation, mentoring support |
| **Progress Reviews** | Quarterly check-ins with manager |

### Development Strategies by Competency Type

**Learning Modalities:**

| Competency Type | Development Strategies | Timeline |
|----------------|------------------------|----------|
| **Technical Skills** | - Formal training courses<br>- Certifications<br>- Hands-on labs<br>- Side projects | 3-6 months per skill |
| **Process Knowledge** | - ITIL/process training<br>- Job shadowing<br>- Process documentation review<br>- Participation in process activities | 2-4 months |
| **Behavioral Competencies** | - Soft skills training<br>- Coaching and feedback<br>- Stretch assignments<br>- Peer learning | 6-12 months |
| **Leadership** | - Leadership development programs<br>- Executive coaching<br>- Lead projects/initiatives<br>- Mentoring relationships | 12-24 months |

---

## Competency Assessment

### Assessment Methods

**Multi-Source Assessment:**

| Method | Description | Frequency | Purpose |
|--------|-------------|-----------|---------|
| **Self-Assessment** | Employee evaluates own competencies | Annual | Self-awareness; development planning |
| **Manager Assessment** | Manager evaluates employee competencies | Annual | Performance evaluation; promotion decisions |
| **Peer Review** | Colleagues provide feedback | Annual or bi-annual | 360-degree view; collaboration skills |
| **Skills Testing** | Technical assessments and certifications | As needed | Validate technical proficiency |
| **Project Reviews** | Evaluation of work products and outcomes | Per project | Applied competency demonstration |

### Competency Assessment Scale

**Rating Scale:**

| Level | Rating | Definition | Development Need |
|-------|--------|------------|------------------|
| **5** | Exceeds | Significantly exceeds level expectations; mentors others | None for current role; prepare for next level |
| **4** | Fully Meets | Consistently meets all expectations; occasional excellence | Continue to refine and deepen |
| **3** | Meets Most | Meets most expectations; developing in some areas | Targeted development in gap areas |
| **2** | Developing | Working toward proficiency; needs regular guidance | Structured development plan required |
| **1** | Below | Does not meet expectations; significant gaps | Intensive development or role reassessment |

---

## Key Takeaways

- **Clear role definitions** establish accountability and set performance expectations
- **RACI matrices** eliminate confusion about who does what in processes
- **Competency frameworks** provide objective standards for hiring, development, and evaluation
- **Career paths** create transparency around advancement opportunities and retention
- **Job families** enable consistent leveling and compensation across the organization
- **Development planning** translates competency gaps into actionable learning plans
- **Multi-source assessment** provides comprehensive view of competency levels

---

## Summary

Roles, responsibilities, and competency frameworks are the foundation of effective workforce management. This chapter provided comprehensive definitions of ITSM roles, RACI matrices for process governance, competency models spanning technical and behavioral skills, career path structures, and development planning frameworks.

These frameworks serve multiple purposes: they guide hiring decisions, inform development investments, enable fair performance evaluation, support succession planning, and provide employees with clear expectations and career visibility. Organizations with mature role and competency frameworks experience better role clarity, more effective hiring, targeted development, and improved retention.

Implementation of these frameworks requires collaboration between HR, IT leadership, and subject matter experts. They should be reviewed and updated regularly to reflect evolving technology, business needs, and industry best practices.

---

## Review Questions

1. **RACI Application**: Create a RACI matrix for the software deployment process, including roles such as Release Manager, Deployment Engineer, Change Manager, Application Owner, and Infrastructure Team.

2. **Competency Assessment**: An Analyst II wants to advance to Senior Analyst I. Using the competency framework, what specific competencies should they develop, and what evidence would demonstrate readiness?

3. **Career Pathing**: An experienced Service Desk Analyst is interested in moving into either Problem Management or Change Management. Compare the skill requirements and suggest a development plan for each path.

4. **Role Design**: Your organization is implementing DevOps practices. How would you define the DevOps Engineer role, including responsibilities, required competencies, and where it fits in the existing job family structure?

5. **Competency Gaps**: Your team scores high on technical skills but low on behavioral competencies like communication and collaboration. Design a development strategy to address this gap across the team.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 5: Talent Acquisition and Recruitment](/TalentAndWorkforceManagementHandbook/chapters/05-talent-acquisition/) | [Chapter 7: Workflows and Processes](/TalentAndWorkforceManagementHandbook/chapters/07-workflows/) |
