# Botium Toys – Internal IT Audit Report

## 1. Scope and Goals

### Scope
The scope of this audit covers the entire security program at Botium Toys, including:

- On-premises infrastructure
- Employee equipment and end-user devices
- Internal network
- E-commerce and payment systems
- Data storage and retention
- Legacy systems
- Physical security controls

### Goals
- Assess existing assets
- Evaluate current security controls
- Identify compliance gaps
- Complete controls and compliance checklist
- Recommend improvements to strengthen security posture

## 2. Current Assets

Assets managed by the IT department include:

- On-premises business systems
- Employee devices (desktops, laptops, smartphones, remote workstations)
- Warehouse inventory systems
- E-commerce platform
- Accounting and database systems
- Internal network and internet connectivity
- Legacy systems
- Physical storefront security infrastructure

## 3. Risk Assessment Summary

### Overall Risk Score: 8/10 (High)

Botium Toys currently faces a high risk exposure due to:

- Inadequate asset management
- Weak access control implementation
- Lack of encryption for cardholder data
- No intrusion detection system (IDS)
- No disaster recovery plan or data backups
- Non-compliance with best practices for least privilege and separation of duties

## 4. Control Evaluation

### Access Control
- All employees currently have broad access to internally stored data.
- Least privilege and separation of duties are NOT implemented.
- Password policy exists but is weak and not centrally enforced.
- No centralised password management system.

Risk Level: High

### Data Protection
- Credit card data is NOT encrypted at rest.
- This creates major PCI-DSS compliance exposure.

Risk Level: Critical

### Network Security
- Firewall is properly configured.
- Antivirus software installed and monitored.
- No Intrusion Detection System (IDS) implemented.

Risk Level: Medium-High

### Business Continuity
- No disaster recovery plan.
- No data backups.
- Legacy systems are monitored, but not on a scheduled basis.

Risk Level: Critical

### Compliance & Privacy
- A 72-hour EU breach notification process exists.
- Privacy policies documented and enforced.

Risk Level: Moderate (Good foundation but incomplete controls)

## 5. Recommendations

Immediate:
- Implement encryption for cardholder data (PCI-DSS compliance)
- Enforce least privilege access controls
- Deploy a centralised password management system
- Establish a regular backup schedule
- Develop and test a disaster recovery plan

Short-Term:
- Deploy Intrusion Detection System (IDS)
- Implement asset inventory and classification process
- Establish a formal legacy system maintenance schedule

Long-Term:
- Conduct formal compliance audit (PCI-DSS & GDPR)
- Implement role-based access control (RBAC)
- Perform regular vulnerability assessments

## 6. Conclusion

Botium Toys currently maintains some foundational controls (firewall, antivirus, physical security), but lacks critical security controls required to protect sensitive customer data and maintain regulatory compliance.

Without immediate remediation, the organisation faces significant risk of data breach, regulatory fines, and operational disruption.

This audit demonstrates the importance of structured governance and alignment with the NIST Cybersecurity Framework (CSF).
