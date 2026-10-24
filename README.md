# Enterprise Cloud Risk Management Assessment

**NIST Risk Management Framework (RMF) | AWS Security | Governance, Risk & Compliance (GRC)**

## Project Overview

This academic project applied the NIST Risk Management Framework to a simulated government information system operated by the fictional State Institute of Science and Technology (SIST).

The assessment focused on the AWS-hosted SIST Web Infrastructure System, supporting HR, GMAT, and FCIN applications. Using the high-water-mark approach, the system was categorized as **High impact** for confidentiality, integrity, and availability.

The project involved security categorization, System Security Plan (SSP) development, audit-event control assessment planning, and continuous monitoring strategy development.

## Project Scope

The proposed AWS environment includes:

- Amazon EC2 web, application, and database servers
- AWS Identity and Access Management (IAM)
- AWS CloudTrail for API activity logging
- Amazon CloudWatch Logs for system and application logging
- Amazon S3 for audit log storage
- AWS Config for proposed configuration compliance monitoring

The assessment also considered external system interconnections and a hypothetical migration from Azure to AWS and the SIST Data Center.

## NIST RMF Activities

| RMF Activity | Work Performed |
|---|---|
| Categorize | Evaluated confidentiality, integrity, and availability impact levels and determined system categorization |
| Select & Document | Developed SSP documentation and identified relevant security requirements |
| Assess | Prepared an AU-2 Audit Events control assessment plan using examine, interview, and test methods |
| Monitor | Developed an ISCM strategy, identified security metrics, and analyzed infrastructure migration risks |

## Project Deliverables

- [Executive Summary](deliverables/Executive%20Summary.pdf)
- [Security Categorization](deliverables/RMF_Categorization.pdf)
- [System Security Plan (SSP)](deliverables/RMF_System_Security_Plan.pdf)
- [AU-2 Control Assessment Plan](deliverables/RMF_AU2_Control_Assessment.pdf)
- [Continuous Monitoring Strategy](deliverables/RMF_Continuous%20monitoring.pdf)

## Frameworks and Technologies

**Frameworks:** NIST RMF, NIST SP 800-53, NIST SP 800-53A, NIST SP 800-60, NIST SP 800-137

**Cloud Security:** AWS IAM, CloudTrail, CloudWatch Logs, Amazon S3, AWS Config

**GRC Skills:** Security categorization, control assessment planning, SSP documentation, risk identification, continuous monitoring, and POA&M planning

## Key Recommendations

- Implement automated configuration compliance monitoring.
- Strengthen identity and privileged access management.
- Establish centralized security logging and monitoring.
- Reassess security controls and authorization boundaries following significant infrastructure changes.

## Project Limitations

This project was completed as an academic simulation. The AWS architecture, monitoring services, and assessment procedures were proposed and documented rather than verified through a production deployment or completed technical control testing.


## Note
This is an academic simulation project. No real government systems, sensitive data, or production environments were used.
