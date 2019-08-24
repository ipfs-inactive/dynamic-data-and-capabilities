Creating DApps using Peer Base
-------------------------------

The document as part of dynamic data and capabilities describes how you can
create a DApp on top of IPFS using Peer-Base.

peer-base library can be used for creating DApps. With IPFS large amounts of
data can be addressed placing the immutable, permanent IPFS link in the
blockchain transaction. Enabling timestamping and securing the content without
having to put the data on the chain itself. This enables undisputable proof that
the object existed at the time the entity was uploaded.

A simplest DApp can be to upload a document in IPFS and then store the IPFS hash
on the Ethereum blockchain. Once the IPFS hash number is sent in the Ehtereum
blockchain the user will receive a transaction receipt. The outputs would be as
shown ![here](https://i.gyazo.com/6fa69d66b5a4060b4e82ce542ad75459.png).

In peer-base intead of announcing every peer that is dicovered in the IPFS
layer, filtering is forced. The type will listens `peer:discovery` events and
build a consistent hashring from the peer IDs that are part of the application.
You can read about the protocol
[here](https://github.com/peer-base/peer-base/blob/master/docs/PROTOCOL.md).

For creating the DApp you should

- Install the application
- Define the name in `app.js`
- `src/common/ring.js` has a hash ring of peers. Peers can be added, removed and
	inquired if they belong.


