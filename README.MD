### Compile with truffle

truffle compile


### Deploy 
truffle migrate

#### Truffle console

```sh
truffle(development)> todoList = await TodoList.deployed()
undefined
truffle(development)> todoList.address
'0xE08fC6135Abb14186287E602B6687A81DC59F0A6'
truffle(development)> taskCount = await todoList.taskCount()
undefined
truffle(development)> taskCount
BN { negative: 0, words: [ 0, <1 empty item> ], length: 1, red: null }
truffle(development)> taskCount.toNumber();
0
```