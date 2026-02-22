# Justyn Clark Network

Independent technology and media systems studio.

JCN designs, builds, and operates long-lived platforms across software and media.  
The focus is deterministic execution, explicit state, and systems that remain understandable years later.

---

## Core Systems

### SMALL
A formal execution protocol for AI-assisted work.  
Defines intent, constraints, plan, progress, and handoff as durable artifacts.  
Resumable. Auditable. Tool-agnostic.

### Loopexec
A bounded loop runner built on SMALL.  
Enforces controlled execution cycles with explicit state transitions and machine-readable output.

### Musketeer
A multi-model orchestration CLI.  
Coordinates specialized AI agents with clear contracts and handoffs instead of overloading a single model.

### SchemaFoundry
A curated library of production-ready database schemas.  
Includes Prisma, Drizzle, SQLAlchemy, Ecto, Go structs, and Rust equivalents.  
Designed for real systems, not demos.

### JCN DAW
A deterministic audio engine and tooling stack.  
Focused on reproducible media workflows and explicit command architecture.

---

## Installation

Official distribution channels are maintained under the JCN organization.

### Homebrew

```bash
brew tap justynclarknetwork/homebrew-tap
brew install loopexec
````

### Direct Install (Example)

```bash
curl -fsSL https://loopexec.dev/install.sh | bash
```

Refer to each project repository for platform-specific instructions and checksum verification.

---

## Design Principles

* Systems over features
* Contracts over conventions
* Explicit state over implicit behavior
* Reproducibility over convenience
* Durability over trend

Everything published under JCN is intended to be composable, inspectable, and operationally boring.

---

## Ecosystem

Each repository is designed to stand alone while integrating cleanly with the others.
No hidden coupling. No chat-only knowledge. No magic.

Start with SMALL to understand the execution model.
Use Loopexec to run bounded workflows.
Use Musketeer to coordinate agents.
Use SchemaFoundry to ground data models.

The tools are independent. The architecture is coherent.

