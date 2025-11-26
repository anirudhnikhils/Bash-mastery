)

🚀 Bash Scripting Mastery – For SRE / DevOps / Cloud / Platform Engineers

This repository contains a complete, practical, production-focused learning path
for mastering Bash scripting at the level required for SRE & DevOps roles.

Bash is essential for:

Debugging Linux systems

Automating routine tasks

CI/CD pipelines

Parsing logs

Chaining infra tools (kubectl, aws, terraform)

Writing quick operational scripts

On-call troubleshooting

📂 Repository Structure
bash-scripting-mastery/
 ├── phase-1-basics/
 ├── phase-2-core-shell/
 ├── phase-3-text-processing/
 ├── phase-4-sre-automation/
 ├── projects/
 ├── interview-questions/
 ├── cheatsheets/
 └── README.md

🟩 PHASE 1 — BASH FOUNDATIONS (Basics Needed for All SREs)
Step 1: What is Shell? Bash vs Zsh vs Sh
Step 2: Variables & environment variables
Step 3: User input (read)
Step 4: Arithmetic operations
Step 5: If-else conditions
Step 6: For loops, While loops
Step 7: Exit codes & error handling
Step 8: Functions in Bash
Step 9: Arrays (SRE level basics)
Step 10: File operations (test, -f, -d, etc.)
🟩 PHASE 2 — CORE SHELL SKILLS (Where SRE Bash is actually used)
Step 11: Understanding PATH, aliases, .bashrc
Step 12: Working with processes
Step 13: Signals & trap (basic SRE usage)
Step 14: Redirection: >, >>, <, 2>
Step 15: Pipes: |
Step 16: Command substitution: `command` & $(...)
Step 17: Cron jobs — scheduling scripts
Step 18: Parsing arguments ($@, $#, $*)
Step 19: Using curl for APIs
Step 20: Using jq for JSON parsing (very important for DevOps)
🟩 PHASE 3 — TEXT PROCESSING (SRE’s MOST IMPORTANT SKILL)

(99% of real Bash interview questions come from here)

Step 21: grep basics + regex
Step 22: awk (print, fields, conditions)
Step 23: sed for find/replace
Step 24: cut, sort, uniq, wc
Step 25: tail, head
Step 26: xargs
Step 27: find (very important)
Step 28: Text pipelines (multi-stage)
Step 29: Log filtering & summarization
Step 30: CSV/TSV parsing
🟩 PHASE 4 — SRE AUTOMATION (Real-World Bash Use Cases)
Step 31: System health check scripts
Step 32: Disk usage monitoring script
Step 33: Log analyzer script
Step 34: Alert script (Slack/email)
Step 35: API automation (curl + jq)
Step 36: Kubernetes automation (kubectl inside Bash)
Step 37: AWS CLI automation
Step 38: Terraform automation wrappers
Step 39: Backup + rotation scripts
Step 40: On-call troubleshooting scripts (practical)
🟧 Hands-on SRE Projects

Log analyzer (top IPs, error rate, summary)

Nginx 500-error alert script

CPU/memory usage alert script

Disk space monitoring tool

Kubernetes pod restart automation

Terraform plan checker script

API health-check CLI tool

Cronjob-based reporting system

System cleanup automation

JSON/YAML validation script

📝 SRE-Level Interview Questions Included
Bash Basics

Difference between shell & bash

Exit codes and pipeline failures

Text Processing

Extract top N IPs from logs

Find slow endpoints from logs

Clean and normalize messy data

DevOps/SRE Workflow

CI/CD step scripting

Automating deployments

Parsing JSON from APIs

Working with multi-line outputs

Troubleshooting

Write script to find top CPU processes

Detect app crash patterns from logs

Monitor disk/memory with alerts

🎯 End Goal

By completing this repository, you will be able to:

✔ Automate routine SRE tasks
✔ Write efficient Bash scripts for CI/CD
✔ Parse logs quickly like a production SRE
✔ Combine kubectl/aws/terraform with Bash
✔ Solve SRE/DevOps Bash interview questions
✔ Understand logs, pipelines, servers deeply# Bash-mastery
