# Secure by Design Artefact Library

> [!IMPORTANT]
> Do not enter any sensitive or secret information such as passwords or PII into the chat or publicly available artefacts. This library is publicly visible.

> [!NOTE]
> This library is currently in alpha phase. Contributions from UK government security architects are very welcome - please reach out to the Secure by Design security architecture team.

## Background
The Secure by Design (SbD) Artefact Library provides a centralised repository of proven solutions to common cyber security problems that support the implementation of SbD principles across government. The library is hosted on GitHub and provides essential resources for:

**Guidance:** Enabling teams, regardless of their cyber expertise, to embed security into project delivery by providing practical tools and frameworks.

**Standardisation:** Offering consistent approaches and best practices for addressing security risks across various departments.

**Efficiency:** Reducing duplication by reusing existing security solutions and materials.
It is an open repository, accessible to government, vendors and private sector. The resources are aimed mainly at technical and security architects, developers and DevSecOps, but could be useful to anyone in the digital delivery teams.

## Purpose

The purpose of this document is to outline the management processes of the Secure by Design artefacts library hosted on the Cabinet Office GitHub. This includes key steps relating to:

- content management
- triage and approvals
- feedback and improvements
- monitoring and reporting
- user access and permissions

## Type of available artefacts

The table below describes the artefact types you can access or request through the artefact library. We'll revisit and update this list regularly. 

If you cannot find what you need, you can ask for a new artefact to be created.


| Artefact category| Description | 
| :---         | :---           | 
| Best practice guidance| Actionable advice based on industry standards and proven methodologies. This helps teams implement security effectively to accomplish a task or achieve a specific outcome. | 
| Checklists| Structured lists of key tasks or requirements designed to guide teams through essential security steps. | 
| Security blueprints| High-level and strategic frameworks that provide pre-defined solutions for implementing security controls within applications and infrastructure. These blueprints are designed to be reusable and adaptable, helping teams integrate secure practices efficiently and consistently. | 
| Security designs| Detailed architectural diagrams and documentation that outline how to integrate security measures within a system's overall structure. Security designs focus on proactively embedding security controls at each layer of the system. This helps make sure security is foundational rather than an afterthought. Designs are more concrete and focus on the specific implementation of security measures, including the configuration and integration of various components. | 
| Security documentation| Written materials related to the security measures, policies, procedures, and protocols of a system or organisation. | 
| Security patterns| Reusable solution to a common security problem within a specific context in software or system design. Security patterns are comparable to design patterns. They provide developers with validated solutions for specific security challenges they might face during software development. They typically focus on a single aspect of security and the relationship between different components or processes in a security context. | 
| Security requirements| Specific and measurable criteria that a system or application must meet to be considered secure. These requirements outline the necessary security controls and protocols to protect against threats and vulnerabilities, ensuring that the system aligns with organisational policies and industry standards. | 
| Software code| Instructions and statements in a programming language that define the functionality and behaviour of a software application. | 
| Templates| Pre-formatted documents or forms that provide a consistent structure for capturing and presenting information.| 
| Threat models| Comprehensive views of  security threats and vulnerabilities, used to identify and prioritise potential security threats and vulnerabilities within a system, application or network. | 
| Use cases| Scenario-based descriptions of how a system or application is expected to perform in various real-world situations, highlighting specific actions, interactions or workflows. Use cases help identify security needs by demonstrating how users (or other systems) interact with a system, providing insight into required security controls and potential vulnerabilities. | 



## Artefact development process 

To create a new artefact or modify an existing one within the GitHub repository, we follow 5 steps: 

- request
- review
- create or change
- integrate
- publish

### Request 
The process begins when a Requester identifies the need for a new artefact or a change to an existing artefact and creates a new 'issue' on GitHub. The Requester uses a template that's appropriate to the type of artefact being requested. This ensures all necessary details are captured. 

This step means we have a standardised and efficient way to manage requests. It helps the repository maintainers and approvers effectively review and prioritise the work. 

### Review 
Once a request has been initiated and submitted as a GitHub issue, users who are ‘watching’ the SbD artefact library repository receive a notification. This includes all SbD team members who are Collaborators in the library. The notification triggers the review process and the issue will be assigned to a Triager. 

The Requester will receive an acknowledgment of their submission within 3 working days. They'll receive a final decision, whether the request is accepted or rejected, within 10 working days.

During the review, a Triager evaluates the request based on predefined criteria and procedures to determine whether the artefact should be created or changed. 
The process may also involve tagging relevant Contributors for feedback and suggestions. This ensures a collaborative and comprehensive review before final approval. 

Following the Triager's assessment, an Approver makes the final decision on whether to move forward with the creation or modification of the artefact.

### Create or change
Once a request has been reviewed and approved, the Triager assigns the responsibility for developing or amending the artefact to a Contributor. The Contributors develop the artefact specification and are tasked with drafting or updating the artefact based on the specific requirements of the request. 

Following the initial creation or amendment, all artefacts must undergo a peer review process to ensure quality, accuracy, and compliance with agreed document specification / standards. During this review, Collaborators invite peer feedback, ensuring that the artefact is refined and aligned with best practices.

### Integrate (beta)
Once the artefact has passed through community peer review, testing and final approval, it can be integrated into the library. 

Firstly, the Collaborator will notify the community that the artefact is ready for review. This gives stakeholders visibility of the newly-added artefact and invites further feedback. 

Next, feedback is gathered from the community, which may involve additional refinement or updates to the artefact to make sure it meets user needs. 

After incorporating any necessary adjustments, the artefact is tagged with appropriate metadata, such as platform-specific tags (for example, AWS or Azure) or cybersecurity frameworks (for example, CAF, NIST or ISO), allowing users to quickly find relevant artefacts. 

The Collaborator plays a critical role in these tasks, ensuring that all relevant documentation and release notes are updated accordingly. 

Lastly, the artefact must be formally approved by the designated Approver. Once that's happened, it can be published in the library and made available for use by the wider community.


### Publish (live)
Finally, the artefact will be published into the main branch for broad access and use, and an announcement is made to the community.

Throughout this process, the Collaborator makes sure that the artefact is properly categorised, tagged with relevant metadata (for example, related to specific platforms like AWS, security standards, or frameworks), and that its documentation is fully up-to-date. The Maintainer may also assist in ongoing management of the artefact, ensuring it remains available and that any future updates or revisions are promptly applied.



**This flowchart shows the key steps of the artefact creation process.**

![Screenshot of the process map.](https://github.com/co-cddo/SbD/blob/Main/AL%20Flow.png)

