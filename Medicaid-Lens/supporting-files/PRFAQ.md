# PRFAQ: AWS Medicaid Well-Architected Lens

**AWS launches Medicaid Well-Architected Lens to streamline CMS certification readiness for state Medicaid agencies**
*New customized framework helps state agencies accelerate Medicaid Management Information System (MMIS) certification and ensure compliance with federal standards while leveraging cloud benefits*

**SEATTLE – December 15, 2025** – Today, Amazon Web Services (AWS) announced the launch of its Medicaid Well-Architected Lens, designed specifically to help state Medicaid agencies assess their cloud-based Medicaid Management Information Systems (MMIS) for Centers for Medicare & Medicaid Services (CMS) certification readiness. This specialized framework extends the AWS Well-Architected Framework to address the unique compliance, security, and operational needs of Medicaid systems, enabling agencies to accelerate certification processes while increasing operational efficiency and reliability.

State Medicaid agencies across the United States are increasingly modernizing their systems by moving to cloud infrastructure, but face significant challenges meeting the stringent CMS certification requirements that determine federal funding eligibility. The new AWS Medicaid Well-Architected Lens provides agencies with a comprehensive evaluation framework that maps directly to CMS certification criteria while incorporating AWS best practices across the six pillars of the Well-Architected Framework: operational excellence, security, reliability, performance efficiency, cost optimization, and sustainability.

Previously, Medicaid agencies struggled with lengthy certification processes, often taking 18-24 months to complete, with no standardized approach for cloud-based implementations. Technical teams had to manually translate CMS requirements into cloud architecture decisions, creating inconsistency across implementations and introducing compliance risks. Certification readiness assessments were typically conducted late in the implementation cycle, when architectural changes were most costly and time-consuming.

"Our teams were spending countless hours trying to interpret how CMS certification requirements translated to our AWS environment," said Maria Rodriguez, CIO at a large state Medicaid agency. "We had to create our own mapping between certification criteria and our cloud architecture, then develop custom controls and documentation processes. Without clear guidelines specific to cloud implementations, we risked delayed certification and potential funding impacts." The AWS Medicaid Well-Architected Lens solves these challenges through a structured approach that includes a comprehensive question framework with over 100 Medicaid-specific best practices aligned to CMS certification requirements. The lens provides detailed implementation guidance for each WAFR pillar, allowing agencies to conduct ongoing self-assessments throughout their implementation lifecycle.

"The Medicaid Well-Architected Lens has transformed our certification preparation," said James Williams, MMIS Program Director for another state Medicaid agency that participated in the preview program. "What previously took our team months of preparation now takes weeks. We identified certification gaps early in our implementation timeline when they were easier and less expensive to address. The clear mapping between AWS architecture decisions and CMS certification criteria gave our team confidence we were building a compliant system from the ground up."

The lens includes specialized guidance across all six Well-Architected Framework pillars. For example, the Security pillar incorporates specific controls for protecting Personally Identifiable Information (PII) and Protected Health Information (PHI) according to both HIPAA and CMS standards. The Operational Excellence pillar focuses on automation and observability approaches that satisfy CMS system monitoring requirements while reducing operational overhead.

"State Medicaid agencies are entrusted with managing critical healthcare services for millions of Americans, and the systems supporting these services must meet rigorous federal standards," said Sarah Johnson, Director of Public Sector Health at AWS. "We developed the Medicaid Well-Architected Lens to help agencies confidently build and operate cloud-based Medicaid systems that not only achieve certification but deliver better experiences for beneficiaries and providers."

The AWS Medicaid Well-Architected Lens is available starting today at no additional cost to AWS customers. Agencies can access the lens through the AWS Well-Architected Tool, documentation, and workshops delivered by AWS and AWS Partners specializing in healthcare and public sector implementations.

## Frequently Asked Questions

### What is the customer problem?

