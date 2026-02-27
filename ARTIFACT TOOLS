1️⃣ What is an Artifact?

Artifact = Build output

Examples:

.jar

.war

.ear

.zip

.tar

Docker image

Helm chart

👉 After build stage, artifacts store cheyyali future deployments kosam.

2️⃣ Why Artifact Repository is Needed?

Without artifact repo:

Version control kashtam

Rollback problem

Duplicate builds

No centralized storage

With artifact repo:

Versioned storage

Secure access

CI/CD integration

Immutable builds

3️⃣ Types of Artifacts
🔹 Binary Artifacts

JAR, WAR

EXE files

Libraries

🔹 Container Artifacts

Docker images

🔹 Infrastructure Artifacts

Terraform modules

Helm charts

4️⃣ Popular Artifact Repository Tools
🟢 JFrog Artifactory

Universal repository

Supports Maven, npm, Docker, Helm

High enterprise usage

Metadata management

🔵 Nexus Repository

Developed by Sonatype

Supports Maven, Docker, npm

Open-source version available

🟣 AWS CodeArtifact

Managed service

Integrates with AWS services

Supports Maven, npm, pip

🟡 Docker Hub

Public container registry

Stores Docker images

🟠 GitHub Packages

Integrated with GitHub

Supports multiple package formats

5️⃣ Artifact Repository Architecture
Developer → SCM → CI Tool → Build → Artifact Repo → Deploy
6️⃣ Artifact Lifecycle

Code Commit

Build Trigger

Artifact Generated

Upload to Repository

Version Tagging

Deployment

Rollback (if needed)

7️⃣ Repository Types
📦 Hosted Repository

Stores your own artifacts

🌍 Proxy Repository

Caches external dependencies

🔄 Virtual Repository

Combines multiple repositories

8️⃣ Versioning Concepts

Semantic Versioning (1.0.0)

Snapshot versions

Release versions

Immutable artifacts

9️⃣ Security Concepts

Role-based access control

Repository permissions

Token-based authentication

Vulnerability scanning (integration)

🔟 CI/CD Integration

Works with:

Jenkins

GitHub Actions

GitLab CI

Azure DevOps

Pipeline Example:
Build → Unit Test → Package → Upload Artifact → Deploy
1️⃣1️⃣ Container Registry Concepts

Docker image tagging

Private vs Public registry

Image pull & push

Registry authentication

Image retention policy

Examples:

Amazon ECR

Harbor

1️⃣2️⃣ Dependency Management

Centralized dependency storage

Proxy for Maven Central

Caching external packages

Reducing build time

1️⃣3️⃣ Real-Time DevOps Use Case

Developer pushes code

Jenkins builds project

JAR file generated

Uploaded to Nexus

Deployment server pulls artifact

Deploy to staging

Promote to production

1️⃣4️⃣ Rollback Strategy

Maintain version history

Deploy previous stable version

Immutable artifact strategy

1️⃣5️⃣ Best Practices

Never deploy directly from build server

Use versioned artifacts

Separate snapshot & release repos

Enable access control

Backup repository database
