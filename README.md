# Dynamic Data and Capabilities in IPFS Working Group

[![#ipfs-dynamic-data](https://img.shields.io/badge/irc-%23ipfs--dynamic--data-brightgreen.svg)](https://webchat.freenode.net/?channels=ipfs-dynamic-data)

> Research and development of building blocks that enable collaborative applications, providing solutions for security, identity, access control, concurrency, synchronization, offline and near-real-time collaboration on top of IPFS.

## Responsibilities include

- Research and implement CRDTs on top of IPFS, creating building blocks that can be used by other applications.
- Research Cryptographic ACLs (Capabilities Systems) and create building blocks that implement.
- Apply this research and implementation to products like PeerPad, validating the solutions and defining new problems to be solved.

## Bi-Weekly Sync

Join us on our bi-weekly calls. For that, check out [the global IPFS community calendar](https://calendar.google.com/calendar/embed?src=ipfs.io_eal36ugu5e75s207gfjcu0ae84@group.calendar.google.com&ctz=UTC). [Issue describing next meeting](https://github.com/ipfs/dynamic-data-and-capabilities/issues/36).

## Current Status

[![Waffle.io - Columns and their card count](https://badge.waffle.io/ipfs/dynamic-data-and-capabilities.svg?columns=all)](https://waffle.io/ipfs/dynamic-data-and-capabilities)

## Accomplishments and current endeavours

- [Peer-Star](https://github.com/ipfs-shipyard/peer-star-app): a library to help create DApps on top of IPFS.
- [Peer-Pad](https://peerpad.net): a decentralized editor that allows concurrent writing of text. Besides making live changes to a given document, it allows read-only nodes to follow the changes in real-time. It also allows you to publish a self-contained snapshot of the document to IPFS.
- [delta-crdts](https://github.com/ipfs-shipyard/js-delta-crdts#delta-crdts): delta-state-based CRDTs in JavaScript.
- 2 research RFPs:
  - [Optimize storage and convergence time in causal CmRDTs](https://github.com/protocol/research/issues/9)
  - [Decentralised Access Control in CRDTs](https://github.com/protocol/research/issues/8)
- [Identity RFC](https://github.com/ipfs-shipyard/peer-star/blob/c249510b4873a9a4b58b245bf97dbe48513a2689/docs/rfc-identity.md): an identity management system for DApps.
- [Discussify](https://github.com/ipfs-shipyard/discussify/): Fully decentralized platform for discussing anything on the web.

## Chronology

- **Jul 2018:** [PeerPad](https://peerpad.net/) now uses [peer-star-app](https://github.com/ipfs-shipyard/peer-star-app).
- **Jun 2018:** created [peer-star-app](https://github.com/ipfs-shipyard/peer-star-app).
  - Peer-Star App support for real-time collaborative DApps built on top of IPFS.
- **Jun 2018:** published [Identity RFC](https://github.com/ipfs-shipyard/peer-star/blob/c249510b4873a9a4b58b245bf97dbe48513a2689/docs/rfc-identity.md).
  - Identity management system for DApps.
- **May 2018:** Published [delta-crdts](https://github.com/ipfs-shipyard/js-delta-crdts).
  - Delta state-based CRDTs in Javascript NPM package.
- **Apr 2018:** Launched 2 CRDT research RFPs.
  - [Optimize storage and convergence time in causal CmRDTs](https://github.com/protocol/research/issues/9).
  - [Decentralised Access Control in CRDTs](https://github.com/protocol/research/issues/8).
- **Apr 2018, 📍 Lisbon:** Held CRDT research day mini-conf.
- **Apr 2018:** started Working Group bi-weekly call.
- **Mar 2018:** created [peer-star](https://github.com/ipfs-shipyard/peer-star).
  - Distributed Applications and their internal building blocks exposed as reusable components that can be used for all kinds of p2p use-cases.
- **Mar 2018:** [Dynamic Data and Capabilities Working Group](https://github.com/ipfs/dynamic-data-and-capabilities) was born.
  - Research and development of building blocks that enable collaborative applications, providing solutions for security, identity, access control, concurrency, synchronization, offline and near-real-time collaboration on top of IPFS.
- **Oct 2017:** [PeerPad](https://peerpad.net/) MozFest 2017 demo.
  - Fully decentralised private collaborative text editor.
- **Jun 2017, 📍 Rome:** 2017 IIIF conference demo.
  - Two different products implementing IIIF were demoed using [ipfs-iiif-db](https://github.com/ipfs-shipyard/ipfs-iiif-db) to sync annotation data between them.
- **Jun 2017:** created [ipfs-iiif-db](https://github.com/ipfs-shipyard/ipfs-iiif-db).
  - Allowing syncing [IIIF](http://iiif.io/) annotation data in a truly server-less and conflict-free way.
- **May 2017:** first version of [y-ipfs-connector](https://github.com/ipfs-shipyard/y-ipfs-connector#readme).
  - A connector that allows Y.js, the CRDT library, to use the IPFS network.
- **Mar 2017:** created [Research CRDT](https://github.com/ipfs/research-CRDT).
  - Gathering research papers and discussions.

## Contributing

There are several ways you can get involved:

* Join our [#ipfs-dynamic-data IRC Channel](https://webchat.freenode.net/?channels=ipfs-dynamic-data)
* Join us on our bi-weekly calls. For that, check out [the global IPFS community calendar](https://calendar.google.com/calendar/embed?src=ipfs.io_eal36ugu5e75s207gfjcu0ae84@group.calendar.google.com&ctz=UTC). [Issue describing next meeting](https://github.com/ipfs/dynamic-data-and-capabilities/issues/36).
* Check out [the working group challenges](https://github.com/ipfs/dynamic-data-and-capabilities/issues) and see how you can help contribute.
