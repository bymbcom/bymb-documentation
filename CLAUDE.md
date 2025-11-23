# CLAUDE.md - AI Assistant Guide for BY MB Documentation Repository

**Document Version:** v1.0
**Date:** November 23, 2025
**Purpose:** Comprehensive guide for AI assistants working with the BY MB Knowledge Center
**Repository:** bymb-documentation

---

## Repository Overview

### **What This Repository Is**
The BY MB Knowledge Center is a comprehensive documentation system for BY MB Consultancy, a Bahrain-based technology consultancy specializing in:
- Smart home and office automation
- Security and surveillance systems
- Networking and digital transformation
- Data analytics and business intelligence
- AI-powered customer service

This repository serves as the **knowledge foundation** for AI agents providing intelligent customer service, technical support, and business operations.

### **Primary Objectives**
1. **AI-Optimized Knowledge Management** - Structured documentation for AI consumption
2. **Customer Service Excellence** - Accurate, consistent information for customer interactions
3. **Quality Assurance** - Automated content review and classification
4. **Security & Privacy** - Proper separation of public and confidential information

---

## Repository Structure

### **Directory Organization**

```
bymb-documentation/
├── AI_Roles/                    # AI agent role definitions and behavior specs
├── Approval_Workflow/           # Document approval and review processes
├── Company_Information/         # Company profiles, team directory, business info
├── Content_Classification_Status.md  # Security status and classification tracking
├── FAQ/                         # Customer support FAQs across all service areas
├── Knowledge_Center_Status_Dashboard.md  # Project progress and metrics
├── Policies/                    # Organizational policies and procedures
├── Quality_Assurance/           # QA framework, classification guidelines, metrics
├── README.md                    # Public-facing knowledge center overview
├── Services/                    # Service documentation and packages
├── Technical_Documentation/     # Installation guides, troubleshooting, system requirements
├── index.md                     # Internal knowledge center overview
└── logo/                        # Brand assets
```

### **Key Directories Explained**

#### **AI_Roles/** - AI Agent Definitions
Contains comprehensive role definitions for AI agents:
- `AI_Roles_OperationsDirector_v1.0_20250524.md` - Strategic oversight agent
- `AI_Roles_SupportBot_v1.0_20250524.md` - First-line customer support
- `AI_Roles_TechBot_v1.0_20250524.md` - Technical support specialist
- `AI_Roles_OdooBot_v1.0_20250524.md` - ERP integration agent
- `AI_Roles_QualityAssuranceAgent_v1.0_20250610.md` - Content quality reviewer

**Usage:** Review these files to understand agent capabilities, responsibilities, and coordination protocols.

#### **Quality_Assurance/** - QA System
Contains the comprehensive quality assurance framework:
- `QA_Framework_v1.0_20250610.md` - Complete QA process and standards
- `Content_Classification_Guidelines.md` - Security classification rules
- `Quality_Metrics_Dashboard.md` - Performance tracking
- `Quality_Review_Templates/` - Standardized review reports

**Critical:** All content must pass QA review before publication.

#### **Services/** - Service Documentation
Organized by service category:
- `Analytics_Business_Intelligence/` - Data analytics, Power BI, AI automation
- `Networking_Digital_Transformation/` - Cloud, networking, modernization
- `Smart_Solutions/` - Home automation, security systems
- Service package references and catalogs

**Note:** Main branch contains public-safe versions without detailed pricing.

#### **Technical_Documentation/** - Technical Guides
Customer-facing technical documentation:
- Installation guides (CCTV, network, smart home, security)
- Troubleshooting guides (by system type)
- System requirements
- General technical guidance (no proprietary methods)

---

## Critical Naming Conventions

### **Document Naming Standard**
All documents follow this strict pattern:
```
[Category]_[Subcategory]_[Description]_v[Version]_[Date].md
```

**Examples:**
- `Services_SmartSolutions_HomeAutomation_v1.2_20250422.md`
- `AI_Roles_TechBot_v1.0_20250524.md`
- `Company_Information_Profile_English_v1.1_20250422.md`

**Components:**
- **Category:** Main classification (Services, AI_Roles, Policies, etc.)
- **Subcategory:** Secondary classification (optional)
- **Description:** Clear, descriptive name
- **Version:** v[Major].[Minor] or v[Major].[Minor].[Patch]
- **Date:** YYYYMMDD format

