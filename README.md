[video 2.html](https://github.com/user-attachments/files/28626753/video.2.html)# jobops-deployment-project
Deployed and configured JobOps, an AI-powered job search platform, using Docker and Docker Compose. Integrated Google Gemini API for resume analysis, job matching, and AI-driven recommendations. Demonstrated skills in containerization, troubleshooting, API integration, and self-hosted application deployment in a real-world DevOps environment.
# JobOps Deployment and Configuration Project

## Overview

This repository documents the deployment, configuration, and testing of JobOps, an open-source AI-powered job search and application management platform.

The purpose of this project is to demonstrate practical DevOps skills including Docker containerization, application deployment, AI integration, troubleshooting, and system configuration.

## Project Objectives

* Deploy JobOps using Docker and Docker Compose.
* Configure Google Gemini API as the AI provider.
* Import and analyze resumes.
* Explore AI-powered job matching capabilities.
* Document deployment and troubleshooting procedures.
* Gain hands-on experience with self-hosted applications.

## Architecture

```text
+----------------+
| Resume Upload  |
+--------+-------+
         |
         v
+----------------+
|  Gemini API    |
+--------+-------+
         |
         v
+----------------+
| Resume Parsing |
+--------+-------+
         |
         v
+----------------+
| Skill Analysis |
+--------+-------+
         |
         v
+----------------+
| Job Matching   |
+--------+-------+
         |
         v
+----------------+
| Tracking Board |
+----------------+
```

## Technology Stack

* Docker Desktop
* Docker Compose
* Google Gemini API
* JobOps
* Git
* GitHub
* Windows 11

## Prerequisites

Before starting, install:

* Git
* Docker Desktop
* Google Gemini API Key

Verify installation:

```bash
docker --version
git --version
```

## Deployment Steps

### 1. Clone the Repository

```bash
git clone https://github.com/DaKheera47/job-ops.git
cd job-ops
```

### 2. Start Docker

Verify Docker is running:

```bash
docker ps
```

### 3. Pull the Application Image

```bash
docker pull ghcr.io/dakheera47/job-ops:latest
```

### 4. Start JobOps

```bash
docker compose up -d
```

### 5. Verify Running Containers

```bash
docker ps
```

### 6. Access Application

Open:

```text
http://localhost:3005
```

## AI Configuration

### Gemini API Setup

1. Create a Gemini API key from Google AI Studio.
2. Select Gemini as the LLM provider.
3. Configure the API key during onboarding.
4. Choose a Gemini model.

### Gemini Capabilities

* Resume parsing
* Resume optimization
* Skill extraction
* Job matching
* Application assistance
* AI-powered recommendations

## Resume Import

Supported formats:

* PDF
* DOCX
* Reactive Resume JSON

The uploaded resume is analyzed and transformed into a structured profile for job matching.

## Features Explored

* Resume Management
* Job Search Aggregation
* AI Resume Tailoring
* Job Matching
* Application Tracking
* Interview Tracking
* Dashboard Analytics

## Troubleshooting

### Docker Engine Error

Error:

```text
dockerDesktopLinuxEngine:
The system cannot find the file specified
```

Solution:

```powershell
Start-Service com.docker.service
```

### Application Not Loading

Issue:

```text
http://localhost:3005
```

not accessible.

Solution:

```powershell
docker compose up -d
docker ps
```

### Resume Upload Error

Issue:

AI provider configuration incomplete.

Solution:

* Verify Gemini API Key.
* Verify provider selection.
* Re-upload resume.

## Key Learnings

* Docker Container Management
* Docker Compose Orchestration
* Self-Hosted Application Deployment
* Gemini API Integration
* Troubleshooting Containerized Applications
* DevOps Workflow Fundamentals
* AI-Powered Job Search Systems

## Credits

Original Project:

https://github.com/DaKheera47/job-ops

Thanks to the original JobOps maintainers and contributors for developing the platform.

This repository focuses on deployment, configuration, testing, troubleshooting, and learning outcomes from implementing JobOps.

<img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/a94a0d95-269c-40a4-bfac-4df15e6c8805" />

<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/3f1c6ee4-5e22-4f97-bcf2-c63c28c198dc" />

<img width="1199" height="19" alt="Screenshot 2026-04-23 131739" src="https://github.com/user-attachments/assets/f6f2ee2c-819a-4438-a0e7-ed70f5a398f9" />

<img width="1895" height="892" alt="Screenshot 2026-04-23 131806" src="https://github.com/user-attachments/assets/c9f82499-a4b4-4594-8b48-2745ea2c01e4" />

<img width="1920" height="1020" alt="Screenshot 2026-06-04 164530" src="https://github.com/user-attachments/assets/f717a5e6-05c1-45d4-abfd-6ec908abbc3d" />

<img width="1920" height="1020" alt="Screenshot 2026-06-04 164719" src="https://github.com/user-attachments/assets/ee65f097-0961-4719-b79b-b161ab7f3bf7" />

<img width="1920" height="1080" alt="Screenshot 2026-06-04 164645" src="https://github.com/user-attachments/assets/134e1759-df86-442e-8115-cc7e9d408321" />

<img width="1920" height="1080" alt="Screenshot 2026-06-04 164734" src="https://github.com/user-attachments/assets/e55aeb52-df26-4770-a704-9ca76a035725" />

<img width="1920" height="1080" alt="Screenshot 2026-06-04 164829" src="https://github.com/user-attachments/assets/c9be1aee-97c8-49c3-b58c-3a821abde83b" />

<img width="1920" height="1080" alt="Screenshot 2026-06-04 164847" src="https://github.com/user-attachments/assets/ff201730-47d7-4236-93fb-ae7b842fea6a" />

<img width="1920" height="1080" alt="Screenshot 2026-06-04 164906" src="https://github.com/user-attachments/assets/8dd7513a-82d1-4b5a-8137-05f14ca3905b" />



https://github.com/user-attachments/assets/757b7f2d-f479-4169-bafa-72046d387282

