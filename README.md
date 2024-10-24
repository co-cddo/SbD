Background
The Secure by Design (SbD) Artefact Library provides a centralised repository of proven solutions to common cyber security problems that support the implementation of SbD principles across government. The library is hosted on Github and provides essential resources for:
Guidance: Enabling teams, regardless of their cyber expertise, to embed security into project delivery by providing practical tools and frameworks.
Standardisation: Offering consistent approaches and best practices for addressing security risks across various departments.
Efficiency: Reducing duplication by reusing existing security solutions and materials.
It is an open repository, accessible to government, vendors and private sector. The resources are aimed mainly at technical and security architects, developers, DevSecOps, but could be useful to anyone in the digital delivery teams.
Purpose

The purpose of this document is to outline the management processes of the Secure by Design artefacts library hosted on the Cabinet Office Github. This includes key steps in relation to content management, triage and approvals, feedback and improvements, monitoring & reporting, and user access and permissions.
Types of artefacts

The table below provides a brief description of the various artefact types available for access or request through the artefact library. This list will be revisited and updated on regular intervals. 

Type
Description/Comments
Best Practice Guidance
Widely accepted guidelines or standards that represent the most efficient and effective way to accomplish a task or achieve a specific outcome.
Checklists
Lists of items or tasks to be completed, often used to ensure that all necessary steps in a process are followed.
Security Blueprints
High-level, strategic framework that guides the design, implementation and management of security measures within an organisation. It provides a high-level overview of security goals, principles, and architectures.
Security Designs
High-level considerations / decisions about how security will be integrated into the entire system. This includes the selection of appropriate security controls (like firewalls, encryption, and authentication systems), how these controls interact, and how they fit into the overall system architecture.
Security Documentation
Written materials related to the security measures, policies, procedures, and protocols of a system or organisation.
Security Patterns
Reusable solution to a common security problem within a specific context in software or system design. Security patterns are like design patterns, providing developers with tested solutions for specific security challenges they might face during software development. They are typically focused on a single aspect of security and are detailed. 
Security Requirements
Criteria that a system must meet to ensure its protection from threats and vulnerabilities.
Software Code
Instructions and statements in a programming language that define the functionality and behaviour of a software application.
Templates
Pre-formatted documents or forms that provide a consistent structure for capturing and presenting information.
Threat Models
Representations of potential security threats and vulnerabilities, used to identify and prioritise risks to a system.
Use Cases
Scenarios in which a system or application is used, detailing the interactions between users and the system to achieve a particular goal.


Artefact development process 

The following diagram outlines the end-to-end process for the development of an artefact in GitHub, showcasing the various stages from request to publication. It visually represents the collaborative and agile nature of artefact development using GitHub’s version control system. Refer to Annex 1 for Github terms and Annex 2 for the detailed steps in Github.

Principles
Short increments periods for contributors to avoid clashes 


Request 
This sub-process outlines the steps for submitting a request to either create a new artefact or modify an existing one within the GitHub repository. 
The process begins when a Requester identifies the need for a new artefact or a change to an existing artefact and creates a new 'issue' on GitHub. The Requester uses the appropriate template, specific to the type of artefact being requested, to ensure all necessary details are captured. This step ensures a standardised and efficient way to manage requests, enabling the repository maintainers and approvers to effectively review and prioritise the work. 

Review 
This sub-process includes the steps for reviewing and approving new requests submitted via GitHub. 
Once a request has been initiated and submitted as a GitHub issue, a notification is automatically sent to users that are ‘watching’ the SbD artefact library repository. This will include all SbD team members that have a responsibility of Collaborator in the library. The notification will trigger the review process and the issue will be assigned to a Triager. The Requester will receive an acknowledgment of their submission within 3 working days, and a final decision—whether the request is accepted or rejected—within 10 working days.
During the review, a Triager evaluates the request based on predefined criteria and procedures to determine whether the artefact should be created or changed. 
The process may also involve tagging relevant Contributors for feedback and suggestions, ensuring a collaborative and comprehensive review before final approval. 
Following the Triager's assessment, an Approver makes the final decision on whether to move forward with the creation or modification of the artefact.

Create (or change)
This sub-process outlines the steps involved in the creation or modification of artefacts.
Once a request has been reviewed and approved, the Triager assigns the responsibility for developing or amending the artefact to a Contributor. The Contributors develop the artefact specification and are tasked with drafting or updating the artefact based on the specific requirements of the request. 
Following the initial creation or amendment, all artefacts must undergo a peer review process to ensure quality, accuracy, and compliance with agreed document specification / standards. During this review, Collaborators facilitate peer feedback, ensuring that the artefact is refined and aligned with best practices.

Integrate (Beta)
This sub-process outlines the steps required for integrating the artefact into the artefact library once it has passed through community peer review, testing, and final approval. 
The first step is the formal announcement of the artefact to the community for review. The Collaborator makes the announcement. This provides stakeholders with visibility of the newly added artefact and invites further feedback. 
Next, feedback is gathered from the community, which may involve additional refinement or updates to the artefact to ensure it continues to meet the needs of the users. 
After incorporating any necessary adjustments, the artefact is tagged with appropriate metadata, such as platform-specific tags (e.g., AWS, Azure) or cybersecurity frameworks (e.g. CAF, NIST, ISO), allowing users to quickly find artefacts relevant to their requirements. The Collaborator plays a critical role in facilitating these tasks, ensuring that all relevant documentation and release notes are updated accordingly. 
Finally, the artefact must be formally approved by the designated Approver before it can be published in the library and made available for use by the wider community.


Publish (Live)
This sub-process outlines the steps required for publishing the artefact in the library, specifically into the main branch for broad access and use and an announcement is made to the community.
Throughout this process, the Collaborator ensures that the artefact is properly categorised, tagged with relevant metadata (e.g., related to specific platforms like AWS, security standards, or frameworks), and that its documentation is fully up-to-date. The Maintainer may also assist in ongoing management of the artefact, ensuring it remains available and that any future updates or revisions are promptly applied.