### **Version Numbering**
- **Major version (X.0):** Significant content changes, restructuring
- **Minor version (X.X):** Content additions, improvements
- **Patch version (X.X.X):** Corrections, typos, minor fixes

**Version History:** Must be documented in each file's version history table.

---

## AI Markers - Essential for AI Assistants

### **What Are AI Markers?**
Special markdown tags that guide AI behavior and decision-making. These are **critical** for proper AI operation.

### **The Four AI Markers**

#### **[AI-PRIORITY]** - Essential Information
Marks critical information that AI must prioritize in responses.

**Example:**
```markdown
[AI-PRIORITY]
- Service offerings overview
- Core company capabilities
- Contact methods for inquiries
```

**Usage:** Always reference this information first when answering related queries.

#### **[AI-CAUTION]** - Sensitive Content Handling
Indicates information requiring careful, nuanced handling.

**Example:**
```markdown
[AI-CAUTION]
Client contracts may restrict information sharing. Always verify confidentiality
requirements before discussing specific project details.
```

**Usage:** Apply extra validation and context checking before using this information.

#### **[AI-EXAMPLE]** - Reference for Responses
Provides examples AI can use in responses or for learning patterns.

**Example:**
```markdown
[AI-EXAMPLE]
When discussing service timelines:
"A typical smart home installation takes 2-3 days for a 3-bedroom villa,
including consultation, installation, testing, and training."
```

**Usage:** Use these examples as templates for similar customer queries.

#### **[AI-ESCALATE]** - Human Intervention Required
Marks topics that require escalation to human experts.

**Example:**
```markdown
[AI-ESCALATE]
Pricing negotiations, custom enterprise solutions, and contractual terms
require human sales team involvement.
```

**Usage:** Route these queries to appropriate human team members immediately.

---

## Content Classification System

### **Critical Security Framework**
All content is classified to protect confidential business information while enabling public marketing.

### **Classification Categories**

#### **🌐 PUBLIC (Main Branch)**
Safe for public distribution on websites, marketing materials, and customer-facing documentation.

**Characteristics:**
- General service descriptions
- Public methodology overviews
- Industry best practices
- General troubleshooting guides
- Company contact information
- Public certifications

**Location:** Main branch - safe for any public use

#### **🔒 CONFIDENTIAL (Protected Branch)**
Information restricted to internal use only.

**Characteristics:**
- Specific client names and project details
- Detailed pricing structures and profit margins
- Proprietary methodologies and trade secrets
- Team member personal information
- Vendor-specific negotiated rates
- Internal operational procedures
- AI system operational details

**Location:** Confidential branch - never expose publicly

#### **🔄 MIXED**
Documents containing both public and confidential information.

**Handling:** Create separate versions or sanitize content for public use.

#### **❓ NEEDS REVIEW**
Information requiring business decision regarding classification.

**Action:** Escalate to human reviewers for classification decision.

### **Classification Decision Matrix**

| Content Type | Public? | Example |
|--------------|---------|---------|
| Service overview | ✅ YES | "We provide CCTV installation services" |
| Specific pricing | ❌ NO | "Installation costs BHD 500" |
| General process | ✅ YES | "We start with a free consultation" |
| Client names | ❌ NO | "Completed project for ABC Corp" |
| Contact info (public) | ✅ YES | "Email: info@by-mb.com" |
| Personal contacts | ❌ NO | "John's mobile: +973..." |
| Industry standards | ✅ YES | "Cat6 cable specifications" |
| Vendor rates | ❌ NO | "15% discount from supplier X" |

---

## Quality Assurance Process

### **100-Point Quality Scoring System**
Every document is evaluated across five categories:

#### **1. Template Compliance (20 points)**
- Complete structure and formatting
- Required sections properly populated
- Metadata accuracy and completeness
- File naming convention adherence

#### **2. Technical Accuracy (25 points)**
- Factual correctness and current information
- Industry standards compliance
- Practical applicability
- Cross-reference accuracy

#### **3. Content Quality (20 points)**
- Clarity, readability, professional presentation
- Complete topic coverage
- Appropriate examples and context
- Effective use of AI markers

#### **4. Integration & Standards (15 points)**
- Style guide consistency
- Brand alignment and tone
- Cross-reference functionality
- Accessibility considerations

