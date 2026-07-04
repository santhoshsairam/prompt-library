# Project: Design and Build a Production-Grade Food Delivery Platform

I want you to act as a Principal Software Architect, Cloud Architect, DevOps Architect, Security Architect, SRE, and Platform Engineer.

Do NOT immediately start coding.

Instead, guide me through designing an enterprise-scale food delivery platform similar to Uber Eats, Swiggy, DoorDash, or Zomato.

The goal is NOT only to build the application but to understand every engineering decision behind it.

I want to learn:

- Software Architecture
- Cloud Architecture
- DevOps
- Kubernetes
- CI/CD
- Security
- Scalability
- High Availability
- Reliability Engineering
- Monitoring
- Cost Optimization
- Disaster Recovery
- Platform Engineering

Treat this as if a real company hired us to build the system from scratch.

---

# Phase 1 - Requirements Gathering

First help identify:

- Functional requirements
- Non-functional requirements
- Business requirements
- Performance requirements
- Security requirements
- Compliance requirements
- Availability requirements
- Disaster Recovery requirements
- Cost constraints

Example questions:

- Expected daily users?
- Peak concurrent users?
- Orders per second?
- Restaurants?
- Delivery partners?
- Admin users?
- Countries supported?
- Payment methods?
- Languages?
- Notifications?
- Search?
- Recommendations?

Do not skip this phase.

---

# Phase 2 - High Level Architecture

Design the complete architecture.

Show:

- Client applications
- Backend
- Databases
- Storage
- Authentication
- Payment
- Maps
- Notification systems
- Analytics
- Monitoring
- Logging
- CI/CD
- Infrastructure

Explain WHY every component exists.

---

# Phase 3 - Repository Strategy

Help decide repository structure.

Examples:

- Monorepo
- Polyrepo

If polyrepo,

list every repository.

Example:

frontend-web

customer-mobile

restaurant-mobile

delivery-mobile

admin-portal

api-gateway

authentication-service

restaurant-service

menu-service

order-service

payment-service

delivery-service

notification-service

search-service

recommendation-service

inventory-service

promotion-service

user-service

review-service

location-service

config-repository

helm-charts

terraform

github-actions

documentation

shared-libraries

sdk

Explain why each repository exists.

---

# Phase 4 - Microservices

Design all microservices.

For each service explain:

Purpose

Responsibilities

Database

API

Dependencies

Scaling strategy

Communication

Technology

Stateful or Stateless

Caching

Expected traffic

Failure scenarios

Retry strategy

Circuit breakers

---

# Phase 5 - Technology Selection

Choose technologies.

Prefer mature, popular open-source technologies.

Explain WHY each one is selected.

Compare alternatives.

Examples:

Programming Language

Java

Go

NodeJS

Python

Rust

C#

Framework

Spring Boot

Express

FastAPI

Gin

Database

PostgreSQL

MySQL

MongoDB

Redis

ElasticSearch

Kafka

RabbitMQ

NATS

gRPC

REST

GraphQL

Object Storage

MinIO

AWS S3

Azure Blob

---

# Phase 6 - Infrastructure

Design infrastructure.

Questions to answer:

How many servers initially?

How many Kubernetes nodes?

Node sizing?

Worker nodes?

Control plane?

Autoscaling?

Storage?

Persistent volumes?

Ingress?

Networking?

DNS?

TLS?

Firewalls?

Load balancers?

Availability Zones?

Multi-region?

Virtual Networks?

Private/Public subnets?

NAT Gateway?

Service Mesh?

---

# Phase 7 - Containerization

Explain:

Dockerfile design

Multi-stage builds

Image optimization

Security scanning

Base image selection

Image signing

Image registry

Versioning

Immutable images

---

# Phase 8 - Kubernetes Design

Design production Kubernetes.

Namespaces

Deployments

DaemonSets

StatefulSets

Jobs

CronJobs

Services

Ingress

ConfigMaps

Secrets

Persistent Volumes

PVC

Storage Classes

Network Policies

Horizontal Pod Autoscaler

Vertical Pod Autoscaler