State Medicaid agencies struggle to efficiently navigate the CMS certification process for cloud-based Medicaid Management Information Systems, resulting in extended timelines, increased costs, and compliance risks. Our research with Medicaid agencies reveals three primary challenges:
First, agencies lack clear guidance mapping CMS certification requirements to cloud architecture decisions. In a survey of 15 state Medicaid IT leaders, 87% reported difficulties translating CMS criteria into AWS implementation choices, with architecture teams spending an average of 320 hours per module creating custom mappings and documentation approaches.
Second, certification preparation typically occurs late in the implementation cycle. Data from recent MMIS implementations shows that 73% of certification deficiencies are identified within 90 days of certification reviews, when architectural changes are up to 5x more expensive to implement than if identified earlier in the development cycle.
Third, agencies struggle to maintain continuous compliance as systems evolve. 64% of Medicaid agencies report challenges keeping cloud environments aligned with certification requirements over time, with an average of 8.3 compliance gaps introduced per quarterly release.
These challenges result in certification delays averaging 7.5 months across recent implementations, with associated federal matching funds impacted accordingly, and rework costs averaging $1.2M per implementation.

### How will you solve these problems?

The AWS Medicaid Well-Architected Lens solves these problems through a comprehensive framework that directly maps CMS certification requirements to AWS architecture best practices across six pillars:

1. **Operational Excellence**: Provides guidance on implementing CMS-compliant operational processes including incident management, change management, and system monitoring. Includes specific patterns for automated compliance reporting, operational metrics collection, and business continuity that satisfy CMS operational criteria.

2. **Security**: Offers detailed implementation patterns for securing PHI/PII data in accordance with both HIPAA and CMS requirements. Includes reference architectures for identity management, encryption, and access controls specifically tailored for Medicaid workflows and data sensitivity levels.

3. **Reliability**: Provides fault tolerance and disaster recovery patterns that meet CMS system availability requirements. Includes specific approaches for testing recovery processes, implementing active-active configurations, and ensuring service continuity during maintenance windows.

4. **Performance Efficiency**: Delivers specific guidance on meeting CMS performance criteria, including transaction processing times, batch processing windows, and peak load handling. Includes reference architectures for scaling MMIS components and optimizing database performance for Medicaid-specific workloads.

5. **Cost Optimization**: Provides strategies for optimizing cloud spending while maintaining compliance, including resource right-sizing, reserved instance planning, and cost allocation approaches that align with federal claiming models.

6. **Sustainability**: Introduces approaches to reduce environmental impact while maintaining compliance, including energy-efficient architecture patterns and carbon footprint reduction strategies.

The framework includes over 100 Medicaid-specific best practices in the form of lens questions, detailed implementation guidance with technical specifications, and an automated assessment tool that generates certification readiness reports. Agencies can conduct self-assessments throughout the implementation lifecycle to identify and address gaps early, rather than discovering issues during formal certification reviews.

### How will you measure success?

We will measure the success of the AWS Medicaid Well-Architected Lens through four key metrics:

1. **Certification Timeline Reduction**: Our primary goal is to reduce the average time to achieve CMS certification by 40% (from 18-24 months to 10-14 months) by enabling agencies to identify and address certification requirements earlier in the implementation process.

2. **Early Issue Detection**: Increase the percentage of certification-related issues identified in the design and early implementation phases (versus pre-certification review) from the current 27% to 80%, enabling more cost-effective remediation.

3. **Implementation Cost Efficiency**: Reduce the average implementation costs related to certification compliance and rework by 30%, from an average of $1.2M to $840K per implementation.

4. **Customer Satisfaction**: Achieve a 90% or higher satisfaction rate among state Medicaid agencies using the lens, as measured through customer surveys and feedback mechanisms.

### Who are the customers for this Medicaid Well-Architected Lens?

The primary customers for the AWS Medicaid Well-Architected Lens are:

1. **State Medicaid Agencies**: IT and program leadership responsible for implementing and certifying MMIS systems, including CIOs, CTOs, MMIS Program Directors, and Technical Architects.

2. **Medicaid System Integrators**: Consulting firms and technology partners who implement and operate Medicaid systems on behalf of state agencies.

3. **AWS Partners**: Consulting partners who specialize in healthcare and public sector implementations and need to ensure their solutions meet CMS certification requirements.

Secondary customers include CMS reviewers who can use the framework to standardize their evaluation approach for cloud-based implementations.

### How does the Medicaid Well-Architected Lens align with CMS certification requirements?

The Medicaid Well-Architected Lens directly maps to CMS certification requirements through a comprehensive crosswalk that connects each certification criterion to specific AWS architectural best practices. The lens organizes requirements across three dimensions:

1. **CMS Certification Checklist Items**: Each of the certification checklist items from the most recent CMS MMIS certification framework is mapped to specific AWS architectural decisions and implementations.

