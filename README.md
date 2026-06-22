# Advanced-Threat-Hunting-Agent-by-Inspira

Building a custom Microsoft Security Copilot agent to perform autonomous threat hunting and evidence-driven investigations across Microsoft Sentinel and Microsoft Defender XDR environments.

# Description

The Advanced Threat Hunting Agent is a deterministic, read-only Microsoft Security Copilot custom agent designed to proactively identify suspicious activity and investigate complex threats across Microsoft Sentinel and Microsoft Defender XDR.

The agent automatically retrieves incident context, correlates entities and indicators, analyzes users, devices, processes, files, URLs, and enriches findings with threat intelligence to uncover attack patterns and reconstruct attack chains.

The agent behaves like an experienced L3/L4 threat hunter by applying evidence-based reasoning, MITRE ATT&CK mapping, timeline reconstruction, and threat intelligence enrichment to generate analyst-grade investigation reports.

# Business Requirements

- Standardized threat hunting workflows for SOC operations.
- Faster identification of malicious activity and hidden threats.
- Improved analyst efficiency and investigation consistency.
- Reduced manual effort during advanced investigations.
- Evidence-driven analysis and reporting.
- Read-only and production-safe architecture.

# Prerequisites

- An active Microsoft Security Copilot environment.
- Access to Microsoft Security Store / Security Copilot custom agents.
- Microsoft Sentinel workspace.
- Microsoft Defender XDR access.

## Required Security Copilot Skillsets

- Generic
- Fusion
- Sentinel
- M365
- Threat Intelligence

## Permissions

- Read permissions to Microsoft Sentinel resources.
- Read permissions to Microsoft Defender XDR resources.
- Appropriate Security Copilot workspace access.

# Setup Guide

## Step 1: Access Microsoft Security Copilot

- Sign in to Microsoft Security Copilot.
- Open the Security Store.
- Search for Advanced Threat Hunting Agent by Inspira.
- Select the custom agent published by Inspira Enterprise.

## Step 2: Install the Agent

- Select Set up.
- Review the required permissions.
- Begin the installation process.

## Step 3: Grant Required Permissions

Ensure access exists to:

- Microsoft Sentinel
- Microsoft Defender XDR
- Required Security Copilot skillsets

## Step 4: Validate Required Skillsets

Ensure the following skillsets are enabled:

- Generic
- Fusion
- Sentinel
- M365
- Threat Intelligence

## Step 5: Complete Configuration

- Finish the setup process.
- Verify that the agent is visible and enabled.

# Running the Agent

## Option 1: Run Manually

Provide one of the following:

- Microsoft Sentinel Incident ID
- Microsoft Defender XDR Incident ID

The agent automatically:

- Detects the source platform.
- Retrieves incident context.
- Correlates entities and indicators.
- Performs threat hunting analysis.
- Enriches findings with threat intelligence.
- Generates analyst-grade investigation reports.

## Option 2: Trigger-Based Execution

The agent can be integrated into:

- Logic Apps
- SOC automation workflows
- Event-driven Security Copilot processes

# Input Requirements

Accepted Inputs

- Microsoft Sentinel Incident ID
- Microsoft Defender XDR Incident ID

# Threat Hunting Workflow

The agent performs:

- Entity correlation
- User and device investigation
- Process and file analysis
- Indicator and IOC analysis
- Threat intelligence enrichment
- Attack chain reconstruction
- MITRE ATT&CK mapping
- Timeline analysis
- Recommendation generation

# Output Structure

Every successful execution produces:

- Executive Summary
- Hunt Findings
- Entity Analysis
- Threat Intelligence Insights
- MITRE ATT&CK Mapping
- Attack Timeline
- Critical Evidence
- Recommended Actions
- Final Threat Hunting Assessment

# Security and Architecture Guardrails

- Read-only enforcement.
- No containment actions.
- No incident modifications.
- No fabricated evidence.
- Evidence-based reasoning only.
- Automatic source detection.
- Production-safe architecture.

# Supported Use Cases

- Threat hunting investigations
- Advanced incident investigations
- IOC analysis
- Malware investigations
- Lateral movement analysis
- Persistence analysis
- Insider threat investigations
- Threat intelligence enrichment

