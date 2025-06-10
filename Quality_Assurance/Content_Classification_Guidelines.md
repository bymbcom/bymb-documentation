# Content Classification Guidelines

**Document Version:** v1.0  
**Date:** June 10, 2025  
**Author:** BY MB Consultancy  
**Status:** Active  
**Category:** Quality Assurance Guidelines

---

## Overview

This document provides comprehensive guidelines for classifying content as public, confidential, or mixed to ensure appropriate security measures and publication decisions for BY MB Knowledge Center documentation.

---

## Classification Categories

### **🌐 PUBLIC Content**
Content safe for public distribution on websites, marketing materials, and external-facing documentation.

#### Characteristics:
- General service descriptions
- Public methodology overviews
- Industry best practices
- General troubleshooting guides
- Non-sensitive technical information
- Company contact information
- Public certifications and credentials

#### Examples:
- "We provide CCTV installation services"
- "Hikvision cameras offer excellent night vision capabilities"
- "Network security best practices include regular password updates"
- "Our support hours are 9 AM to 5 PM"

### **🔒 CONFIDENTIAL Content**
Information that must be protected and restricted to internal use only.

#### Characteristics:
- Specific client names and project details
- Detailed pricing structures and profit margins
- Proprietary methodologies and trade secrets
- Internal team member personal information
- Vendor-specific negotiated rates
- Competitive advantage strategies
- Financial performance data
- Internal process vulnerabilities

#### Examples:
- "Project completed for ABC Corporation"
- "Our markup on Hikvision cameras is 35%"
- "Our exclusive vendor rate with XYZ supplier"
- "Team member John Smith's mobile number"

### **🔄 MIXED Content**
Documents containing both public and confidential information requiring separation or modification.

#### Characteristics:
- Case studies with client details
- Service descriptions with specific pricing
- Technical guides with proprietary elements
- Team information mixing roles with personal details

#### Handling Requirements:
- Create separate public and internal versions
- Anonymize sensitive details in public version
- Clearly mark confidential sections
- Provide alternative examples for public version

### **❓ NEEDS REVIEW Content**
Information requiring business decision regarding classification.

#### Characteristics:
- Competitive positioning statements
- Detailed technical capabilities
- Partnership information
- Certifications with conditions
- Industry relationships

---

## Classification Decision Matrix

### **Always Public ✅**
| Content Type | Examples | Justification |
|--------------|----------|---------------|
| **General Services** | "CCTV Installation", "Network Setup" | Marketing value, no competitive risk |
| **Industry Standards** | "Cat6 cable specifications" | Public knowledge, educational value |
| **General Support** | "Email support@by-mb.com" | Customer service requirement |
| **Company Overview** | "Founded in 2023", "Based in Bahrain" | Public information, credibility building |

### **Always Confidential 🔒**
| Content Type | Examples | Justification |
|--------------|----------|---------------|
| **Client Information** | Names, addresses, project details | Privacy protection, contractual obligations |
| **Pricing Details** | Costs, margins, vendor rates | Competitive protection, business strategy |
| **Personal Data** | Team member personal contact info | Privacy protection, security risk |
| **Proprietary Methods** | Unique processes, trade secrets | Competitive advantage protection |

### **Context-Dependent 🔄**
| Content Type | Public Version | Confidential Version |
|--------------|----------------|---------------------|
| **Case Studies** | "A major retail client..." | "ABC Retail Corporation..." |
| **Pricing Examples** | "Starting from competitive rates" | "Starting from $X per hour" |
| **Team Expertise** | "Our certified technicians" | "John Smith, CCTV certified" |
| **Vendor Relationships** | "Authorized Hikvision partner" | "Preferred rate: 15% below MSRP" |

---

## Content Security Risk Assessment

### **🔴 HIGH RISK - Never Public**
- Client names and specific project details
- Exact pricing, costs, and profit margins
- Personal information of team members
- Vendor-specific negotiated rates and terms
- Proprietary installation methods or trade secrets
- Financial performance or internal metrics
- Security vulnerabilities or system weaknesses

