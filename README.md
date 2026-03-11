# Node Port Stop

Node Port Stop is a governed node identity, contact, topology, and fleet visibility system.

It models nodes as first-class actors in a trusted environment so systems can answer a simple but critical set of questions:

- who acted
- from what node
- under what authority and policy
- against what resource
- through what contact path
- with what resulting proof

Node Port Stop is designed for environments where attribution, fleet awareness, and node-to-resource visibility matter as much as raw connectivity.

## Why it exists

Most infrastructure can tell you that a machine is online, that software is installed, or that a service responded.

Node Port Stop is built to answer deeper operational questions:

- which node performed an action
- which user session was involved
- what the node was allowed to do at that time
- what resources it contacted
- what peer relationships existed
- whether the node was healthy, current, trusted, or drifting
- what evidence proves that state

This makes Node Port Stop useful for governed infrastructure, distributed systems, field devices, secure operations, and environments where node behavior must be attributable and inspectable.

## What a node means here

In Node Port Stop, a node is not just a machine.

A node is a governed execution and contact identity.

A node may represent:

- a workstation
- a laptop
- a server
- an appliance
- a relay
- a verifier
- a storage participant
- an edge device
- a local runtime
- a field unit

## Core capabilities

Node Port Stop centers on a few core capabilities:

- node identity
- node enrollment and trust state
- heartbeat and health visibility
- node-to-resource contact tracking
- node-to-node adjacency and topology awareness
- session linkage and actor attribution
- capability and policy state visibility
- transfer and attestation receipts
- fleet-wide awareness of state, drift, and contact history

## Operational model

Node Port Stop connects these layers of reality:

- human actor
- session
- node
- organization or trust domain
- resources, peers, and networks
- recorded events and receipts
- authority and verification systems

This allows important activity to be described consistently as:

actor + session + node + target + authority + proof

## Core object model

The public object model currently centers on:

- node identity
- heartbeat
- health report
- contact event
- session event
- topology adjacency
- capability state
- policy state
- transfer receipt
- attestation receipt

These objects make it possible to build a durable and inspectable picture of node behavior across a fleet or network.

## Where it fits

Node Port Stop is intended to work alongside systems that handle:

- trust and identity
- policy enforcement
- event recording
- verification
- transport and exchange
- operational visibility

It is especially valuable when a broader platform needs a strong node layer to connect people, systems, and resources through attributable machine activity.

## Example questions Node Port Stop helps answer

- Which node contacted this resource?
- Which user session originated that action?
- Was that node healthy and current at the time?
- What policy state was active?
- Which peers was the node connected to?
- What receipts prove the event path?
- Is this node trusted to act, verify, relay, or store?

## Initial documentation

See the docs folder for the current public project shape:

- `docs/OVERVIEW.md`
- `docs/ARCHITECTURE.md`
- `docs/OBJECTS.md`
- `docs/FLEET_MODEL.md`
- `docs/INTEGRATIONS.md`

## Status

Node Port Stop is being built as a foundational node layer for systems that need governed fleet visibility, attributable action, and trustworthy node contact modeling.

## License

Add the license that matches your release plan.
