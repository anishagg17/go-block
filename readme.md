# go-block

My own blockchain implementation in goLang using `sha256 hash` and `badger db`.

- Go version `1.16.2 darwin/amd64`

## Installation

1. Install [Go](https://golang.org/)
2. run `git clone git@github.com:anishagg17/go-block.git` in the terminal.
3. cd into the directory.
4. run `go mod tidy` in the directory

## Development

-  Run `go run main.go --help` to get all the applicable commands.

-  Run `go run main.go add -block "data"` to add a new block with data="data" into the blockchain.

-  Run `go run main.go print` to print the entire blockchain.
