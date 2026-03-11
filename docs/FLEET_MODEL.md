# Fleet Model

Node Port Stop treats fleet management as more than inventory and remote control.

A useful fleet model should answer not only what a node is, but also whether it is current, trusted, connected, active, drifting, or acting outside expected boundaries.

## Fleet questions this project is built to support

- What nodes exist?
- Which nodes are healthy?
- Which nodes are current?
- Which nodes are stale?
- Which nodes are trusted?
- Which nodes are drifting?
- Which nodes contacted a given resource?
- Which nodes are related as peers or relays?
- Which user sessions originated from which nodes?
- Which nodes are allowed to perform which classes of action?

## Node classes

Examples of node classes include:

- workstation
- laptop
- server
- appliance
- relay
- verifier
- edge device
- storage participant
- field unit
- local runtime

## Fleet outcomes

A strong fleet model should make it possible to determine:

- whether a node should be admitted
- whether a node should be observed more closely
- whether a node should be restricted
- whether a node is safe to trust in a certain role
- whether a node has become operationally risky