Cluster Autoscaler

Pod Disruption Budget

Affinity

Anti-affinity

Taints

Tolerations

Resource Limits

Requests

RBAC

Service Accounts

Admission Controllers

Explain every object.

---

# Phase 9 - Helm

Explain:

Helm chart structure

Parent charts

Subcharts

Values

Templates

Secrets

Versioning

Environment overrides

Release strategy

Rollback

---

# Phase 10 - CI/CD

Design enterprise CI/CD.

For every repository explain:

Branch strategy

Pull Requests

Reviews

Unit Tests

Integration Tests

Static Analysis

Security Scan

Dependency Scan

License Scan

Artifact Build

Container Build

Container Scan

Package

Publish

Deploy

Rollback

Promotion

Approval Gates

Blue Green

Canary

GitOps

Progressive Delivery

---

# Phase 11 - DevSecOps

Explain security from developer laptop to production.

Include:

SAST

DAST

SCA

Container scanning

Secrets scanning

IaC scanning

Image signing

SBOM

Dependency updates

Code signing

Policy as Code

RBAC

Least privilege

Secrets Management

Vault

Kubernetes Secrets

External Secrets

Certificate Management

Key Rotation

Supply Chain Security

Zero Trust

---

# Phase 12 - Infrastructure as Code

Compare:

Terraform

Pulumi

OpenTofu

Ansible

Chef

Puppet

SaltStack

When to use each.

Create enterprise folder structure.

---

# Phase 13 - Configuration Management

Explain:

Environment variables

Secrets

Feature Flags

Spring Config

Config Server

Vault

ConfigMaps

GitOps

Versioning

Dynamic configuration

---

# Phase 14 - Scaling

Explain how the system handles:

100 users

1,000 users

10,000 users

100,000 users

1 million users

10 million users

Explain:

Horizontal Scaling

Vertical Scaling

Database Scaling

Caching

Read Replicas

Sharding

Partitioning

Queueing

Async Processing

Rate Limiting

Backpressure

CDN

Autoscaling

---

# Phase 15 - Observability

Design complete observability.

Metrics

Logging

Tracing

Alerting

Dashboards

SLO

SLI

SLA

Tools:

Prometheus

Grafana

Loki

ELK/OpenSearch

Jaeger

OpenTelemetry

AlertManager

PagerDuty

Explain why.

---

# Phase 16 - Reliability

Design for failures.

Node failures

Pod failures

Zone failures

Database failures

Network failures

Cloud failures

Retry

Circuit Breaker

Bulkhead

Timeouts

Fallbacks

Chaos Engineering

Disaster Recovery

Backup

Restore

RPO

RTO

---

# Phase 17 - Performance

How to support thousands of requests per second.

Connection pooling

Caching

Redis

CDN

Compression

Async APIs

Kafka

Database indexing

Query optimization

Load testing

Stress testing

Profiling

---

# Phase 18 - Security

Authentication

Authorization

JWT

OAuth2

OIDC

SSO

API Gateway

WAF

DDoS protection

TLS

mTLS

Encryption

Audit logs

Compliance

OWASP Top 10

PCI DSS (Payments)

GDPR basics

---

# Phase 19 - Cost Optimization

Explain cost optimization.

Reserved instances

Spot nodes

Autoscaling

Storage optimization

Image optimization

Monitoring costs

Logging retention

Compute optimization

---

# Phase 20 - Documentation

Create documentation for:

Architecture

Runbooks

Developer Guide

Deployment Guide

Incident Response

Production Checklist

Security Checklist

Onboarding Guide

Disaster Recovery

---

# Rules

For every recommendation explain:

1. Why this tool?

2. Why not competitors?

3. Advantages

4. Disadvantages

5. Cost

6. Open-source alternatives

7. Industry adoption

8. Production best practices

9. Common mistakes

10. Real-world examples

Never assume unlimited budget.

Prefer battle-tested open-source tools whenever possible.

Explain concepts visually using ASCII diagrams where appropriate.

Proceed phase by phase and wait for confirmation before moving to the next phase.
