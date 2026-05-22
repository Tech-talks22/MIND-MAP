1️⃣ Introduction to SonarQube

SonarQube

Open-source Static Code Analysis tool

Detects Bugs, Vulnerabilities & Code Smells

Improves Code Quality & Security

Supports multiple programming languages

Integrates with CI/CD pipelines

2️⃣ Core Purpose

Maintainable Code

Secure Code

Reliable Code

Continuous Code Inspection

3️⃣ SonarQube Architecture

Developer → SCM → CI Tool → SonarQube Scanner → SonarQube Server → Database


Components:
🔹 SonarQube Server

Processes analysis reports

Displays dashboard

Applies Quality Gates

🔹 SonarQube Scanner

Scans source code

Sends report to server

🔹 Database

Stores metrics & results

PostgreSQL recommended

🔹 Web UI

Project dashboard

Issue tracking

Metrics visualization

4️⃣ Key Concepts
✅ Project

Each code repository analyzed separately

✅ Quality Profile

Set of coding rules

Language-specific

Customizable

✅ Quality Gate

Conditions like:

No new bugs

Coverage > 80%

No critical vulnerabilities

If failed → Pipeline fails

✅ Issues

Bugs

Vulnerabilities

Code Smells

5️⃣ Code Quality Metrics

| Metric          | Meaning                |
| --------------- | ---------------------- |
| Bugs            | Logic errors           |
| Vulnerabilities | Security risks         |
| Code Smells     | Maintainability issues |
| Coverage        | % of code tested       |
| Duplications    | Repeated code          |
| Technical Debt  | Estimated fix time     |
| Complexity      | Cyclomatic complexity  |


6️⃣ Security Concepts

SAST (Static Application Security Testing)

OWASP Top 10 rule detection

Secret detection

Injection vulnerability detection

Hardcoded credentials detection

7️⃣ Branch & PR Analysis

Main branch analysis

Feature branch analysis

Pull Request decoration

New Code vs Overall Code concept

8️⃣ CI/CD Integration

Works with:

Jenkins

GitHub Actions

GitLab CI

Azure DevOps

Pipeline Flow:
Build → Test → Sonar Analysis → Quality Gate → Deploy

9️⃣ Installation Methods

Standalone (Linux VM)

Docker container

Kubernetes deployment

Cloud version → SonarCloud

🔟 SonarQube in Kubernetes

Deploy SonarQube Pod

Use Persistent Volume

Expose via Service

Ingress for external access

Configure PostgreSQL database

1️⃣1️⃣ Authentication & Authorization

Local authentication

LDAP integration

SSO integration

Role-based access control (RBAC)

Project-level permissions

1️⃣2️⃣ Rule Engine

Language-specific rules

Severity levels:

Blocker

Critical

Major

Minor

Info

Custom rule creation (Enterprise)

1️⃣3️⃣ Analysis Types

Full scan

Incremental scan

Branch scan

Pull Request scan

1️⃣4️⃣ Reporting & Dashboards

Code health overview

Technical debt graph

Issue distribution

Coverage trend

Duplication percentage

1️⃣5️⃣ Real-Time DevOps Use Case

Developer pushes code to repository

CI tool triggers build

Tests run

SonarQube analysis starts

Quality Gate evaluated

If PASS → Deploy

If FAIL → Stop deployment

1️⃣6️⃣ Common Problems & Troubleshooting

Scanner authentication error

Database connection issue

Quality gate not failing build

High memory usage

Large project scan timeout



