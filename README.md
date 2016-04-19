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

Or just wait until random selects you for new perticipant without inviter.
As everything is based on Ethereum blockchain, that could be live infinitely, you have good chances to win even doing nothing. Just be first.

### The visualization of network you can check on etheramid.cloudapp.net

### Contract ABI

[{ "constant": true, "inputs": [{ "name": "id", "type": "uint256" }], "name": "getParticipantById", "outputs": [{ "name": "inviter", "type": "address" }, { "name": "itself", "type": "address" }, { "name": "totalPayout", "type": "uint256" }], "type": "function" }, { "constant": true, "inputs": [], "name": "getParticipantCount", "outputs": [{ "name": "count", "type": "uint256" }], "type": "function" }, { "constant": false, "inputs": [{ "name": "inviter", "type": "address" }], "name": "enter", "outputs": [], "type": "function" }, { "constant": true, "inputs": [{ "name": "adr", "type": "address" }], "name": "getParticipantByAddress", "outputs": [{ "name": "inviter", "type": "address" }, { "name": "itself", "type": "address" }, { "name": "totalPayout", "type": "uint256" }], "type": "function" }, { "inputs": [], "type": "constructor" }]
