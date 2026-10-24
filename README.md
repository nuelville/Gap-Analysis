ISO/IEC 27001:2022 Gap Analysis --- Cartex Technologies Ltd
Project Overview
This project documents an ISO/IEC 27001:2022 Annex A gap analysis for
Cartex Technologies Ltd. It identifies five information-security
gaps, maps each gap to a relevant Annex A control, explains why the
control is relevant, and defines a proposed Information Security
Management System (ISMS) scope.

The assessment focuses on asset inventory, security awareness, physical
access, access-rights management, and multi-factor authentication (MFA).
These areas provide a structured starting point for understanding where
current practices may not align with the selected ISO/IEC 27001:2022
controls.
Project note: This README reflects the findings and proposed scope
in the supplied gap-analysis document. It does not claim that the
identified gaps have been remediated, that the controls have been
independently tested, or that Cartex Technologies Ltd is ISO/IEC 27001
certified.

Objectives
- Identify the security gaps documented for Cartex Technologies Ltd.
- Map each gap to the relevant ISO/IEC 27001:2022 Annex A control.
- Explain the security and governance rationale for each control.
- Define a proposed ISMS scope under Clause 4.3.
- Present the findings in a clear format suitable for GRC
  documentation and follow-up planning.
Assessment Scope
The proposed ISMS scope in the source document is:
The Information Security Management System (ISMS) applies to all
information assets, technology systems, infrastructure, and business
processes involved in delivering Cartex Technologies Ltd's digital
management platform---encompassing sales, inventory, customer data,
and payment services. This scope covers all management,
administrative, and operational functions across both on-site
operations at the main office and all remote working environments.

This scope includes the platform's sales, inventory, customer-data, and
payment-service functions, as well as relevant information assets and
technology across on-site and remote work environments.
Methodology
The supplied document presents a control-mapping gap analysis. For each
identified gap, it records:
1. Current-state gap --- the security weakness or inconsistency
   described in the document.
2. Relevant Annex A control --- the ISO/IEC 27001:2022 control
   associated with the gap.
3. Control category --- Organizational, People, Physical, or
   Technological.
4. Relevance --- why the control matters to information security.
The document does not provide a formal scoring model, risk ratings,
control-test evidence, implementation owners, deadlines, or remediation
status. Those items would need to be established during a subsequent
risk-treatment and remediation-planning activity.
Gap Analysis Findings
Summary
  #                Identified gap    ISO/IEC           Annex A category
                                      27001:2022
                                      control           
  1                 Lack of central   A.5.9 ---         Organizational
                    asset inventory   Inventory of      Controls (A.5)
                                      information and
                                      other associated
                                      assets            

  2                 Inconsistent      A.6.3 ---         People Controls
                    security          Information       (A.6)
                    awareness         security
                    training          awareness,
                                      education and
                                      training          

  3                 Unmanaged         A.7.2 ---         Physical Controls
                    physical access   Physical entry    (A.7)
                    to equipment                        

  4                 Unreviewed role   A.5.18 --- Access Organizational
                    transitions       rights            Controls (A.5)

  5                 Inconsistent MFA  A.8.5 --- Secure  Technological
                implementation    authentication    Controls (A.8)
1. Lack of Central Asset Inventory
Identified gap

There is no formal, centralized inventory of important information
assets. Different teams maintain disconnected lists.

Mapped control
- Control: A.5.9 --- Inventory of information and other associated
  assets
- Category: Organizational Controls (A.5)
Why the control is relevant

An ISMS requires the organization to identify and maintain an inventory
of assets associated with information and information-processing
facilities. An inventory supports accountability and helps ensure that
assets receive appropriate protection.

Follow-up considerations
- Establish a central inventory for relevant information assets and
  associated assets.
- Define who is responsible for maintaining inventory records.
- Agree on a consistent process for recording and updating assets.
- Periodically review inventory completeness and accuracy.
These follow-up considerations are suggested next steps, not remediation
activities confirmed as completed in the source document.
2. Inconsistent Security Awareness Training
Identified gap

Employees receive security training when they join the organization, but
there is no ongoing or refresher training for existing staff.

Mapped control
- Control: A.6.3 --- Information security awareness, education and
  training
- Category: People Controls (A.6)
Why the control is relevant

Employees need regular security-awareness education and updates relevant
to their organizational roles. Ongoing training helps maintain security
vigilance over time.

Follow-up considerations
- Establish a recurring security-awareness training schedule.
- Provide refresher training for existing employees.
- Tailor awareness content to organizational roles and
  responsibilities.
- Maintain records of training completion and identify outstanding
  training needs.
The source document identifies the absence of ongoing and refresher
training; it does not specify a training frequency or completion metric.
3. Unmanaged Physical Access to Equipment
Identified gap

Office entry is restricted, but there is no formal process for
controlling and reviewing access to specific internal areas that host
critical systems or equipment.

Mapped control
- Control: A.7.2 --- Physical entry
- Category: Physical Controls (A.7)
Why the control is relevant

Secure areas containing sensitive information-processing equipment must
be protected by appropriate entry controls and access-review processes.
These measures help prevent unauthorized physical access.

