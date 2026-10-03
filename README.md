<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=n8n%20multi%20api%20orchestration%20assessment;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=n8n-multi-api-orchestration-assessment&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/n8n-multi-api-orchestration-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/n8n-multi-api-orchestration-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment) · [🐞 Report Issue](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/issues/new) · [⭐ Star](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/n8n-multi-api-orchestration-assessment/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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
