---
type: Entry Point
title: meta
description: System-maintenance package for drift review, audit, repair, and revision policy.
tags: [meta, upkeep, self-audit, maintenance, revision, okf]
okf_version: "0.1"
status: draft
---

# meta

`meta` is the system-maintenance layer of an Architectonic constitution.

Install it with:

```bash
npx architectonic add meta
```

Optional addon for knowledge-heavy systems:

```bash
npx architectonic add living-knowledge
```

## Role

`meta` records how a system checks its own condition, detects drift, reviews failures, maintains artifacts, and revises procedures.

It does not grant a system authority to change its own purpose, boundaries, or permissions. Material changes remain subject to the authority and review rules defined elsewhere in the stack.

## Boundary

`meta` is not general knowledge about the world. That belongs in `knowledge`.

`meta` contains knowledge about the system itself: known weaknesses, review cadence, maintenance procedures, failure modes, verification evidence, and revision policies.

A meta artifact should exist only when it changes future maintenance, preserves verification evidence, defines a review boundary, or prevents a recurring mistake. Routine history belongs in version control or operational logs.

## Relationship to the stack

```text
constitution      = root scaffold
doctrine          = sets the governing rules for maintenance
identity          = defines who may audit, approve, or intervene
project           = supplies operating context for upkeep
skills            = supplies reusable maintenance procedures
knowledge         = records reviewed claims and evidence
meta              = records system condition, drift, maintenance, and revision policy
living-knowledge  = optional addon for campaign-based corpus maintenance
```

## Core file

```text
meta.md -- root system-maintenance contract
```
