## Observing Agentic AI workloads using Amazon CloudWatch

This repository contains the sample code and resources for the AWS blog post [Observing Agentic AI workloads using Amazon CloudWatch](http://aws.amazon.com/blogs/mt/observing-agentic-ai-workloads-using-amazon-cloudwatch/).

![Architecure Diagram](/architecture-diagram.png)

## Overview

This sample demonstrates how to implement comprehensive observability for agentic AI applications using Amazon CloudWatch. The application features a weather forecasting agent built with the Strands agents AI framework, showcasing metrics collection, distributed tracing, and log correlation.

## Contents

- [app.py](/app.py) - Main weather forecaster agent application with OpenTelemetry tracing
- [metrics_utils.py](/metrics_utils.py) - Utilities for collecting and formatting metrics in EMF format
- [CW-AgentConfig.json](/CW-AgentConfig.json) - CloudWatch Agent configuration file for telemetry collection
- [ec2-deployment.yaml](/ec2-deployment.yaml) - CloudFormation template for automated EC2 deployment
- [setup-app.sh](/setup-app.sh) - Setup script to deploy weather forecaster agent and configuring the Cloudwatch agent

## Deployment

For detailed deployment instructions and setup steps, please refer to the complete blog post:

[Observing Agentic AI workloads using Amazon CloudWatch](http://aws.amazon.com/blogs/mt/observing-agentic-ai-workloads-using-amazon-cloudwatch/)

The blog post provides comprehensive guidance on:
- Setting up the observability infrastructure
- Configuring CloudWatch monitoring
- Understanding the metrics and traces generated
- Best practices for monitoring agentic AI workloads

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.


