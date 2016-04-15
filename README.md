# etheramid
Decentralised social pyramid

### Multi-level pyramid.

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

### Contract ABI

[ { "constant": true, "inputs": [ { "name": "id", "type": "uint256", "index": 0, "typeShort": "uint", "bits": "256", "displayName": "id", "template": "elements_input_uint" } ], "name": "getParticipantById", "outputs": [ { "name": "inviter", "type": "address", "displayName": "inviter" }, { "name": "itself", "type": "address", "displayName": "itself" }, { "name": "totalPayout", "type": "uint256", "displayName": "total Payout" } ], "type": "function", "displayName": "get Participant By Id" }, { "constant": true, "inputs": [], "name": "getParticipantCount", "outputs": [ { "name": "count", "type": "uint256", "displayName": "count" } ], "type": "function", "displayName": "get Participant Count" }, { "constant": false, "inputs": [ { "name": "inviter", "type": "address", "index": 0, "typeShort": "address", "bits": "", "displayName": "inviter", "template": "elements_input_address" } ], "name": "enter", "outputs": [], "type": "function", "displayName": "enter" }, { "constant": true, "inputs": [ { "name": "adr", "type": "address", "index": 0, "typeShort": "address", "bits": "", "displayName": "adr", "template": "elements_input_address" } ], "name": "getParticipantByAddress", "outputs": [ { "name": "inviter", "type": "address", "value": "0x0000000000000000000000000000000000000000", "displayName": "inviter" }, { "name": "itself", "type": "address", "value": "0x0000000000000000000000000000000000000000", "displayName": "itself" }, { "name": "totalPayout", "type": "uint256", "value": "0", "displayName": "total Payout" } ], "type": "function", "displayName": "get Participant By Address" }, { "inputs": [], "type": "constructor" } ]
