1️⃣ Ansible Basics

What is Ansible

Why Ansible?

Configuration Management

Provisioning vs Configuration

Ansible vs Chef vs Puppet

2️⃣ Ansible Architecture

Control Node

Managed Nodes

Inventory

Modules

Plugins

3️⃣ Ansible Installation & Setup

Ansible on Linux

Ansible on Windows

Ansible Configuration File (ansible.cfg)

SSH Key-based Authentication

4️⃣ Inventory

Static Inventory

Dynamic Inventory

Inventory File Format

Groups & Hosts

Host Variables

Group Variables

5️⃣ Ansible Ad-Hoc Commands

What are Ad-Hoc Commands?

Use cases

Common Ad-Hoc Examples

ping

shell

command

copy

yum / apt

6️⃣ Ansible Playbooks

What is a Playbook

YAML Basics

Playbook Structure

Plays

Tasks

Handlers

7️⃣ Ansible Modules

Core Modules

System Modules

File Modules

Package Modules

Service Modules

Cloud Modules

8️⃣ Variables in Ansible

Defining Variables

Variable Precedence

Host Vars

Group Vars

Facts

Extra Vars

9️⃣ Facts & Gathering Facts

What are Facts?

setup module

Custom Facts

Using Facts in Playbooks

🔟 Ansible Templates (Jinja2)

What is Jinja2

Variables in Templates

Conditionals

Loops

Filters

1️⃣1️⃣ Conditionals & Loops

when condition

with_items

loop

until

retries & delay

1️⃣2️⃣ Handlers

What are Handlers

notify keyword

Use cases (restart services)

1️⃣3️⃣ Roles

What is a Role

Role Directory Structure

Default Vars

Role Dependencies

Reusability

1️⃣4️⃣ Ansible Vault

What is Vault

Encrypt files

Encrypt variables

Vault password

Best practices

1️⃣5️⃣ Ansible Configuration Management

Desired State Configuration

Idempotency

State Enforcement

1️⃣6️⃣ Ansible Tags

What are Tags

Selective play execution

Skipping tasks

1️⃣7️⃣ Error Handling

ignore_errors

failed_when

block / rescue / always

Debug module

1️⃣8️⃣ Ansible Plugins

Connection Plugins

Callback Plugins

Lookup Plugins

Filter Plugins

1️⃣9️⃣ Ansible for Cloud & DevOps

Ansible with AWS

Ansible with Azure

Ansible with GCP

Ansible with Docker

Ansible with Kubernetes

2️⃣0️⃣ Ansible Security Best Practices

SSH key authentication

Vault usage

Least privilege

No hardcoded secrets

2️⃣1️⃣ Ansible Performance Tuning

Forks

Async & Poll

Pipelining

Fact caching

2️⃣2️⃣ Ansible Testing & Debugging

ansible-lint

Syntax check

Dry run (--check)

Verbose mode (-vvv)

2️⃣3️⃣ Ansible vs Other Tools

Ansible vs Chef

Ansible vs Puppet

Ansible vs Terraform

2️⃣4️⃣ Ansible Best Practices

Role-based structure

Small reusable playbooks

Clear variable naming

Version control

2️⃣5️⃣ Real-Time Ansible Use Cases

Server configuration

Application deployment

Patch management

CI/CD automation

Kubernetes cluster setup