Follow-up considerations
- Identify internal areas that host critical systems and equipment.
- Define authorization requirements for entry to those areas.
- Establish a process for reviewing and updating physical access
  permissions.
- Document how access is approved, changed, and revoked.
The supplied document notes that office entry is restricted; the
identified gap concerns access control and review for specific internal
areas.
4. Unreviewed Role Transitions
Identified gap

System access rights are not promptly reviewed or modified when
employees change roles within the company.

Mapped control
- Control: A.5.18 --- Access rights
- Category: Organizational Controls (A.5)
Why the control is relevant

Access rights to information and information-processing assets should be
provisioned, modified, or revoked in a timely manner whenever an
employee's role or status changes.

Follow-up considerations
- Establish a defined process for role changes and access-rights
  reviews.
- Coordinate role transitions with the relevant access-provisioning
  process.
- Review whether existing permissions remain appropriate for the
  employee's new role.
- Record access changes and revocations to support accountability.
These considerations are proposed follow-up actions; the source document
does not describe an existing remediation workflow or its implementation
status.
5. Inconsistent Multi-Factor Authentication (MFA) Implementation
Identified gap

MFA is not applied universally across all relevant systems, cloud
applications, and user accounts.

Mapped control
- Control: A.8.5 --- Secure authentication
- Category: Technological Controls (A.8)
Why the control is relevant

Secure authentication technologies, including MFA, should be
consistently enforced based on information-security risk to protect
access to systems and applications.

Follow-up considerations
- Identify relevant systems, cloud applications, and user accounts.
- Assess where MFA is enabled and where coverage is incomplete.
- Define risk-based authentication requirements for in-scope services.
- Track exceptions and monitor progress toward the approved coverage
  target.
The source document identifies inconsistent MFA coverage but does not
provide a system-by-system inventory, exception list, or implementation
status.
Proposed ISMS Scope --- ISO/IEC 27001 Clause 4.3
The proposed scope covers information assets, technology systems,
infrastructure, and business processes involved in delivering Cartex
Technologies Ltd's digital management platform, including:
- Sales
- Inventory
- Customer data
- Payment services
- Management, administrative, and operational functions
- Main-office, on-site operations
- Remote working environments
The scope statement establishes the proposed organizational and
operational boundaries for the ISMS. Any formal adoption should be
validated by the organization against its actual business activities,
locations, systems, interfaces, and applicable requirements.
Suggested Remediation Planning
The source document identifies gaps and relevant controls but does not
assign priorities, owners, or target dates. The following is a suggested
structure for a future remediation tracker, not a record of approved or
completed actions.
  Gap area                Suggested next step     Evidence to consider
  Asset inventory         Create and maintain a   Approved inventory,
                          centralized asset       asset ownership
                          inventory               records, review history

  Security awareness      Define a recurring      Training plan,
                          awareness and refresher attendance/completion
                          program                 records, awareness
                                                  materials

  Physical access         Formalize access to     Access authorization
                          critical equipment      records, review logs,
                          areas and periodic      access lists
                          reviews                 

  Role transitions        Define access-change    Role-change records,
                          and revocation steps    access review evidence,
                          for role changes        change tickets

  MFA                     Assess and improve MFA  System coverage report,
                          coverage for relevant   authentication
                          systems and accounts    policies, approved
                                              exception records
Suggested Tracking Fields
A practical remediation register could include:
- Finding ID
- Gap description
- Mapped ISO/IEC 27001:2022 control
- Risk rating and rationale
- Remediation action
- Accountable owner
- Target completion date
- Required evidence
- Status
- Residual-risk decision
- Validation or review date
Risk ratings, owners, deadlines, and statuses should be assigned by the
organization using its approved risk-assessment and risk-treatment
processes.
Expected Project Deliverables
Based on the supplied document, the project deliverables are:
- An Annex A gap-analysis table containing five identified security
  gaps.
- Control mappings to ISO/IEC 27001:2022 Annex A.
- Justifications explaining the relevance of each mapped control.
- A proposed ISMS scope statement aligned with Clause 4.3.
A remediation plan, risk register, Statement of Applicability,
control-testing results, and certification evidence are not included in
the supplied document and should not be treated as completed
deliverables.
Conclusion
The gap analysis identifies five areas for follow-up at Cartex
Technologies Ltd: asset inventory, continuing security awareness,
physical access to critical equipment areas, access-rights changes
following employee role transitions, and consistent MFA implementation.

Mapping these findings to relevant ISO/IEC 27001:2022 Annex A controls
gives the organization a structured basis for further assessment and
remediation planning. The proposed ISMS scope defines the
platform-related information assets, systems, infrastructure, business
processes, and on-site and remote functions intended to be covered.

The next step would be for the organization to validate the findings,
assess risks, assign remediation responsibilities, define target dates,
and retain evidence demonstrating the implementation and effectiveness
of selected controls.
Framework References
- ISO/IEC 27001:2022 --- Information security management systems
  requirements, including Clause 4.3 for determining the scope of the
  ISMS.
- ISO/IEC 27001:2022 Annex A --- The control references mapped in
  this analysis: A.5.9, A.6.3, A.7.2, A.5.18, and A.8.5.