#### **5. Content Classification & Security (20 points)**
- Proper privacy level identification
- No confidential information in public content
- Appropriate business sensitivity handling
- Security risk assessment accuracy

### **Quality Thresholds**

| Score | Status | Action Required |
|-------|--------|-----------------|
| **95-100** | ✅ APPROVED | Minimal validation, proceed to publication |
| **85-94** | ⚠️ MINOR REVISIONS | Quick fixes needed before approval |
| **70-84** | 🔄 MAJOR REVISIONS | Significant improvements required |
| **<70** | ❌ REJECTED | Complete rework necessary |

### **QA Review Process**
1. **Document Submission** - Author submits using approved template
2. **AI QA Review** - Automated 15-minute comprehensive assessment
3. **Quality Scoring** - 100-point evaluation across all categories
4. **Report Generation** - Detailed feedback with specific action items
5. **Human Review** - Final validation based on QA score
6. **Publication** - Approved content published to knowledge center

---

## Document Metadata Requirements

### **Required Metadata (In Every Document)**
Every document MUST include:

```markdown
# Document Title

**Document ID:** [Category]_[Subcategory]_[Description]_v[Version]_[Date]
**Author:** [Author name or team]
**Last Updated:** [Date in format: Month DD, YYYY]
**Version:** [X.Y or X.Y.Z]
**Language:** [English/Arabic]
**Review Date:** [Next review date]
**Keywords:** [Comma-separated relevant keywords]
**Category:** [Primary category]
**Status:** [Active/Draft/Archived]
```

### **Optional But Recommended**
- **Related Documents:** Links to associated documentation
- **Supersedes:** Previous version(s) replaced by this document
- **Audience:** Target audience (customers, internal, technical, etc.)
- **Approval History:** Approval chain and dates

---

## Approval Workflow

### **Enhanced Approval Process with QA Integration**

```
[Content Creation] → [Self-Review] → [AI QA Review] → [Human Approval] → [Publication]
     (2 hours)         (15 min)         (15 min)          (5 min)        (Complete)
```

### **Approval Levels**

#### **Level 1: Basic Content (1-2 hours)**
- Content Types: FAQs, minor updates, general information
- Process: Self-Review → AI QA → Content Manager Approval
- Timeline: 2 hours maximum

#### **Level 2: Technical Content (2-3 hours)**
- Content Types: Technical specifications, troubleshooting guides
- Process: Self-Review → AI QA → Technical Lead → Content Manager
- Timeline: 3 hours maximum

#### **Level 3: Policy & Strategic Content (4-6 hours)**
- Content Types: Policies, strategic documents, compliance materials
- Process: Self-Review → AI QA → Subject Expert → Department Head → Executive
- Timeline: 6 hours maximum

#### **Level 4: Emergency Updates (30 minutes)**
- Content Types: Critical updates, security alerts, urgent corrections
- Process: Immediate AI QA → Emergency Team Approval → Immediate Publication
- Timeline: 30 minutes maximum

---

## Git Workflow & Branch Strategy

### **Branch Structure**

#### **main** - Public-Safe Content
All content on the main branch is:
- ✅ Safe for public websites and marketing
- ✅ Free of confidential information
- ✅ Free of personal data
- ✅ Free of specific pricing details
- ✅ Optimized for SEO and customer engagement

**Usage:** Use exclusively for public-facing applications.

#### **confidential-content** - Protected Information
Contains:
- 🔒 Complete original documentation with all details
- 🔒 Specific pricing and financial information
- 🔒 Personal contact information
- 🔒 Internal operational procedures
- 🔒 AI system documentation with operational details

**Usage:** Internal operations, sales teams, development only.

### **Branch Usage Guidelines for AI Assistants**

**When working with documentation:**
1. ✅ **DO** assume you're on the main branch (public-safe content)
2. ✅ **DO** reference only information present in main branch files
3. ❌ **DO NOT** reference pricing details or confidential information
4. ❌ **DO NOT** assume information from confidential branch is available
5. ✅ **DO** direct users to "contact for pricing" for cost inquiries

---

## Working with This Repository

### **For Documentation Review Tasks**

