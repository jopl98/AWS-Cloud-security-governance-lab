# AWS Cloud Security Governance Lab
> Designed and implemented a centralized AWS security governance and logging architecture using AWS Organizations, CloudTrail, Amazon S3, and Security Hub.

## Overview
This project focuses on implementing security governance controls, audit logging, and secuirty visibility aligned with AWS secuirty best pratices.

## Architecture
- AWS Organizations (SCP enabled)
- Amazon S3 for centralized log storage
- AWS CloudTrail for API logging
- AWS Security Hub for monitoring

## Security Controls
- Enabled Service Control Policies (SCPs)
- Secured S3 bucket (Block Public Access ON)
- Configured CloudTrail multi-region logging
- Enabled Security Hub

## Screenshots

### AWS Organizations - SCP Enabled
![SCP](SCP_ENABLED.JPEG)

### S3 Bucket
![S3](Block_public_S3_access.JPEG)

### CloudTrail Logging
![CloudTrail](CloudTrail_created.JPEG)

### Security Hub
![SecurityHub](SecurityHub_enabled_dashboard.jpg)

## Notes
Multi-account setup was simulated due to account creation issues. Core governance and monitoring concepts were still implemented.

## What This Demonstrates
- Centralized AWS security governance using AWS Organizations
- Secure log storage and data protection using Amazon S3
- Multi-region API activity tracking using AWS CloudTrail
- Security monitoring and findings aggregation using AWS Security Hub
- Ability to design and document cloud security architecture
