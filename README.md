# hdaddy

Derive Decred addresses from extended keys using dcrutil/hdkeychain

`hdaddy` is a golang package with functions for deriving Decred P2PKH addresses from extended keys. A command line utility is in the cmd/keyaddresses folder. To build the `keyaddresses` app:

 1. Clone the repository
 2. Open a command prompt in the cmd/keyaddresses subdirectory.
 3. `go build`
 4. Run `./keyaddresses -h` and read the help.
