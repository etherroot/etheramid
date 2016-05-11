# etheramid
Decentralised social invitation game.

### Multi-level social invitation game.

### Send 1 Ether to enter.

### Invite other participants and get ether back from each pay:
* 1st level - 50%
* 2nd level - 25%
* 3rd level - 12.5%
* 4th level - 6.25%
* 5th level - 3.125%
* 6th level - 1.5625%
* 7th level - 1.5625%

The contract is updated!
New contract address is : 0xfeeb8A968F0d7FD58E29FBfC525051f50eE2FeDC
All users are moved to the new contract for free!
The old contract still works at address 0x9758DA9B4D001Ed2d0DF46d25069Edf53750767a and are accessible by etheramid.cloudapp.net/deprecated
All your invitation links are live.
Read more details.


The previous version of contract randomly selects a network for the new user without inviter. It was right and fair. But some users started not fair play. They created a lot of accounts and built a chain of them, so at the result, they could join the game without sending 1 Ether ( actually they send but it comes back to them using previous accounts in the chain). That allows them to join from many new created accounts and dramatically increase chances to include new user to their network. 
In the new version the user can not just send 1 Ether to join a random network, he should select inviter from the graph (he can select any account) and join with selected inviter.


Join from online wallets:
You can join from online wallets, but you must be sure that deposit address for your wallet and address from which you send Ether(withdraw) are the same. This guarantees you will receive your reward.
Right now there are many online wallets but all of them use one of two schemes:
1) The deposit and withdrawal (sending) operations are done from one address.
2) The deposit and withdrawal (sending) operations are done from different addresses.
The option 1) works with Etheramid, the option 2 - does not work.
For example, let's consider Poloniex exchange, to deposit into Poloniex you should send Ether to the generated address for you by Poloniex, but when you withdraw Ether the transaction is initiated from global Polonies account (wallet) not generated address. So it does not suit to Etheramid.
As everything is based on Ethereum blockchain, that could be live infinitely, you have good chances to win even doing nothing. Just be first.

### The visualization of network you can check on etheramid.cloudapp.net

### Contract ABI / JSON Code

[{"constant":true,"inputs":[{"name":"id","type":"uint256"}],"name":"getParticipantById","outputs":[{"name":"inviter","type":"address"},{"name":"itself","type":"address"},{"name":"totalPayout","type":"uint256"}],"type":"function"},{"constant":true,"inputs":[],"name":"getParticipantCount","outputs":[{"name":"count","type":"uint256"}],"type":"function"},{"constant":false,"inputs":[{"name":"inviter","type":"address"}],"name":"enter","outputs":[],"type":"function"},{"constant":false,"inputs":[{"name":"id","type":"uint256"}],"name":"moveOldUser","outputs":[],"type":"function"},{"constant":true,"inputs":[{"name":"adr","type":"address"}],"name":"getParticipantByAddress","outputs":[{"name":"inviter","type":"address"},{"name":"itself","type":"address"},{"name":"totalPayout","type":"uint256"}],"type":"function"},{"constant":true,"inputs":[],"name":"top","outputs":[{"name":"","type":"address"}],"type":"function"},{"inputs":[],"type":"constructor"}]