2. **MITA Business Processes**: The lens aligns with the Medicaid Information Technology Architecture (MITA) framework, helping agencies demonstrate MITA maturity level advancement through cloud adoption.

3. **Functional Modules**: The lens provides specialized guidance for each MMIS functional module (Eligibility & Enrollment, Claims Processing, Provider Management, etc.), recognizing the unique requirements and workflows of each area.

The mapping includes specific AWS service recommendations, security controls, operational processes, and documentation approaches that satisfy each certification requirement while leveraging cloud capabilities.

### What are the biggest risks, and how will you mitigate them?

We've identified four key risks and corresponding mitigation strategies:

1. **Risk**: CMS certification requirements evolve over time, potentially making lens guidance outdated. **Mitigation**: We've established a quarterly review process with CMS stakeholders to ensure the lens remains aligned with current certification requirements. Updates to the lens will be released within 30 days of any significant CMS guidance changes.

2. **Risk**: Agencies have varying levels of cloud maturity, making some guidance inapplicable to less mature environments. **Mitigation**: The lens includes implementation paths for different cloud maturity levels, with "foundation," "intermediate," and "advanced" guidance for each requirement.

3. **Risk**: Some agencies operate hybrid environments with both legacy and cloud components. **Mitigation**: The lens includes specific sections on integration patterns between cloud and on-premises systems, ensuring hybrid environments can still benefit from the guidance.

4. **Risk**: Agencies may view the lens as replacing rather than complementing formal CMS reviews. **Mitigation**: Clear documentation states that the lens is a preparatory tool, not a replacement for formal CMS certification processes. We've included guidance on how to use lens outputs as inputs to formal certification reviews.

### What were the alternatives considered?

We considered several alternative approaches before developing the Medicaid Well-Architected Lens:

1. **Enhanced general healthcare guidance**: We considered expanding our healthcare industry guidance with specific Medicaid sections. This approach proved insufficient as it failed to address the specific regulatory requirements of CMS certification.

2. **Partner-led solutions**: We explored having consulting partners develop proprietary frameworks. This approach would have created inconsistency across implementations and limited access to smaller agencies with lower consulting budgets.

3. **Documentation-only approach**: We considered developing detailed documentation without integrating into the Well-Architected Tool. While simpler to produce, this approach would have lacked the interactive assessment capabilities that enable ongoing compliance evaluation.

4. **Generic compliance lens**: We considered a broader government compliance lens covering multiple regulatory frameworks. This approach would have provided insufficient depth on Medicaid-specific requirements.

The dedicated Medicaid Well-Architected Lens provides the most comprehensive solution by combining specialized guidance with interactive assessment capabilities and integration with existing AWS tools.

### How will this lens be kept current with CMS requirements?

The Medicaid Well-Architected Lens will be maintained through a structured governance process:

1. **CMS Engagement**: We've established a quarterly engagement process with CMS stakeholders to understand upcoming guidance changes and certification requirement updates.
2. **User Feedback Loop**: A dedicated feedback mechanism allows Medicaid agencies and partners to suggest improvements and report gaps in the guidance.
3. **Automated Monitoring**: We monitor CMS publications and guidance documents using automated tools to flag potential impacts to lens guidance.
4. **Version Control**: The lens follows a versioned release approach, with major updates (aligning to significant CMS guidance changes) and minor updates (incorporating feedback and refinements).
5. **Partner Contributions**: Selected AWS Partners with Medicaid expertise participate in a review board that evaluates and contributes to lens updates.

Updates are prioritized based on potential certification impact, with critical updates released within 30 days of CMS guidance changes and routine updates consolidated into quarterly releases.

### What technical resources and tools support this lens?

The Medicaid Well-Architected Lens is supported by a comprehensive set of resources:

1. **AWS Well-Architected Tool Integration**: The lens is fully integrated into the AWS Well-Architected Tool, allowing agencies to conduct assessments, track improvements, and generate reports.
2. **Reference Architectures**: A library of Medicaid-specific reference architectures addressing common MMIS modules and functions, each mapped to relevant certification criteria.
3. **Implementation Guides**: Detailed technical guides explaining how to implement specific patterns that satisfy certification requirements.
4. **Compliance Automation Templates**: CloudFormation templates, AWS Config rules, and Security Hub controls that automate compliance verification for key certification requirements.
5. **Documentation Templates**: Pre-built templates for certification evidence documentation that agencies can customize for their implementations.
6. **Workshop Materials**: Facilitation guides and materials for conducting Medicaid Well-Architected reviews with technical teams.

