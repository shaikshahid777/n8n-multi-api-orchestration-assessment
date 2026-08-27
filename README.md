# Lesson 8 – Multi-API Orchestration Assessment

## Integrating Multiple APIs Together

This repository contains the n8n workflow for the Lesson 8 LMS assessment.

### Workflow Flow

`Start (Manual Trigger) → Initialize Ticket Payload → Generate Transaction ID → Customer Lookup → Log Ticket to Mock DB API → Verify DB Response → Send Notification → Validate Execution Flow`

### Assessment Coverage

- Manual workflow initialization
- Support ticket payload creation
- Dynamic transaction ID generation
- Customer email to customer ID mapping
- Mock database API integration
- Database response verification
- Notification API request
- Ancestor-node data references
- End-to-end execution validation

### APIs

The workflow uses HTTPBin as the mock API endpoint for ticket logging and notification requests.

### Security / Good Practices

Dynamic values are mapped through n8n expressions and previous-node references. Do not commit real credentials, tokens, or secrets to this repository.

### Submission Evidence

The LMS submission should include the Loom/YouTube demonstration, exported n8n workflow JSON, and assessor comments describing challenges, assumptions, limitations, and enhancements.