### **🟡 MEDIUM RISK - Review Required**
- Detailed technical specifications that might reveal capabilities
- Partnership details that might imply exclusivity
- Competitive positioning statements
- Certification details with limitations
- Industry relationship information

### **🟢 LOW RISK - Generally Safe**
- General service descriptions
- Public industry standards and best practices
- General troubleshooting guidance
- Company contact and location information
- Public certifications and credentials

---

## Implementation Guidelines

### **For Quality Reviewers**

#### **[AI-PRIORITY] Classification Checklist**
1. **Scan for Client Information**
   - [ ] No specific client names mentioned
   - [ ] No project addresses or locations
   - [ ] No client contact information
   - [ ] No confidential project details

2. **Review Financial Information**
   - [ ] No specific pricing mentioned
   - [ ] No cost breakdowns or margins
   - [ ] No vendor rates or discounts
   - [ ] No financial performance data

3. **Check Personal Information**
   - [ ] No team member personal details
   - [ ] No personal contact information
   - [ ] No private addresses or phone numbers
   - [ ] No sensitive personal data

4. **Evaluate Competitive Information**
   - [ ] No proprietary methodologies exposed
   - [ ] No competitive advantage details
   - [ ] No exclusive partnership terms
   - [ ] No internal strategic information

#### **[AI-CAUTION] Red Flag Indicators**
- **Immediate Confidentiality Concerns:**
  - Any mention of specific client names
  - Exact dollar amounts or percentages
  - Personal phone numbers or addresses
  - Detailed vendor pricing or terms
  - Proprietary process descriptions

#### **[AI-ESCALATE] Review Required Scenarios**
- Uncertain classification of technical capabilities
- Partnership information with unclear public status
- Competitive positioning requiring business decision
- New content types not covered in guidelines

### **For Content Creators**

#### **Self-Assessment Questions**
Before submitting content, ask:
1. Would sharing this information give competitors an advantage?
2. Does this content include any client-specific information?
3. Would I be comfortable seeing this on a competitor's website?
4. Does this expose any pricing or cost information?
5. Are there any personal details that should be protected?

#### **Content Sanitization Process**
1. **Replace Specific with General**
   - "ABC Corporation" → "A major retail client"
   - "$500/hour" → "Competitive hourly rates"
   - "John Smith" → "Our certified technician"

2. **Remove Sensitive Details**
   - Delete exact pricing information
   - Remove client contact information
   - Eliminate personal phone numbers
   - Strip vendor-specific terms

3. **Create Alternative Examples**
   - Use hypothetical scenarios instead of real projects
   - Reference industry standards instead of proprietary methods
   - Provide general ranges instead of specific prices

---

## Classification Workflow

### **Step 1: Initial Classification**
Content creator performs self-assessment and assigns preliminary classification:
- **PUBLIC** - Safe for external distribution
- **CONFIDENTIAL** - Internal use only
- **MIXED** - Contains both public and confidential elements
- **UNSURE** - Requires review for classification

### **Step 2: QA Review**
Quality Assurance Agent validates classification:
- Reviews content against classification guidelines
- Identifies any misclassified information
- Provides specific recommendations for content modification
- Escalates unclear cases to human reviewers

### **Step 3: Content Separation (if MIXED)**
For mixed content documents:
- Create public version with sensitive information removed
- Maintain confidential version for internal use
- Clearly label both versions
- Cross-reference between versions

### **Step 4: Approval and Publication**
- Public content approved for website and external use
- Confidential content restricted to internal knowledge base
- Mixed content published with appropriate access controls
- All versions tracked in version control system

---

## Common Classification Scenarios

### **Service Documentation**
**✅ Public Elements:**
- Service overview and benefits
- General process descriptions
- Industry best practices
- Contact information for inquiries

**🔒 Confidential Elements:**
- Specific pricing structures
- Detailed implementation methodologies
- Client-specific configurations
- Internal resource allocation

### **Technical Guides**
**✅ Public Elements:**
- General troubleshooting steps
- Industry standard procedures
- Product specification overviews
- Safety guidelines

