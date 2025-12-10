# Overview

## Current

```mermaid
flowchart LR
  subgraph Mitre
    E --> F(IntrusionSet)
  end
    E(AttackPattern) -->|isIdentifiedBy| D
    C -->|isIdentifiedBy| D[Attack Pattern ID<br>E.g., 1234]
    C(AttackPattern) -->|relatedToWeakness| B
  subgraph Nist
    G(Product) -->|isAffectedBy| A
    A(Vulnerability) -->|relatedToWeakness| B(Weakness)
  end
```

Currently, attack patterns are from two different sources. These attack patterns have matching identifiers and are currently minted as two unique objects linked via their matching identifier.

## Ideal

```mermaid
flowchart LR
  A(Product) -->|isAffectedBy| B(Vulnerability)
  B -->|relatedToWeakness| C(Weakness)
  D(AttackPattern) -->|relatedToWeakness| C
  D(AttackPattern) -.-> F(AttackPattern)
  D --> E(IntrusionSet)
  F -.-> E
```

Moving forward, attack patterns will be minted as one object or linked via an object property.
