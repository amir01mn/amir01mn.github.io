---
layout: page
title: Synapse
description: Human-Centered AI Assurance Framework — YorkU × TD Bank capstone scoring Jira user stories against versioned AI/privacy policies in real time.
img: assets/img/1.jpg
importance: 1
category: work
giscus_comments: false
---

**Stack:** Python · FastAPI · TypeScript · NestJS · Next.js · MongoDB · Auth0 · Atlassian Forge

**Timeline:** Sep 2025 – April 2026 · Team of 7 · Client: **TD Bank**

## Overview

Synapse is a Human-Centered AI Assurance Framework built for **TD Bank** as my York University capstone project. It scores Jira user stories in real time against a versioned AI / privacy policy framework, surfacing violations and remediation hints **inline** via an Atlassian Forge plugin so policy review happens where work is already being done — not after the fact.

## What I built

- **Risk-scoring microservice** — Python / FastAPI service powered by OpenAI Structured Outputs and a hierarchical policy schema. Returns deterministic, auditable risk assessments per user story.
- **Policy management API** — NestJS + MongoDB backend with full CRUD, activation workflows, revision history, and Auth0-based RBAC.
- **Admin console** — Next.js front-end for policy authors to draft, version, and activate policies; deployed to Render.
- **Forge plugin** — Embeds the assessment results directly in Jira issue views with severity-coded badges and remediation hints.

## Collaboration

Worked in a multidisciplinary team of 7 (engineering + UX + product) under real client constraints from TD Bank, balancing security, auditability, and developer ergonomics.

[GitHub](https://github.com/amir01mn)
