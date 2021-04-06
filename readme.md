# go-block

My own blockchain implementation in `Go` using `sha256 hash` and `badger db`.

- Go version `1.16.2 darwin/amd64`

## Installation

1. Install [Go](https://golang.org/)
2. run `git clone git@github.com:anishagg17/go-block.git` in the terminal.
3. cd into the directory.
4. run `go mod tidy` in the directory

## Development

-  Run `go run main.go --help` to get all the applicable commands.
```
Usage: 
 add -block <BLOCK_DATA> - add a block to the chain
 print - prints the blocks in the chain
```

-  Run `go run main.go add -block "data"` to add a new block with data="data" into the blockchain.

-  Run `go run main.go print` to print the entire blockchain. Demo output :   
```
Previous hash: 000be79ee71e25c20f15189e544b1c60aa81f1414f6ed33636dfdbd68ddc68b7
data: hexxx
hash: 0001c19e5f888aab7e502de21c3dabe93192695ea46a6b00797da84b3c23ec28

Previous hash: 
data: Origin
hash: 000be79ee71e25c20f15189e544b1c60aa81f1414f6ed33636dfdbd68ddc68b7
```