#### **When Reading Documentation:**
1. **Check AI markers** - Identify [AI-PRIORITY], [AI-CAUTION], [AI-EXAMPLE], [AI-ESCALATE]
2. **Verify classification** - Ensure no confidential information in public docs
3. **Validate metadata** - Check all required metadata is present and accurate
4. **Review structure** - Confirm document follows template standards
5. **Check references** - Validate all cross-references and links work

#### **When Creating Documentation:**
1. **Use approved templates** - Refer to Quality_Assurance/templates
2. **Include AI markers** - Add appropriate markers for AI guidance
3. **Complete metadata** - Fill all required metadata fields
4. **Self-classify** - Determine PUBLIC/CONFIDENTIAL classification
5. **Self-review** - Check against QA criteria before submission

### **For Content Quality Assessment**

#### **Quality Review Checklist:**
- [ ] Document uses approved template structure
- [ ] All required metadata fields completed
- [ ] File naming convention followed correctly
- [ ] AI markers used appropriately
- [ ] No confidential information in public documents
- [ ] Technical accuracy verified
- [ ] Writing is clear, professional, and consistent
- [ ] Cross-references are accurate and functional
- [ ] Examples are relevant and helpful
- [ ] Document serves its intended purpose

#### **Security Classification Checklist:**
- [ ] No specific client names or project details
- [ ] No exact pricing, costs, or profit margins
- [ ] No personal contact information (phone/email)
- [ ] No vendor-specific negotiated rates
- [ ] No proprietary methodologies or trade secrets
- [ ] No internal strategic information
- [ ] No system vulnerabilities or weaknesses

### **For Content Updates**

#### **Update Process:**
1. **Identify need** - Determine what requires updating
2. **Check current version** - Read existing document completely
3. **Determine impact** - Assess scope of changes (major/minor/patch)
4. **Update content** - Make necessary modifications
5. **Increment version** - Update version number appropriately
6. **Update metadata** - Change date, version, add to version history
7. **Update version history table** - Document what changed
8. **Submit for QA** - Follow approval workflow

#### **Version History Table Format:**
```markdown
## Version History
| Version | Date       | Changes                    | Author          |
|---------|------------|----------------------------|-----------------|
| 1.1     | 2025-11-23 | Added troubleshooting section | BY MB Tech Team |
| 1.0     | 2025-06-10 | Initial document creation  | BY MB Team      |
```

---

## Common AI Assistant Scenarios

### **Scenario 1: Customer Service Query**

**Customer asks:** "What smart home services do you offer?"

**AI Assistant should:**
1. Reference `Services/Professional_Services_Overview_v2.0_20250610.md`
2. Look for [AI-PRIORITY] sections
3. Provide overview of smart home automation services
4. Mention free consultation offering
5. Provide contact information for next steps

**Avoid:**
- Providing specific pricing (not in public docs)
- Making commitments beyond documented services
- Sharing client project details

### **Scenario 2: Technical Support Request**

**Customer asks:** "My CCTV camera isn't recording properly"

**AI Assistant should:**
1. Reference `Technical_Documentation/CCTV_Troubleshooting_Guide_v1.0_20250610.md`
2. Provide general troubleshooting steps
3. Check for [AI-ESCALATE] markers for complex issues
4. Offer to connect with technical team if needed

**Avoid:**
- Guessing at solutions not in documentation
- Providing proprietary technical methods
- Making guarantees about fixes

### **Scenario 3: Pricing Inquiry**

**Customer asks:** "How much does a smart home installation cost?"

**AI Assistant should:**
1. Acknowledge the question
2. Explain that pricing depends on specific requirements
3. Mention service packages exist (reference `Services/Service_Packages_Reference_v1.0_20250609.md`)
4. Offer free consultation to discuss needs and pricing
5. Provide contact information

**Avoid:**
- Making up pricing information
- Referencing confidential pricing documents
- Providing specific cost estimates

### **Scenario 4: Documentation Review Request**

**User asks:** "Review this new FAQ document for quality"

**AI Assistant should:**
1. Read document completely
2. Check against QA Framework criteria (all 5 categories)
3. Verify template compliance
4. Check for proper AI markers
5. Validate content classification
6. Score across 100-point system
7. Provide detailed feedback report
8. Recommend approval status

**Avoid:**
- Superficial review without checking all criteria
- Approving content with confidential information
- Missing metadata validation

---

## Style Guide & Writing Standards

