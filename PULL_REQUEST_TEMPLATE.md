<!-- You can override this template by creating a `.github/PULL_REQUEST_TEMPLATE.md` file in the repository root. -->

### Description
<!-- Briefly summarize the changes and their purpose. -->

### Additional Notes
<!-- Provide any additional information that might help the reviewer. -->

### Creator Checklist
- [ ] **Testing**
  - Changes have been tested locally or in an appropriate environment
- [ ] **Security**
  - Secrets (e.g., credentials, keys) are not hardcoded or exposed
  - Changes adhere to security best practices 
- [ ] **Logging**
  - Created logs are stored securely
  - Created logs do not contain sensitive information
- [ ] **Dependencies** (e.g., providers, modules, libraries)
  - Are from trusted sources
  - Have versions pinned to avoid unexpected changes
  - Have been checked for licensing issues
- [ ] **Documentation**
  - Relevant documentation has been updated.

### Reviewer Checklist

- [ ] **Testing**
  - The Terraform plan has been reviewed (if applicable)
- [ ] **Security**
  - All security considerations have been addressed, such as:
    - IAM roles and policies follow the principle of least privilege
    - Sensitive resources (e.g., buckets) are properly secured
    - Public exposure is appropriately restricted (e.g., using security groups or firewalls)
- [ ] **Dependencies**
  - Dependencies are from trusted sources and versions are pinned
