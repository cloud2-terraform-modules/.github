### Description
<!-- Briefly summarize the changes and their purpose. -->  

### Additional Notes
<!-- Provide any additional information that might help the reviewer, e.g., how testing has been done. -->  

### Creator Checklist
<!-- Check items by adding an "x" within the brackets or clicking after the PR is created. -->  

- [ ] **Testing**
  - Changes have been tested locally or in an appropriate environment.
  - Infrastructure configurations have been reviewed (e.g., Terraform plans).

- [ ] **Security**
  - No hardcoded secrets (e.g., API keys, credentials).
  - IAM roles and permissions follow the principle of least privilege.
  - Public exposure of resources (e.g., storage, APIs, security groups) is restricted unless explicitly required.
  - No security misconfigurations in infrastructure (e.g., open security groups, unrestricted access).
  - Input validation and error handling follow secure coding practices (e.g., OWASP Top 10).

- [ ] **Logging & Monitoring**
  - Logging provides sufficient context for debugging and auditing without exposing sensitive information.
  - Logs are securely stored and adhere to compliance requirements.
  - Monitoring and alerting have been updated to reflect changes.

- [ ] **Dependencies**
  - Dependencies come from trusted sources.
  - Versions are pinned to prevent unexpected updates.
  - Dependencies have been vetted for security vulnerabilities and licensing issues.

- [ ] **Documentation**
  - Relevant documentation (e.g., API docs, usage instructions, examples) has been updated.

### Reviewer Checklist
<!-- Ensure all security and quality checks are met before approving. -->  

- [ ] **Code Review**
  - Code is clean, follows best practices, and avoids unnecessary complexity.
  - Error handling and input validation are properly implemented.

- [ ] **Security**
  - No hardcoded secrets or sensitive data exposure.
  - IAM and access controls are properly scoped and follow least privilege.
  - No unnecessary publicly accessible resources.
  - Code follows secure development practices (e.g., input validation, error handling).

- [ ] **Logging & Monitoring**
  - Sufficient logging is in place for debugging and auditing.
  - No sensitive data is logged.
  - Monitoring and alerting have been updated to reflect changes.

- [ ] **Dependencies**
  - No untrusted or vulnerable dependencies are introduced.
  - Versioning strategy is appropriate.

- [ ] **Documentation**
  - Any necessary updates to documentation are made.  