# SAP CPI CI/CD — Developer Guide

## Overview

This repository runs an automated quality-gate pipeline for SAP CPI iFlows.
When an iFlow is deployed and marked ready, the pipeline downloads it, runs
**CPILint** (static checks) and **Postman** (runtime tests), and reports the
results. iFlows that fail any gate are **automatically removed** from the branch.

---

## 🔄 The Complete Flow
