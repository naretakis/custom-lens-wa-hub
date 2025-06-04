# Medicaid Provider Lens Updates Documentation

## Original Prompt

```
I am attempting to create a custom Medicaid WA Tool lens (see the main readme.md file in this repo for context of what that is). I have created a `Medicaid-Lens/supporting-files` folder with Medicaid provider system information. Your tasks is to review the `provider-management-outcomes.md` file and then use information within that file to update/revise the following files:
`sample-provider-enrollment.md`
`sample-provider-management.md`
`sample-provider-termination.md`
```

## Changes Made

I've updated all three sample files based on the information in the provider-management-outcomes.md file. Here's a summary of the changes made:

### 1. Sample Provider Enrollment (sample-provider-enrollment.md)
- Updated the capability area description to reference relevant CMS-Required outcomes (PM1, PM2-3, PM4, PM6, PM8-13)
- Added assessment questions related to revalidation, risk levels, and external verification
- Enhanced maturity level definitions to incorporate specific requirements for provider screening, revalidation, and risk-based assessment

### 2. Sample Provider Management (sample-provider-management.md)
- Changed the capability area from "Provider Enrollment" to "Provider Management"
- Updated the capability area description to focus on provider management and referenced relevant CMS-Required outcomes (PM14, PM16, PM17, PM19, PM20, PM21)
- Replaced assessment questions with ones focused on provider information maintenance, directory management, network adequacy, communications, fraud monitoring, and agreement management
- Updated maturity level definitions to address provider information management, provider directory functionality, network adequacy reporting, and provider communications

### 3. Sample Provider Termination (sample-provider-termination.md)
- Changed the capability area from "Provider Enrollment" to "Provider Termination"
- Updated the capability area description to focus on provider termination and referenced relevant CMS-Required outcomes (PM5, PM7, PM15, PM18)
- Replaced assessment questions with ones focused on termination management, appeals process, payment suspensions, information sharing, and termination tracking
- Updated maturity level definitions to address termination processes, appeals management, and information sharing with other programs

## CMS-Required Outcomes Mapping

The updates ensure that each file correctly reflects its specific capability area and incorporates the relevant CMS-Required outcomes from the provider-management-outcomes.md file:

### Provider Enrollment
- PM1: Application
- PM2-3: Screening
- PM4: Revalidation
- PM6: Reactivation
- PM8: Site Visits
- PM9: Background Checks
- PM10: External Systems Checks
- PM11: Risk Level Assignment
- PM12: Application Fees
- PM13: Moratoria

### Provider Management
- PM14: Network Adequacy
- PM16: Notices and Communications
- PM17: Fraud
- PM19: Agreements and Disclosures
- PM20: Change in Circumstances
- PM21: Directory

### Provider Termination
- PM5: Termination
- PM7: Appeal
- PM15: Sanctions and Terminations
- PM18: Payment Suspension

## Latest Update - Medicaid-Lens.json Creation

### Prompt
```
Your task is to create a v1 of a custom AWS WA Custom Lens for Medicaid. To do this, please review @workspace for context, and then examine the `Medicaid-Lens` folder wherein there is template version of `Medicaid-Lens.json`. Please use the files in the `supporting-files` folder for the Medicaid Provider system to create a v1 of the `Medicaid-Lens.json`
```

### Changes Made

Created the v1 of the Medicaid-Lens.json file for the AWS Well-Architected Custom Lens with the following structure:

1. **Overall Structure**:
   - Created a custom lens with three pillars representing the Provider capability areas: Provider Enrollment, Provider Management, and Provider Termination
   - Named the lens "Medicaid Provider Systems Lens" with an appropriate description

2. **Provider Enrollment Pillar**:
   - Created three key questions focused on enrollment efficiency, credential validation, and revalidation management
   - Each question includes three best practices as choices
   - Added risk rules to evaluate compliance levels
   - Aligned questions with CMS-Required outcomes (PM1, PM2-3, PM4, PM6, PM8-13)

3. **Provider Management Pillar**:
   - Created three key questions focused on information maintenance, provider directory, and network adequacy
   - Each question includes three best practices as choices
   - Added risk rules to evaluate compliance levels
   - Aligned questions with CMS-Required outcomes (PM14, PM16, PM17, PM19, PM20, PM21)

4. **Provider Termination Pillar**:
   - Created three key questions focused on termination management, appeals process, and information sharing
   - Each question includes three best practices as choices
   - Added risk rules to evaluate compliance levels
   - Aligned questions with CMS-Required outcomes (PM5, PM7, PM15, PM18)

Each question in the lens includes:
- Detailed descriptions explaining the importance of the topic
- Best practices as selectable choices
- Helpful resources with URLs to relevant regulations and guidance
- Improvement plans for each choice
- Risk rules to evaluate the overall risk level based on selected choices