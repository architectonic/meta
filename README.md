# Meta

> **Status: experimental, pre-1.0.** This package defines one layer of the Architectonic protocol. Evaluate it through its canonical contract, package validator, conformance manifest, and explicit limitations.

`meta` defines how the organization inspects and maintains its own operating system.

## What it gives an agent

- one predictable home for this concern;
- a canonical entry that can be found through `architectonic map`;
- a machine-readable `architectonic.protocol.json`;
- boundaries that prevent neighboring layers from silently owning the same concept;
- package validation that runs against both the source checkout and the exact npm tarball.

## Canonical entry

```text
meta.md
```

## Boundary

Meta does not grant authority to rewrite the constitution, expand permissions, or bypass human review.

## Install

```bash
npx architectonic@latest add meta --source npm
npx architectonic@latest verify
```

Installing a layer provides reusable public structure. Organization-specific facts, private knowledge, credentials, runtime state, and local decisions belong only in controlled workspace instances.

## Claims

This package claims only that its declared structure and validators are inspectable and reproducible. It does not claim universal performance improvement or domain correctness.
