# Architecture

Node Port Stop provides the node layer that connects actors, sessions, machines, resources, peer relationships, and operational proof.

## Core concept

A node is a governed execution and contact identity.

This means a node is the place where action becomes attributable in operational systems.

Without a node layer, a system may know that a user exists and that an event happened. With a node layer, a system can also know where the action occurred, through what machine or runtime context, against what target, and with what surrounding state.

## Topology model

Node Port Stop uses a simple topology model:

Human -> Session -> Node -> Trust Domain -> Resources / Peers / Networks -> Events / Receipts -> Authorities / Verifiers / Ledgers

This allows important actions to be understood through a consistent structure:

actor + session + node + target + authority + proof

## Main responsibility areas

### Identity
Defines the node as a distinct participant.

### State
Captures heartbeat, health, freshness, policy visibility, and trust-relevant status.

### Contact
Captures the node's interaction with resources, peers, and networks.

### Topology
Captures adjacency, peer relationships, and fleet position.

### Attribution
Links sessions and actors to node actions.

### Evidence
Captures receipts and attestation outputs that support the node's operational record.

## Result

The result is a node-aware system that can reason about more than uptime. It can reason about attributable activity, fleet trust, contact pathways, and operational context.
