# AI Roles Directory

This directory contains role definitions for all AI agents and systems within BY MB Consultancy.

## Structure

```
AI_Roles/
├── README.md (this file)
├── AI_Operations_Director/
├── SupportBot/
├── TechBot/
├── OdooBot/
└── Other AI Agents/
```

## Purpose

Each AI role is defined using the standard template found in `/Knowledge_Center/Templates/AI_Role_Template.md`. These role definitions serve to:

1. Define responsibilities and boundaries for each AI agent
2. Establish system prompts for consistent behavior
3. Document performance metrics and success criteria
4. Set escalation protocols
5. Define access levels and tool integration

## Creating New AI Roles

1. Copy the template from `/Knowledge_Center/Templates/AI_Role_Template.md`
2. Create a new directory under this folder with the agent name
3. Fill out all required fields in the template
4. Submit for review through standard approval workflow
5. Place approved role definition in the appropriate directory

## File Naming Convention

```
AI_Roles_[AgentName]_v[X.X]_[YYYYMMDD].md
```

Example: `AI_Roles_SupportBot_v1.0_20250422.md`

## Review Schedule

- Monthly: Performance metrics review
- Quarterly: Role responsibilities and access review
- Annually: Complete role definition review

## Standards and Compliance

All AI role definitions must:
- Follow the template structure
- Include all required metadata
- Use appropriate AI context markers
- Reference relevant policies and decision trees
- Be approved through the standard workflow

## AI Context Markers

The following markers should be used appropriately:
- `[AI-PRIORITY]` - Essential information for AI operations
- `[AI-CAUTION]` - Sensitive information requiring careful handling
- `[AI-EXAMPLE]` - Examples for reference
- `[AI-ESCALATE]` - Escalation triggers

## Related Documents

- `/Knowledge_Center/Templates/AI_Role_Template.md`
- `/Knowledge_Center/Policies/AI_Ethical_Standards.md`
- `/Knowledge_Center/Policies/AI_Escalation_Process.md`
- `/Knowledge_Center/Decision_Trees/AI_Decision_Flow.md`
