
# Zero Trust Security Architecture for Cloud Environments

## Overview

This project implements a Python-based Zero Trust security model for cloud environments based on the principles of NIST SP 800-207.

The model evaluates security posture across identity, device, cloud, network and behavioural factors to generate a trust score and make risk-based access decisions.

## Key Features

- Zero Trust security architecture based on NIST SP 800-207
- 100-point trust scoring system
- Identity security assessment
- Device compliance assessment
- Cloud security configuration assessment
- Network security assessment
- Behavioural anomaly analysis
- Risk-based access decisions

## Security Domains

The model evaluates five security domains:

1. Identity
2. Device
3. Cloud
4. Network
5. Behaviour

## Technology Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Cloud Platforms

The project uses simulated users across:

- AWS
- Microsoft Azure
- Google Cloud Platform

## Access Decisions

The trust score determines the access decision:

- **70–100:** Grant Access
- **40–69:** Verify
- **Below 40:** Deny Access

## Project Data

The project uses simulated cloud-user data for demonstration and analysis. It is not connected to live production cloud environments.

## Future Improvements

Future development could integrate live security data sources such as AWS CloudTrail, Azure identity services and other cloud security monitoring platforms.
