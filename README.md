---
type: Entry Point
title: meta
description: System-maintenance package for drift review, audit, repair, and revision policy.
tags: [meta, upkeep, self-audit, maintenance, revision, okf]
okf_version: "0.1"
status: draft
---

# meta

```bash
npx architectonic add meta
```

`meta` records how a system checks its own condition, detects drift, reviews failures, maintains artifacts, and revises procedures.

It does not grant a system authority to change its own purpose, boundaries, or permissions. Material changes remain subject to the authority and review rules defined elsewhere in the stack.

## In the ensemble

```text
constitution      composition contract for the ensemble
doctrine          purpose, principles, ontology, epistemology, ethics, governance, incentives
identity          actors, roles, authority, delegation, incentives, privacy
project           operating-unit context, sources, decisions, risks, continuity
skills            reusable procedures, verification, failure handling
knowledge         claims, sources, evidence, uncertainty, known unknowns
models            model metadata, evaluations, capability requirements, routing policy
agents            software actors composed from identity, skills, models, knowledge, permissions
living-knowledge  optional: governed maintenance of frequently changing corpora
meta              audit, upkeep, drift review, revision policy
```

`meta` is not general knowledge about the world. It contains knowledge about the system itself: known weaknesses, review cadence, maintenance procedures, failure modes, verification evidence, and revision policies.

## Commands

```bash
npx architectonic add meta
npx architectonic add meta --source npm
npx architectonic init
npx architectonic list
npx architectonic doctor
```

CLI: https://github.com/architectonic/architectonic

## Boundary

A meta artifact should exist only when it changes future maintenance, preserves verification evidence, defines a review boundary, or prevents a recurring mistake. Routine history belongs in version control or operational logs.

## Core file

```text
meta.md   root system-maintenance contract
```
