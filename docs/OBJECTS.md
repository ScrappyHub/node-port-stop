# Object Model

Node Port Stop uses a compact object model to describe node reality.

## Node Identity

Describes a node as a durable participant in the system.

Typical fields may include:

- node identifier
- display name
- node class
- enrollment facts
- authority binding
- trust domain
- role or function

## Heartbeat

Describes liveness and freshness.

Typical fields may include:

- node identifier
- observed time
- claimed time
- software/runtime reference
- freshness status

## Health Report

Describes node condition.

Typical fields may include:

- node identifier
- health summary
- subsystem states
- resource pressure
- software/runtime details
- diagnostic references

## Contact Event

Describes contact between a node and a target.

Typical fields may include:

- source node
- target resource, peer, or network
- contact type
- start time
- end time
- outcome
- related session or operation identifier

## Session Event

Describes actor activity through a node.

Typical fields may include:

- session identifier
- actor identifier
- node identifier
- start or end state
- scope or permission context
- result

## Topology Adjacency

Describes a node relationship.

Typical fields may include:

- source node
- target node
- relationship type
- observed or declared status
- time window
- route or channel context

## Capability State

Describes what the node is able or allowed to do.

Typical fields may include:

- node identifier
- capability set
- enabled or disabled state
- source of authority
- effective time

## Policy State

Describes the node's active policy view.

Typical fields may include:

- node identifier
- policy reference
- claimed active state
- observed active state
- drift or mismatch indicators

## Transfer Receipt

Describes movement through a node.

Typical fields may include:

- source
- destination
- transfer class
- transfer result
- timestamps
- related operation identifiers

## Attestation Receipt

Describes a concluded trust or state result about a node.

Typical fields may include:

- node identifier
- verifier or authority
- attestation result
- reasons
- timestamps
- supporting references
