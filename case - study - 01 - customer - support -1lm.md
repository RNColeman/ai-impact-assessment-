# Case Study 01: Customer Support LLM

## 1. System overview
- **Name:** Customer Support Virtual Assistant
- **Purpose:** Assist customers with account questions and troubleshooting via chat.
- **Context:** Deployed on a bank’s customer portal.

## 2. Key risks and harms
- Hallucinated answers leading to incorrect financial guidance.
- Exposure of sensitive financial information in chat logs.
- Biased responses or tone toward certain customer groups.
- Over-reliance on AI instead of escalation to human agents.

## 3. Privacy considerations
- Processes names, contact details, and account-related information.
- Chat logs stored for quality improvement and monitoring.
- Risk of logs being used beyond original purpose if not governed.

## 4. Controls and mitigations
- Human-in-the-loop for high-risk queries (e.g., loans, disputes).
- Strict access controls and retention limits on chat logs.
- Regular bias and quality audits of responses.
- Clear customer messaging that the assistant is AI and may escalate.

## 5. Residual risk and decision
- **Residual risk:** Medium
- **Decision:** Approve with conditions
- **Conditions:** Quarterly review, strict data retention, mandatory escalation rules.
