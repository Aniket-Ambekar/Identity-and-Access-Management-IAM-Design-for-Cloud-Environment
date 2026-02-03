# Identity and Access Management (IAM) Design for Cloud Environment

## Objective
To design a secure and scalable IAM model that minimizes unauthorized access and reduces identity-related security risks in a cloud environment.

---

## Role Definition
The following roles were defined:

### Administrator
- Full infrastructure access
- MFA enforced
- All actions logged and audited

### Developer
- Access limited to application resources
- No infrastructure-level permissions
- No access to security logs

### SOC Analyst
- Read-only access to logs and monitoring systems
- No modification privileges

---

## Access Control Strategy
- Role-Based Access Control (RBAC)
- Separation of duties across roles
- No shared user accounts
- Least privilege enforced for all roles

---

## Authentication Strategy
- Multi-factor authentication for privileged roles
- Strong password policies
- Centralized identity management

---

## Risk Mitigation Mapping
| Risk | Control | Outcome |
|----|----|----|
| Credential theft | MFA | Reduced account compromise |
| Privilege abuse | RBAC | Limited blast radius |
| Insider threat | Logging and audits | Improved accountability |

---

## Conclusion
A well-designed IAM strategy significantly reduces unauthorized access risks while maintaining operational efficiency in a cloud environment.
