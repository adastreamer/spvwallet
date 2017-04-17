[![Build Status](https://travis-ci.org/OpenBazaar/spvwallet.svg?branch=master)](https://travis-ci.org/OpenBazaar/spvwallet)
[![Coverage Status](https://coveralls.io/repos/github/OpenBazaar/spvwallet/badge.svg?branch=master)](https://coveralls.io/github/OpenBazaar/spvwallet?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/OpenBazaar/spvwallet)](https://goreportcard.com/report/github.com/OpenBazaar/spvwallet)

# spvwallet

Lightweight p2p SPV wallet in Go. It connects directly to the bitcoin p2p network to fetch headers, merkle blocks, and transactions.

It uses a number of utilities from btcsuite but natively handles blockchain and wallet. 
