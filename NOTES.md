NOTES.md


relateD:
- ripple : federated system for currency exchange

- omega block finalization function
Where $\Omega$ is the block-finalisation state transition function (a function that rewards a nominated party); $B$ is this block, which includes a series of transactions amongst some other components; and $\Pi$ is the block-level state-transition function.



\subsection{Random Numbers}
Providing random numbers within a deterministic system is, naturally, an impossible task. However, we can approximate with pseudo-random numbers by utilising data which is generally unknowable at the time of transacting. Such data might include the block's hash, the block's timestamp and the block's beneficiary address. In order to make it hard for malicious miner to control those values, one should use the {\small BLOCKHASH} operation in order to use hashes of the previous 256 blocks as pseudo-random numbers. For a series of 
such numbers, a trivial solution would be to add some constant amount and hashing the result.


- what about the pokerstars proton RNG -> ethereum service.
RNG as a decentralized service

/ future direcitons

