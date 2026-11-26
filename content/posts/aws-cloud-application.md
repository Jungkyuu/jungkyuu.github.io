---
title: "Fragments Cloud Microservice (AWS S3 & DynamoDB)"
date: '2026-11-25T03:00:00-05:00'
draft: false
summary: "A containerized RESTful microservice built with Node.js, Express, AWS S3, and DynamoDB. Configured LocalStack for local cloud emulation, automated 12 API integration tests with Hurl, and built a GitHub Actions CI/CD pipeline for Docker Hub deployment."
tags: ["AWS", "S3", "DynamoDB", "LocalStack", "Docker", "Node.js", "GitHub Actions", "CI/CD"]
---

## Overview

In this project, I built and tested a cloud-based application using AWS services and automation tools. I worked on cloud storage, connecting a NoSQL database, automating 12 API integration tests, and setting up CI/CD workflows with containers.

## Architecture

![Fragments Cloud Microservice Architecture](https://raw.githubusercontent.com/Jungkyuu/fragments-cloud-microservice/main/diagram.png)

## Technologies Used

- **Backend & Auth:** Node.js 22, Express, HTTP Basic Authentication
- **Cloud & Storage:** Amazon S3, Amazon DynamoDB
- **Local Cloud Emulation:** LocalStack, DynamoDB Local
- **Testing & Linting:** Hurl (12 E2E integration suites), ESLint
- **Containerization & CI/CD:** Docker, Docker Compose, GitHub Actions

## Project Highlights

- Integrated Amazon S3 and DynamoDB as core components of the application's cloud infrastructure.
- Utilized LocalStack to emulate AWS services locally for rapid development and testing.
- Automated HTTP-based API integration tests using Hurl.
- Built CI/CD pipelines with GitHub Actions to automate testing and Docker container builds.

## CI/CD & Integration Testing

### GitHub Actions Workflow
![GitHub Actions CI/CD Pipeline](https://raw.githubusercontent.com/Jungkyuu/fragments-cloud-microservice/main/github_action.png)

### Hurl API Integration Tests
![Hurl 12 API Integration Tests Passing](https://raw.githubusercontent.com/Jungkyuu/fragments-cloud-microservice/main/fragments_tests.png)

## What I Learned

This project strengthened my understanding of cloud-native storage patterns, container orchestration, and automated testing in CI/CD pipelines. Emulating AWS services locally with LocalStack and verifying end-to-end API behaviour with 12 automated Hurl suites taught me how to catch integration and permission issues before deployment.

## Links

- [GitHub Repository](https://github.com/Jungkyuu/fragments-cloud-microservice)