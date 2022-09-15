### Logs from mint.js

```bash
❯ node ./mint.js
1111 a224fa6e6d264684ad002e3ffead9d86 salon dream genuine width marine below scene choice steel excite bitter ozone
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 0

proof {"a":["0x1de4b98037c2e96ad11a64c4e3cb9e736553f6e6dea582b1c24e41392cb16acc","0x086dc3d5949a9bb7d7a5d15011b91760e064283ff7bba45f6d95e5833827de4d"],"b":[["0x0a826e158e5af825af54373f831f0814b28e1f194f134602333fc848603fa6e0","0x0ec949ef127b90f9747e4feae95349922fdd172eab76362545929f3270854e2c"],["0x12ee55f250fed6c3b2455998a625ee0fc31194b38559b4ddbc0b82e52b3de625","0x043b2bdc44e2dc5ffe66664d2f6a697e13badad2ee56c592bba91553d2b0ef08"]],"c":["0x22b6c7687959426a1e92da7680f425616185ae472d392676631ac4c04308a062","0x1ea5eb101cc87a1c11fe8f4d002cb9672aea123589d6dda9094f5d3a6089a779"]}

input 0x0000000000000000000000000000000000000000000000000000000000000009,0x0000000000000000000000000000000000000000000000000000000000000001

node:events:346
      throw er; // Unhandled 'error' event
      ^

Error: Unexpected server response: 404
    at ClientRequest.<anonymous> (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/ws/lib/websocket.js:542:5)
    at ClientRequest.emit (node:events:369:20)
    at HTTPParser.parserOnIncomingClient [as onIncoming] (node:_http_client:646:27)
    at HTTPParser.parserOnHeadersComplete (node:_http_common:129:17)
    at TLSSocket.socketOnData (node:_http_client:512:22)
    at TLSSocket.emit (node:events:369:20)
    at addChunk (node:internal/streams/readable:313:12)
    at readableAddChunk (node:internal/streams/readable:288:9)
    at TLSSocket.Readable.push (node:internal/streams/readable:227:10)
    at TLSWrap.onStreamRead (node:internal/stream_base_commons:190:23)
Emitted 'error' event on WebSocket instance at:
    at abortHandshake (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/ws/lib/websocket.js:649:15)
    at ClientRequest.<anonymous> (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/ws/lib/websocket.js:542:5)
    [... lines matching original stack trace ...]
    at TLSWrap.onStreamRead (node:internal/stream_base_commons:190:23)
❯ node ./mint.js
1111 a224fa6e6d264684ad002e3ffead9d86 salon dream genuine width marine below scene choice steel excite bitter ozone
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 0

proof {"a":["0x1de4b98037c2e96ad11a64c4e3cb9e736553f6e6dea582b1c24e41392cb16acc","0x086dc3d5949a9bb7d7a5d15011b91760e064283ff7bba45f6d95e5833827de4d"],"b":[["0x0a826e158e5af825af54373f831f0814b28e1f194f134602333fc848603fa6e0","0x0ec949ef127b90f9747e4feae95349922fdd172eab76362545929f3270854e2c"],["0x12ee55f250fed6c3b2455998a625ee0fc31194b38559b4ddbc0b82e52b3de625","0x043b2bdc44e2dc5ffe66664d2f6a697e13badad2ee56c592bba91553d2b0ef08"]],"c":["0x22b6c7687959426a1e92da7680f425616185ae472d392676631ac4c04308a062","0x1ea5eb101cc87a1c11fe8f4d002cb9672aea123589d6dda9094f5d3a6089a779"]}

input 0x0000000000000000000000000000000000000000000000000000000000000009,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x7270d24e3db5057ee6b90c4154c457349f22159e982ed5a50751d45697cee543
/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-utils/lib/index.js:49
        error = new Error(error);
                ^

Error: ESOCKETTIMEDOUT
{
  "originalError": {
    "code": "ESOCKETTIMEDOUT",
    "connect": false
  }
}
    at Object._fireError (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-utils/lib/index.js:49:17)
    at sendTxCallback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-method/lib/index.js:539:30)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-requestmanager/lib/index.js:299:20
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:232:9
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/once.js:12:16
    at replenish (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:61:25)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:71:9
    at eachLimit (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/eachLimit.js:43:36)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/doLimit.js:9:16
    at end (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:211:5)
    at Request._callback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/subproviders/rpc.js:36:21)
    at self.callback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/request/request.js:185:22)
    at Request.emit (node:events:369:20)
    at ClientRequest.<anonymous> (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/request/request.js:819:16)
    at Object.onceWrapper (node:events:475:28)
    at ClientRequest.emit (node:events:369:20)
❯ node ./mint.js
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 0

proof {"a":["0x1de4b98037c2e96ad11a64c4e3cb9e736553f6e6dea582b1c24e41392cb16acc","0x086dc3d5949a9bb7d7a5d15011b91760e064283ff7bba45f6d95e5833827de4d"],"b":[["0x0a826e158e5af825af54373f831f0814b28e1f194f134602333fc848603fa6e0","0x0ec949ef127b90f9747e4feae95349922fdd172eab76362545929f3270854e2c"],["0x12ee55f250fed6c3b2455998a625ee0fc31194b38559b4ddbc0b82e52b3de625","0x043b2bdc44e2dc5ffe66664d2f6a697e13badad2ee56c592bba91553d2b0ef08"]],"c":["0x22b6c7687959426a1e92da7680f425616185ae472d392676631ac4c04308a062","0x1ea5eb101cc87a1c11fe8f4d002cb9672aea123589d6dda9094f5d3a6089a779"]}

input 0x0000000000000000000000000000000000000000000000000000000000000009,0x0000000000000000000000000000000000000000000000000000000000000001

Error: Transaction has been reverted by the EVM:
{
  "blockHash": "0xeb8a3c7449bab3c121803d249840089ac90190622d52478c73a62f89733791cd",
  "blockNumber": 11385744,
  "contractAddress": null,
  "cumulativeGasUsed": 1029590,
  "effectiveGasPrice": "0x3b9aca08",
  "from": "0xf124998fca84a6685c282a74b6f51fa5e7bf179a",
  "gasUsed": 31188,
  "logsBloom": "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "status": false,
  "to": "0x9afd2040600375b9dd8752f8b4f48ff48a19986d",
  "transactionHash": "0xbea9814efd634107011ee258e37926ddd5f7f84b93ecc3985c5f74e8f7645e45",
  "transactionIndex": 14,
  "type": "0x2",
  "events": {}
}
    at Object.TransactionError (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-helpers/lib/errors.js:87:21)
    at Object.TransactionRevertedWithoutReasonError (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-helpers/lib/errors.js:98:21)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-method/lib/index.js:393:57
    at processTicksAndRejections (node:internal/process/task_queues:94:5) {
  receipt: {
    blockHash: '0xeb8a3c7449bab3c121803d249840089ac90190622d52478c73a62f89733791cd',
    blockNumber: 11385744,
    contractAddress: null,
    cumulativeGasUsed: 1029590,
    effectiveGasPrice: '0x3b9aca08',
    from: '0xf124998fca84a6685c282a74b6f51fa5e7bf179a',
    gasUsed: 31188,
    logsBloom: '0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000',
    status: false,
    to: '0x9afd2040600375b9dd8752f8b4f48ff48a19986d',
    transactionHash: '0xbea9814efd634107011ee258e37926ddd5f7f84b93ecc3985c5f74e8f7645e45',
    transactionIndex: 14,
    type: '0x2',
    events: {}
  }
}
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 1

proof {"a":["0x230872db63f2052df9357da12286abaa365e72b834c13d4b123d57dd19eabbd6","0x2f44f3a40dc90eecb657221c00282f1ef0fae085a04df690e6c47442d0ba4233"],"b":[["0x2ca36d6241424100832d6c1c9de58d8428513f264addefb7c2924f37301dca74","0x0ba23e8c1f9e5e3ed86744835772590019d3f42f2f0ae7f03c4044dbd6b36a34"],["0x0f6d284f7189b4e7dcf261931561516a910f74de1f78642951893a7f94cd67af","0x2d084e7420421b06b0d1e44d60631b18765112d7e6ad1d88d39d47f3ecc7150f"]],"c":["0x07dc04e649caac35124b42f051aeed30d8de61cd2d593cd0278e1dc79be861d8","0x1a6124b46679b84a526cfccba4ce0bddefb29e52618f03c2b959d79f922053b4"]}

input 0x0000000000000000000000000000000000000000000000000000000000000010,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x17c399d052dd0e076cf87e1bdb0ac6bd3c6a6635def2f02321f90272cc987de8
Minted item. Transaction: 0xc985515e5d9eebe85bf44929f759c6360a1ca255dc314f86257d83f692ee42b0
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 2

proof {"a":["0x240bf58bc035350b5706ff0df28ffed8dedf2109e3a46b91f0dd657dafb515e4","0x015de048b5cc44e91a533909776808a815d978b68f6b9de1e9c5aff335ffa29a"],"b":[["0x20a764e1fbf9b106ab80fa808c76889741b8cb96cfe7b6932ab061f9440addee","0x16793a9ef203d2b41f64b9345ad7a7c409474fac26538e097c9fff05fa3d53ec"],["0x0a121f709aab98480ec9e36a68a4a2443a3288422a51908849234c73104be250","0x103aa7eca67228df83606ff86f5a42deda124431f6a77a6d0aa6e6fe3b89f026"]],"c":["0x274d7ad9bcf212fbeb6ef2fd765fc9585c2a4c44d150890ff5d3b7b8855ed25a","0x01d2ae2bb744c3be77fefeda6f488ed4c778aee730f074bd9ac276c8c31dd052"]}

input 0x0000000000000000000000000000000000000000000000000000000000000019,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0xa90243a64a945642b27b1ad81c6661ca3474f841c9a4355d51ddaa70846b534a
Minted item. Transaction: 0x3e02d64b338734f5302425587be74f8a96595b5b5238ebada0d7f82b81114e05
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 3

proof {"a":["0x13b8a2b7ac13e91a622230cadda1bb8c99dd96016e17286c41b2611bde5c2593","0x27438a60b926bd7e5960ae7eed1947b8de7751e40f750c60dc7ce42fed8ea967"],"b":[["0x2ec79a70c9e34b49772ab4762cad8847a2b5686af412808986ed7a7693ee0b96","0x0b30748e98eefd40ab3cc715ece0b85a335739c7e7cd1615af3fe14b6b6d4ee8"],["0x2ec4b8ea8e5b06e864ec68efe7c99170fcb551f229525b9367e67eebc35c7577","0x175a84fd7aa9f5e8542cafc38664b74bce3cb3bb648f98a99b0bfad91e196cf9"]],"c":["0x14359123d6b88270207b72e232a8c361b979ff6c6fc41214e405f3921f4d150d","0x00977113b3eb9a2dfe74be4aaa8cf5f8a0917c866f51dc402133cf24b6b10709"]}

input 0x0000000000000000000000000000000000000000000000000000000000000024,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x65a93ffebb6f36bef14f9c7d7745c25ec423ec1c111d4e2fb9d72fd6e261baa1
Minted item. Transaction: 0x258190332613fcaf0409ddcbb6e81029fcca78e8522e34a623bdeefecedddf4f
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 4

proof {"a":["0x22658b1596acc16c454f9103eaeee9eab25d9c3ebbb092f124499edce13df620","0x2f7f3a17310f296e7efd1daa2630b088565a4e6e7336fa1979bf10d44f66fd71"],"b":[["0x08b2c63bd2fc785f2c2e7abd207cd73754e0378704148ab43a16c7c982f40854","0x0e024bd3d1b81038e2b4d36a661d8950d00aafcf068f0a634193b04e608c8ae9"],["0x141a0691f40dc95a7113ecfb59819e0b8007dfa85898a121f29c540997d0d9ff","0x2b0280df6ed45a424e3be0b70145f63fef5704acb0496546b59f31f3737de492"]],"c":["0x297e16d0f770484088877f8f09adcaf37afe81c055ee62ec53ffeb86690b7546","0x15a4cf7a77e459489e6f79b0df8aab83d5ac8b43f60107c12df78f1dd92f56f9"]}

input 0x0000000000000000000000000000000000000000000000000000000000000031,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x4f9435d711461a10740eaac22cb1ccf2ee28084dcfb34b8f9cac81e53f7f8575
Minted item. Transaction: 0x115dd266d61cf1b3581d252cc7c08573670e84251218959d8275a2bd30e03a0c
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 5

proof {"a":["0x240b8e4b290fb38b15ec45fb21441c325371044b30f5ac615b3e0a6c0f025bf8","0x1bab53e61dd3ed372afac5d57e4d979a9085af783f8125b54cd188400c4e9575"],"b":[["0x03185d6fccbceadb6153cbc64493613e611df6f2a10b34e64b6faaa47bc8afac","0x1312e273c42c05497463add36b0da69d83fd51586f7799199db823961df5839f"],["0x0c8f6f25db1fd5975cf69c750d26071957c7e790c4ed97b6137deec8ccb878bd","0x24c24f92adc17f41313f7ea4775951e07f434027cb5fd26294b937b2e5d5666e"]],"c":["0x00921b45008bce763ba4af2ca0b34d282125e8faae246fae3e8234d8faed54b1","0x111ae601e2ec4875f7df85533300a98ff6e7ad811b03ae7ec35c1bf006593d5b"]}

input 0x0000000000000000000000000000000000000000000000000000000000000040,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0xc7a548230d38594cb07b256533b0e8501be4a7b5d6b64e92d81ecaf0c40b6497
Minted item. Transaction: 0x8b032f9ed768ad8d4fc396e25667c0be4c2f2bb0952d1e90f518a035890f699a
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 6

proof {"a":["0x12c60cf6f4b94b080a326e6f8fc5bab7bd18a79fc9cbebf77e247512d1a917cd","0x1610116fd57f791e5644586cf9601a9951c384ccf63e9d62159480cb44dd7573"],"b":[["0x2705d62f338ba97c48ef523304d95f1d5de3e5811f5125f8d6df8ec11cef8021","0x1737c9523dabdc9720f3e949d4742a226025c593a07e644acc202e2b5d27663b"],["0x1bc98436cdcdf50c08df52ae1372b7d63e9bf77ec5ceaa8cd0af57a5ac5b6090","0x1c879b263013e8f13a98c1cb97e1cb988a5035ba65d5be13d9be0ffa60ee6ca6"]],"c":["0x2c4a6fa0a8d297bf7929146fcb8637a2c005c061f9ad05eaca5aa8b64436bfdc","0x26acbe4aea8914bbd9d2602d16f07d60ef841d5dbb3f84b5e96f010e70f6b48d"]}

input 0x0000000000000000000000000000000000000000000000000000000000000051,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0xbdff22371e68799f0893c7a3aea0e53bb644cb9c86e068e9cb2e7a4031ffd7f8
Error: Client network socket disconnected before secure TLS connection was established
{
  "originalError": {
    "code": "ECONNRESET",
    "path": null,
    "host": "rinkeby.infura.io",
    "port": 443
  }
}
    at Object._fireError (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-utils/lib/index.js:49:17)
    at sendTxCallback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-method/lib/index.js:539:30)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-core-requestmanager/lib/index.js:299:20
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:232:9
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/once.js:12:16
    at replenish (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:61:25)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:71:9
    at eachLimit (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/eachLimit.js:43:36)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/doLimit.js:9:16
    at end (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:211:5)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/once.js:12:16
    at next (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/waterfall.js:21:29)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/onlyOnce.js:12:16
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/once.js:12:16
    at next (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/waterfall.js:21:29)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/onlyOnce.js:12:16
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 7

proof {"a":["0x2e2fa7e51cc3e26e513c1baecc4bbd1205cd6e7e87ae001a43cf14ab94e52102","0x0f82462e6ee6c84d9b51875a60211cebcc74e93a0412a729dd432b2651ab98d6"],"b":[["0x1060a7d02b3f9f2e8a9ad06489370d4b15d4e879384634aaff687c15746fbfa3","0x0b7e8cb2b27e222677720f9fcfeb8f7bca628d160e40a763710f9252701d285f"],["0x11d085b0926a20e7e98f078e5a2acfda6feb8b8cbd4ef0c9125f3da28c1ba4a5","0x05a10ef11f42598c3713dee31ed2f760fc0575585a6ded5b6b8ec9fd88f2275a"]],"c":["0x029021a56e7526f3c393ca0628db565d6604edc33a3357e11d71263988c04804","0x1e2cf3eaf30f2cd7a6bc8487f3a47f302036a6463234fea9ed96528700dce254"]}

input 0x0000000000000000000000000000000000000000000000000000000000000064,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x59aba343fef3dccd1f8290ba2b31d3050c55413243bde5eded721f78bb5eb577
Minted item. Transaction: 0x897b1ffbbd5be5c47eaa593c9bf4fd961a18169059660f181d6b88b126976685
OWNER_ADDRESS 0xf124998Fca84a6685C282A74b6F51Fa5E7bf179A

index 8

proof {"a":["0x03ddda7bef90fd6a2c733503b43b7a14b29082de634fa5c86841425e1e360215","0x1d9ca8a1f7b4c3552f576d45f5b3bafbab61368630e7885bd5027589c859a261"],"b":[["0x02b4e9d18a575d811157cace3be023f14504c43887f8d8882d57d88b1287d3a5","0x2ff04dc5759d55cb71df29b5b218496249a5d392d171faa7a921a230850fbf22"],["0x22e69bb9457cedb261969e3128e025fa5c686974c6d3411c534d8d41dc514443","0x043bdbaaf94298d101f45dee40f19fba474466ff182f42b0a1efbea71434d239"]],"c":["0x00bae74ef8197ec5c5a91471b4a9b4a3bc42315b4a4836770f2178767918622c","0x0c153cdc26a2ec73cd58ec9a2114f8597ca13ca3698f2a8c12fec1c1bc0bb82c"]}

input 0x0000000000000000000000000000000000000000000000000000000000000079,0x0000000000000000000000000000000000000000000000000000000000000001

Solution added. Transaction: 0x2e8c9dccf33cb1a2d8ee5a5dd0f86f9b43c0c4dfa66c6b133ecc08b04c68cc73
node:events:360
    throw err; // Unhandled 'error' event
    ^

Error [ERR_UNHANDLED_ERROR]: Unhandled error. ({
  code: -32603,
  message: 'ESOCKETTIMEDOUT',
  data: { originalError: { code: 'ESOCKETTIMEDOUT', connect: false } }
})
    at new NodeError (node:internal/errors:329:5)
    at Web3ProviderEngine.emit (node:events:358:17)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:54:14
    at afterRequest (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:148:21)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:174:21
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:232:9
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/once.js:12:16
    at replenish (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:61:25)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/eachOfLimit.js:71:9
    at eachLimit (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/eachLimit.js:43:36)
    at /Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/node_modules/async/internal/doLimit.js:9:16
    at end (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/index.js:211:5)
    at Request._callback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/web3-provider-engine/subproviders/rpc.js:36:21)
    at self.callback (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/request/request.js:185:22)
    at Request.emit (node:events:369:20)
    at ClientRequest.<anonymous> (/Users/mo/code/class/udacity-blockchain/Homework/Blockchain-Capstone/node_modules/request/request.js:819:16) {
  code: 'ERR_UNHANDLED_ERROR',
  context: {
    code: -32603,
    message: 'ESOCKETTIMEDOUT',
    data: { originalError: { code: 'ESOCKETTIMEDOUT', connect: false } }
  }
}

```