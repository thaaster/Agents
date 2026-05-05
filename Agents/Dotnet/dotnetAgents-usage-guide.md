
# .NET Multi-Agent Workflow Guide

This document explains how to use the custom .NET agents:

- dotnetArchitect
- dotnetPlanRefiner
- dotnetAgent
- dotnetReviewer
- dotnetFixer

These agents are designed to work together as a structured development workflow.

---

# 🧠 Overview

This setup mimics a real development team:

| Role        | Agent               | Responsibility              |
|------------|--------------------|-----------------------------|
| Architect  | dotnetArchitect     | Creates implementation plan |
| Refiner    | dotnetPlanRefiner   | Improves and simplifies plan|
| Developer  | dotnetAgent         | Writes the code             |
| Reviewer   | dotnetReviewer      | Validates implementation    |
| Fixer      | dotnetFixer         | Applies targeted fixes      |

---

# 🔄 Full Workflow
