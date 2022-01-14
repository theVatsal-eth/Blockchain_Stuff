# Keys
Keys are an important part of any [[Blockchain]]
**Private Key** are only known to the key holder, it's used to "sign" transactions.
**Public Key** are the ones that everyone else can see and verify the transaction is signed by a specific individual. They are derived from private key.

![[Pasted image 20211018000517.png]]

## Signatures
A signature ensures that a transaction is done by a specific individual.
When we sign a transaction in a blockchain with our private key, it creates message signature from *Elleptic Curve Digital Signature Algorithm*. The power of this algorithm is that it can create a message signature with private key, but no one can derive your private key from this signature.

![[Pasted image 20211018001247.png]]

After we sign the transaction, anyone can then verify that it is signed by a legit transactioner.

![[Pasted image 20211018001325.png]]

Same goes for a transaction:

![[Pasted image 20211018001420.png]]

![[Pasted image 20211018001500.png]]

**Signing transaction**: A "one way" process where someone with a private key signs a transaction by their private key being hashed with their transaction data.