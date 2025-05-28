# Service Inquiry Handling - Decision Tree

## Document Information
- **Document ID:** Process_DecisionTree_ServiceInquiry_v1.0_20250422
- **Author:** BY MB Customer Service Team
- **Last Updated:** April 22, 2025
- **Version:** 1.0
- **Language:** English
- **Review Date:** July 22, 2025
- **Keywords:** service inquiry, customer support, decision tree, automation

## Decision Tree Overview
[AI-PRIORITY]
Purpose of this decision tree:
- Guide AI in handling customer service inquiries efficiently
- Determine appropriate service recommendations
- Identify when to escalate to human support
- Ensure consistent customer experience

## Starting Point
[AI-EXAMPLE]
**Initial Question:** "How can I help you today?"

### Option 1: "I need help with home/office automation"
- **Next Step:** Determine if residential or commercial
- **Sub-question:** "Is this for your home or business?"
  - If Home: Proceed to Smart Home Solutions path
  - If Business: Proceed to Office Automation path

### Option 2: "I need help with security systems"
- **Next Step:** Identify security type needed
- **Sub-question:** "Are you looking for cameras, access control, or a complete security solution?"
  - If Cameras: Proceed to CCTV Solutions path
  - If Access Control: Proceed to Access Control path
  - If Complete Solution: Proceed to Integrated Security path

### Option 3: "I need help with data analytics/business intelligence"
- **Next Step:** Understand business needs
- **Sub-question:** "What type of data analysis are you interested in?"
  - If Performance Dashboards: Proceed to Power BI path
  - If Data Integration: Proceed to Database Solutions path
  - If Predictive Analytics: Proceed to Advanced Analytics path

### Option 4: "I need technical support"
[AI-ESCALATE]
- **Next Step:** Immediate escalation to technical support
- **Action:** Transfer to technical support team
- **Provide:** Ticket number and expected wait time

## Smart Home Solutions Path
[AI-EXAMPLE]
1. **Question:** "What size is your home?"
   - Small (Apartment/Small House): Recommend Essential Smart Package
   - Large (Villa/Large House): Recommend Professional Smart Package

2. **Question:** "What features are most important to you?"
   - Security: Emphasize security integration features
   - Energy Saving: Highlight climate control and automation
   - Convenience: Focus on voice control and automation

3. **Action:** Provide package recommendation and offer consultation

## Office Automation Path
[AI-EXAMPLE]
1. **Question:** "What is the size of your office?"
   - Small (1-10 employees): Basic automation package
   - Medium (11-50 employees): Standard automation package
   - Large (50+ employees): Enterprise automation solution

2. **Question:** "What are your primary automation needs?"
   - Access Control: Focus on security features
   - Energy Management: Highlight efficiency solutions
   - Meeting Room Management: Emphasize collaboration tools

3. **Action:** Provide solution overview and schedule consultation

## Security Solutions Paths
[AI-CAUTION]
### CCTV Solutions
1. **Question:** "Indoor or outdoor cameras needed?"
2. **Question:** "How many cameras do you estimate?"
3. **Action:** Recommend appropriate camera package

### Access Control
1. **Question:** "Number of access points?"
2. **Question:** "Integration with existing systems needed?"
3. **Action:** Suggest suitable access control solution

### Integrated Security
[AI-ESCALATE]
1. **Action:** Due to complexity, escalate to security specialist
2. **Provide:** Basic information about integrated solutions
3. **Schedule:** Security assessment appointment

## Analytics Solutions Paths
[AI-CAUTION]
### Power BI Implementation
1. **Question:** "What data sources need to be connected?"
2. **Question:** "Do you need training for your team?"
3. **Action:** Recommend appropriate BI package

### Database Solutions
1. **Question:** "What type of databases are you currently using?"
2. **Question:** "What are your main data challenges?"
3. **Action:** Suggest database optimization service

### Advanced Analytics
[AI-ESCALATE]
1. **Action:** Complex requirement - escalate to data specialist
2. **Collect:** Basic business information
3. **Schedule:** Analytics consultation

## Pricing Inquiries
[AI-CAUTION]
1. **Response:** "Our pricing is customized based on your specific needs."
2. **Action:** Offer free consultation to provide accurate quote
3. **Provide:** General package information without specific prices

## Consultation Scheduling
[AI-PRIORITY]
1. **Confirm:** Service interest and requirements
2. **Collect:** Contact information (name, email, phone)
3. **Offer:** Available time slots for consultation
4. **Send:** Confirmation email with appointment details

## Escalation Points
[AI-ESCALATE]
Always escalate for:
- Technical issues beyond basic troubleshooting
- Custom solution requests
- Complaints or negative feedback
- Legal or compliance questions
- Pricing negotiations
- Enterprise-level inquiries

## Visual Decision Tree
```
                [Initial Inquiry]
                       |
         -----------------------------
         |             |             |
    [Smart Home]  [Analytics]  [Security]
         |             |             |
    [Size Check]  [Needs Check] [Type Check]
         |             |             |
    [Recommend]   [Recommend]  [Recommend]
         |             |             |
         -----------------------------
                       |
              [Offer Consultation]
```

## Related Documents
- Service Catalog
- Pricing Guidelines
- Consultation Procedure
- Technical Escalation Process

## Version History
| Version | Date       | Changes                    | Author               |
|---------|------------|----------------------------|----------------------|
| 1.0     | 2025-04-22 | Initial decision tree created | BY MB Customer Service |
