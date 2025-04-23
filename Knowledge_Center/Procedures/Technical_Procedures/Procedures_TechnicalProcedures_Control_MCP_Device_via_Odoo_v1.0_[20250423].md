---
Document ID: Procedures_TechnicalProcedures_Control_MCP_Device_via_Odoo_v1.0_[20250423]
Author: BY MB Documentation Team
Last Updated: [Current Date, e.g., April 23, 2025]
Version: 1.0
Language: English/Arabic
Review Date: [Review Date, e.g., October 23, 2025 - ~6 months out]
Keywords: MCP, Odoo, smart home, control, procedure, AI action, integration, smart solutions, technical procedure, device management
---

# Procedures - Control MCP Device via Odoo

## Policy Overview
[AI-PRIORITY]
This procedure outlines the standard steps for AI agents to control devices connected to the MCP server by interacting with the integrated Odoo system. All MCP device control actions initiated by AI agents must follow this documented process to ensure consistency, reliability, and proper logging through the Odoo integration layer.

## Scope
[AI-PRIORITY]
This procedure applies to all AI agents requiring the ability to send control commands to devices managed by the MCP server through the established Odoo integration (`tuanle96/mcp-odoo` module or similar).

## Prerequisites

Before initiating an MCP device control action via Odoo, the AI agent must ensure:

*   The Odoo system is operational and accessible via the designated API tool.
*   The MCP integration module is active and correctly configured within the Odoo instance.
*   The AI agent has access to the "Odoo API Tool" function.
*   The target MCP device has been clearly identified (e.g., by a unique ID or name known to the system).
*   The desired control action and state (e.g., "turn on", "set brightness to 50%") are understood from the user's request.

## Procedure: Initiating a Control Action

[AI-EXAMPLE]
To control an MCP device by sending a command through Odoo, the AI agent must follow these steps:

1.  **Identify Request:** Analyze the user's input to confirm a request to control an MCP-managed device.
2.  **Extract Key Information:** From the request and conversation memory, identify the target device identifier (ID/Name) and the desired action/state.
3.  **Validate Device and Action:** (Optional but Recommended) Check if the identified device is a known MCP device and if the requested action is supported for that device type, potentially by querying the Knowledge Base or Odoo itself. [AI-CAUTION] (Ensure the device exists before attempting control).
4.  **Formulate Odoo Command:** Construct the specific API call payload or command required by your Odoo's MCP integration module to instruct Odoo to perform the desired action on the target device. This will depend on how the `mcp-odoo` module's API is exposed within Odoo.
    *   *Example (Conceptual):* Prepare a JSON payload like `{"device_id": "light_123", "command": "set_state", "state": "on"}` for the Odoo API tool to send.
5.  **Execute Odoo API Tool:** Use the AI agent's designated "Odoo API Tool" function, passing the formulated command as parameters.
    *   *Tool Usage:* `CallTool("Odoo API Tool", command_parameters)`
6.  **Process Odoo Response:** Receive and analyze the response from the "Odoo API Tool". Check for success codes or error messages returned by Odoo.
7.  **Confirm Action Status:** If the Odoo response indicates success, assume the command was sent to the MCP server via the integration. If needed, a follow-up check (if the integration provides a way to query device status through Odoo) could be performed.
8.  **Inform User:** Provide feedback to the user about the outcome of the control action (e.g., "Okay, I've sent the command to turn on the light.").

## Error Handling and Escalation

[AI-ESCALATE]
If any step in the procedure fails (e.g., Odoo API tool returns an error, device validation fails, Odoo reports an error from the MCP integration):

*   **Identify the Error:** Note the specific error message or type of failure.
*   **Attempt Basic Troubleshooting:** Check common issues (e.g., invalid device ID, unsupported command).
*   **Escalate:** If the issue cannot be resolved through basic troubleshooting or is critical (e.g., consistent failure for all commands), trigger the standard escalation protocol. Provide the user's request, the attempted procedure steps, the exact error encountered, and any relevant conversation history to the human support team.
*   **Related Documents:** Refer to `/Knowledge_Center/Policies/AI_Escalation_Process.md` for detailed escalation steps.

## Related Documents

*   `/Knowledge_Center/Policies/AI_Escalation_Process.md`
*   [Placeholder for specific Odoo API Tool documentation for AI Agents]
*   [Placeholder for documentation detailing known MCP devices and supported actions in Odoo]
*   [Placeholder for relevant Service/Product documentation, e.g., Smart Home Automation]

## Version History
| Version | Date           | Changes                                                    | Author             |
| :------ | :------------- | :--------------------------------------------------------- | :----------------- |
| 1.0     | [Current Date] | Initial procedure for controlling MCP devices via Odoo API | BY MB Documentation Team |