These resources are available through the AWS Well-Architected Tool, AWS Documentation, AWS Workshops, and the AWS Solutions Library.

### How will you roll this out to customers?

The Medicaid Well-Architected Lens will be rolled out through a phased approach:
**Phase 1 (Launch)**:

* Lens available in the AWS Well-Architected Tool
* Documentation and implementation guides published
* Initial reference architectures released
* Launch workshops with 5 pilot state agencies

**Phase 2 (90 days post-launch)**:

* Partner enablement program launched
* Additional reference architectures published
* First round of customer feedback incorporated
* Technical deep-dive webinar series

**Phase 3 (180 days post-launch)**:

* Expansion of automation templates
* Advanced implementation patterns added
* Case studies from early adopters published
* Integration with AWS Control Tower for governance

**Phase 4 (12 months post-launch)**:

* Comprehensive revision based on first-year learnings
* Expanded integration with AWS Audit Manager
* Addition of specialized guidance for emerging modules (e.g., third-party liability, program integrity)

The rollout includes dedicated support for early adopters, with AWS Solutions Architects providing guidance on applying the lens to existing implementations.

### Who will you collaborate with to achieve this?

We will collaborate with multiple stakeholders to ensure the success of the Medicaid Well-Architected Lens:

1. **CMS**: Close engagement with CMS certification teams to ensure alignment with current requirements and future direction.
2. **State Medicaid Agencies**: Ongoing feedback and validation from agencies at different stages of cloud adoption and certification.
3. **AWS Partner Network**: Collaboration with partners specializing in Medicaid implementations to validate patterns and contribute expertise.
4. **AWS Public Sector Team**: Coordination with account teams supporting Medicaid agencies to drive awareness and adoption.
5. **AWS Service Teams**: Engagement with relevant service teams to develop Medicaid-specific features and capabilities.
6. **Industry Bodies**: Alignment with organizations like NAMD (National Association of Medicaid Directors) and MESC (Medicaid Enterprise Systems Conference) to incorporate industry best practices.

We have established formal collaboration processes with each group, including regular review sessions, feedback mechanisms, and contribution opportunities.

### How does this accelerate cloud adoption for state Medicaid agencies?

The Medicaid Well-Architected Lens accelerates cloud adoption for state Medicaid agencies in four key ways:

1. **Reduced Certification Risk**: By providing clear guidance on how AWS services and architectures align with CMS requirements, the lens reduces the perceived risk of moving Medicaid systems to the cloud.
2. **Implementation Acceleration**: Pre-built patterns and reference architectures allow agencies to implement certified solutions faster, without reinventing compliance approaches for each implementation.
3. **Cost Efficiency**: Early identification of certification gaps reduces costly late-stage rework, making cloud adoption more economically viable for budget-constrained agencies.
4. **Knowledge Transfer**: Standardized guidance helps agencies build internal cloud expertise specific to Medicaid requirements, reducing dependency on consultants and accelerating self-sufficiency.

Early testing with five state Medicaid agencies showed an average 45% reduction in time spent on certification preparation activities and a 60% increase in confidence regarding cloud readiness for certification.

### How does the lens address the unique challenges of Medicaid systems?

The Medicaid Well-Architected Lens addresses unique Medicaid challenges through specialized guidance:

1. **Service Integration**: Provides patterns for integrating modular Medicaid components as mandated by CMS, including API standards, data exchange protocols, and interoperability approaches.
2. **Program Adaptability**: Incorporates guidance on building flexible systems that can adapt to frequent policy changes and waiver implementations without requiring recertification.
3. **Beneficiary Experience**: Includes specific guidance on meeting CMS requirements for beneficiary-facing systems, including accessibility standards and multi-channel service delivery.
4. **Legacy Integration**: Provides approaches for modernizing incrementally while maintaining integration with remaining legacy components.
5. **Specialized Data Handling**: Addresses unique Medicaid data requirements including claims processing formats, provider credentialing data, and beneficiary eligibility information.
6. **Funding Model Alignment**: Aligns cloud cost structures with the APD (Advance Planning Document) and federal claiming processes that govern Medicaid IT funding.

Each of these areas includes specialized questions, best practices, and implementation guidance that goes beyond generic healthcare or government compliance frameworks.