### **Tone and Voice**
- **Professional yet conversational** - Approachable but expert
- **Customer-focused** - Emphasize benefits and solutions
- **Clear and concise** - Avoid jargon unless necessary
- **Confident but not arrogant** - Expertise without condescension
- **Bilingual awareness** - Consider Arabic language needs

### **Writing Conventions**
- **Active voice preferred** - "We install systems" not "Systems are installed"
- **Second person for customer docs** - "You can control..." not "Customers can..."
- **Bullet points for lists** - Easier scanning and comprehension
- **Headers for organization** - Clear hierarchy and structure
- **Examples for clarity** - Illustrate complex concepts

### **Terminology Standards**
- **Smart Home/Smart Solutions** - Not "home automation" alone
- **CCTV/Video Surveillance** - Both terms acceptable
- **BY MB Consultancy** - Full company name in formal contexts
- **Free Consultation** - Not "free quote" or "free estimate"
- **Professional** - Key differentiator, use frequently

### **Formatting Standards**
- **Markdown format** - All documentation in .md format
- **Headers:** Use # for h1, ## for h2, etc.
- **Bold:** `**text**` for emphasis and labels
- **Italics:** `*text*` for subtle emphasis
- **Code blocks:** ``` for technical content
- **Links:** `[Text](URL)` for all hyperlinks
- **Tables:** Use for comparisons and structured data

---

## Key Reference Documents

### **Must-Read for AI Assistants**

#### **Policy Documents:**
1. `Policies/Knowledge_Center_Policy_for_AI_v1.0_20250422.md` - Foundational AI policy
2. `Policies/Content_Update_Policy_v1.0_20250422.md` - Update procedures
3. `Policies/Data_Privacy_Policy_v1.0_20250422.md` - Privacy requirements

#### **Quality Assurance:**
1. `Quality_Assurance/QA_Framework_v1.0_20250610.md` - Complete QA system
2. `Quality_Assurance/Content_Classification_Guidelines.md` - Security classification
3. `Approval_Workflow/Enhanced_Approval_Workflow_v2.0_20250610.md` - Approval process

#### **AI Agent Roles:**
1. `AI_Roles/index.md` - Overview of all AI agents
2. `AI_Roles/AI_Roles_QualityAssuranceAgent_v1.0_20250610.md` - QA agent responsibilities

#### **Status Tracking:**
1. `Content_Classification_Status.md` - Security and classification status
2. `Knowledge_Center_Status_Dashboard.md` - Project progress

#### **Core Documentation:**
1. `README.md` - Public-facing knowledge center overview
2. `index.md` - Internal knowledge center overview

---

## Project Status & Metrics

### **Current Status (as of June 2025)**
- **Project Progress:** 65 of 89 documents completed (73%)
- **AI Implementation:** Phase 1 complete, Phase 2 in progress
- **Security Status:** 100% compliant - all content properly classified
- **Quality System:** Fully operational with automated QA reviews

### **Key Achievements**
- ✅ All AI agent role definitions complete
- ✅ QA framework fully implemented
- ✅ Content classification system operational
- ✅ Main branch 100% public-safe
- ✅ Quality metrics tracking active

### **Active Focus Areas**
- 🟡 Azure AI environment setup
- 🟡 API integrations (Power BI, SQL, Odoo)
- 🟡 Multi-agent coordination infrastructure
- 🟡 Remaining document completion

---

## Troubleshooting & Common Issues

### **Issue: Missing AI Markers**
**Problem:** Document lacks [AI-PRIORITY], [AI-CAUTION], [AI-EXAMPLE], or [AI-ESCALATE] markers.

**Solution:**
1. Review document purpose and content
2. Add [AI-PRIORITY] for essential information
3. Add [AI-CAUTION] for sensitive topics
4. Add [AI-EXAMPLE] for reference scenarios
5. Add [AI-ESCALATE] for human-only decisions

### **Issue: Unclear Classification**
**Problem:** Unable to determine if content is PUBLIC or CONFIDENTIAL.

**Solution:**
1. Review `Quality_Assurance/Content_Classification_Guidelines.md`
2. Check decision matrix
3. Apply security checklist
4. When uncertain, classify as NEEDS REVIEW
5. Escalate to human reviewer

### **Issue: Incomplete Metadata**
**Problem:** Document missing required metadata fields.

**Solution:**
1. Add all required metadata fields
2. Reference working documents as templates
3. Ensure version number is accurate
4. Verify date formatting (YYYYMMDD in filename, Month DD, YYYY in content)
5. Complete version history table

### **Issue: Broken Cross-References**
**Problem:** Links to other documents don't work.

**Solution:**
1. Use relative paths: `../Category/Document.md`
2. Verify target document exists
3. Check spelling and capitalization
4. Test links after creation
5. Update links when documents move

---

## Best Practices for AI Assistants

### **Documentation Review**
1. ✅ **Always read documents completely** before providing feedback
2. ✅ **Check all five QA categories** systematically
3. ✅ **Verify security classification** rigorously
4. ✅ **Validate metadata completeness** against requirements
5. ✅ **Test cross-references** for functionality

### **Customer Interaction**
1. ✅ **Reference [AI-PRIORITY] content** first
2. ✅ **Respect [AI-ESCALATE] markers** - route to humans
3. ✅ **Handle [AI-CAUTION] topics** with extra care
4. ✅ **Use [AI-EXAMPLE] content** for consistency
5. ✅ **Never invent information** not in documentation

### **Content Creation**
1. ✅ **Follow templates** religiously
2. ✅ **Include AI markers** appropriately
3. ✅ **Complete all metadata** before submission
4. ✅ **Self-classify** for security
5. ✅ **Self-review** against QA criteria

### **Quality Assurance**
1. ✅ **Apply 100-point scoring** systematically
2. ✅ **Provide specific feedback** not general comments
3. ✅ **Identify security risks** proactively
4. ✅ **Recommend concrete actions** for improvement
5. ✅ **Escalate when uncertain** to human reviewers

---

## Contact & Support

### **For Questions About:**

#### **Content & Documentation**
- **Review:** Content Classification Status and QA Framework documents
- **Escalate to:** Content Manager or Documentation Team

#### **Security & Classification**
- **Review:** Content Classification Guidelines
- **Escalate to:** Security team or Department Head

#### **AI Agent Behavior**
- **Review:** AI_Roles directory for agent definitions
- **Escalate to:** AI Operations Director or technical lead

#### **Quality Assurance**
- **Review:** QA Framework and Quality Review Templates
- **Escalate to:** Quality Assurance team

#### **Emergency Issues**
- **Review:** Emergency Response Policy
- **Follow:** Emergency Update Process (30-minute timeline)
- **Escalate to:** Emergency Team immediately

---

## Appendices

### **A. Quick Reference Cheat Sheet**

```markdown
DOCUMENT NAMING: [Category]_[Subcategory]_[Description]_v[Version]_[Date].md
VERSIONING: Major.Minor.Patch (1.0, 1.1, 1.1.1)
AI MARKERS: [AI-PRIORITY], [AI-CAUTION], [AI-EXAMPLE], [AI-ESCALATE]
CLASSIFICATION: PUBLIC, CONFIDENTIAL, MIXED, NEEDS REVIEW
QA SCORE: 95-100 = Approved, 85-94 = Minor Revisions, 70-84 = Major Revisions, <70 = Reject
BRANCHES: main = public-safe, confidential-content = internal only
```

### **B. Common Document Templates**

Refer to templates in `Quality_Assurance/templates/` for:
- Service documentation
- Technical guides
- Policy documents
- FAQ entries
- AI agent roles

### **C. Glossary of Terms**

- **QA:** Quality Assurance
- **AI Marker:** Special tag guiding AI behavior ([AI-PRIORITY], etc.)
- **Content Classification:** Security categorization (PUBLIC/CONFIDENTIAL)
- **Escalation:** Routing to human expert
- **Version Control:** Tracking document changes over time
- **Metadata:** Document information (author, date, version, etc.)
- **Template Compliance:** Adherence to standard document structure
- **Cross-Reference:** Link to related documentation

---

## Document History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | November 23, 2025 | Initial CLAUDE.md creation with comprehensive AI assistant guide | BY MB Documentation Team |

---

**Last Updated:** November 23, 2025
**Next Review:** February 23, 2026
**Status:** ✅ Active
**Classification:** 🌐 PUBLIC

---

*This document is maintained by the BY MB Documentation Team and updated as the knowledge center evolves. AI assistants should reference this guide whenever working with the bymb-documentation repository.*
