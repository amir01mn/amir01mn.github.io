---
layout: page
title: Batch-File-Reconciler
description: A Java CLI for bulk file comparison across two source directories — delimited & fixed-width support, streaming I/O, JSON/CSV mismatch reports, CI/CD-friendly exit codes.
img: assets/img/2.jpg
importance: 2
category: work
giscus_comments: false
---

**Stack:** Java · Maven · JUnit

**Timeline:** May 2025

## Overview

A Java command-line tool for **bulk file reconciliation** across two source directories. Built for high-volume batch processing pipelines that need to validate that two systems produced identical (or expected-to-differ) outputs — the kind of problem I cut my teeth on at Moneris.

## Highlights

- **Format flexibility** — supports both delimited (CSV/TSV/pipe) and fixed-width record formats with configurable field-level normalization (trim, case, decimal scale, etc.).
- **Memory-efficient** — streaming I/O so files larger than available memory still reconcile cleanly. Optional multi-threaded execution for throughput on multi-core hosts.
- **Schema-driven** — comparison logic is declared in a schema with header / trailer handling and per-field comparison rules.
- **CI/CD-ready** — emits structured JSON and CSV mismatch reports and returns standard exit codes so it slots straight into pipelines and nightly jobs.

[GitHub](https://github.com/amir01mn/Batch-File-Reconciler)