**🔒 Confidential Elements:**
- Proprietary configuration methods
- Vendor-specific pricing arrangements
- Internal escalation procedures
- Client-specific implementations

### **Team Information**
**✅ Public Elements:**
- Role descriptions and responsibilities
- General qualifications and certifications
- Team structure and departments
- Professional contact methods

**🔒 Confidential Elements:**
- Personal contact information
- Salary and compensation details
- Performance evaluations
- Personal addresses or phone numbers

### **Case Studies**
**✅ Public Elements (Anonymized):**
- Industry sector and general size
- Challenge types and solutions
- Technology used (general)
- Results and benefits (general)

**🔒 Confidential Elements:**
- Specific client names and details
- Exact project costs and timelines
- Proprietary implementation details
- Specific ROI and performance metrics

---

## Quality Assurance Integration

### **Automated Classification Checks**
The QA system automatically flags content containing:
- Common client name patterns
- Currency symbols and specific amounts
- Phone number formats
- Email addresses (non-public)
- Vendor-specific terminology

### **Manual Review Triggers**
Content requiring human classification review:
- Technical specifications with unclear public status
- Partnership announcements
- Competitive analysis content
- New service or product information
- Industry positioning statements

### **Classification Reporting**
Each QA review includes:
- **Primary Classification:** Overall document classification
- **Security Risk Level:** Assessment of public distribution risk
- **Recommended Actions:** Specific steps for content preparation
- **Version Requirements:** Whether separate versions are needed

---

## Compliance and Legal Considerations

### **Privacy Protection**
- **[AI-CAUTION]** All personal information must be protected
- Client privacy takes precedence over marketing value
- Team member personal data requires explicit consent
- GDPR compliance for any EU-related content

### **Contractual Obligations**
- **[AI-CAUTION]** Client contracts may restrict information sharing
- Non-disclosure agreements supersede general guidelines
- Vendor agreements may limit public disclosure
- Partnership terms may restrict competitive positioning

### **Competitive Protection**
- **[AI-CAUTION]** Proprietary methods provide competitive advantage
- Trade secrets require the highest protection level
- Industry positioning requires careful consideration
- Financial information must remain confidential

---

## Monitoring and Updates

### **Regular Review Schedule**
- **Monthly:** Review classification accuracy metrics
- **Quarterly:** Update guidelines based on new scenarios
- **Annually:** Comprehensive review of classification system
- **As Needed:** Updates for new business areas or partnerships

### **Feedback Integration**
- QA reviewer feedback on classification challenges
- Content creator requests for clarification
- Business stakeholder input on competitive concerns
- Legal team guidance on compliance requirements

### **Continuous Improvement**
- Track classification accuracy rates
- Monitor false positive/negative rates
- Analyze common misclassification patterns
- Update guidelines based on lessons learned

---

## Training and Support

### **QA Reviewer Training**
- Complete understanding of classification guidelines
- Recognition of common red flag indicators
- Escalation procedures for unclear cases
- Regular updates on new classification scenarios

### **Content Creator Guidance**
- Self-assessment checklist and tools
- Common examples and scenarios
- Best practices for content sanitization
- Quick reference guides for classification decisions

### **Stakeholder Communication**
- Regular updates on classification policy changes
- Business impact assessments for classification decisions
- Stakeholder input on borderline classification cases
- Training for new team members and contractors

---

## Related Documents
- [Quality Assurance Framework](QA_Framework_v1.0_20250610.md)
- [Quality Review Report Template](Quality_Review_Templates/Quality_Review_Report_Template.md)
- [AI Role: Quality Assurance Agent](../AI_Roles/AI_Roles_QualityAssuranceAgent_v1.0_20250610.md)

## Support & Contact
For questions about content classification:
- **Email:** support@by-mb.com
- **Documentation:** [BY MB Knowledge Center](https://by-mb.com/knowledge-center)

---
*This document is part of the BY MB Knowledge Center*  
*Last Updated: June 10, 2025*
