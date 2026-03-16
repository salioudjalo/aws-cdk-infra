# AWS CDK Infrastructure

Infrastructure components and patterns built with AWS CDK (TypeScript).

## Stack

- AWS CDK (TypeScript)
- AWS CloudFormation
- Node.js

## Repository Structure

- **bin/** – Entry point of the CDK application  
- **lib/** – Infrastructure stack definitions  
- **test/** – Unit tests

## Useful Commands

- **Build the project**
`npm run build`
- **Synthesize the CloudFormation template**
`npx cdk synth`
- **Deploy the stack to AWS**
`npx cdk deploy`
- **See infrastructure changes before deployment**
`npx cdk diff`

## Purpose

This repository contains infrastructure patterns including:

- secure S3 buckets
- infrastructure modules
- reusable stack components
- AWS service integrations

## Author

Saliou Djalo  
Cloud / DevOps Engineer