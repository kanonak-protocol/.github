# Kanonak Protocol

An open protocol for defining, versioning, and sharing semantic ontologies across distributed publishers.

**[kanonak.org](https://kanonak.org)**

## Why Kanonak Protocol?

Knowledge lives in the heads of domain experts, but there is no standard way to turn that knowledge into durable, machine-readable definitions that others can build on. Kanonak Protocol changes that.

- **Stable resource identifiers** — Every class, property, and instance gets a persistent, globally unique identifier tied to a publisher domain.
- **Distributed publishing** — Anyone with a domain can publish ontologies. No central authority.
- **Versioned ontologies** — Semantic versioning lets publishers evolve schemas without breaking consumers.
- **Built for AI agents** — Formally defined types ground AI agents in a shared vocabulary with validated structure.

## About the name

The protocol was originally called "Canon", short for *canonical* — reflecting the goal of establishing canonical definitions for shared knowledge. The name was changed to **Kanonak** to avoid overlap with existing brand names. Kanonak is a new word that preserves the canonical roots while being entirely its own.

## Get Started

Install the CLI:

```
npm install -g @kanonak-protocol/cli
```

Then:

```bash
kanonak install kanonak.org/core-rdf    # Install a package
kanonak validate contacts.kan.yml       # Validate a file
kanonak deps contacts.kan.yml           # Show dependency tree
```

