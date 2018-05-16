# Truffle Project

## Commands:
$ truffle init	//Create the truffle project skeleton
$ truffle create contract <contract name>
n.b: migration.sol file used by the truffle internally

> truffle.js:
module.exports = {
  // See <http://truffleframework.com/docs/advanced/configuration>
    networks: {
      development: {
        host: "127.0.0.1",
        port: 8545,
        network_id: "*" // Match any network id
      }
    }
};

$ truffle compile	//to compile the contract
$ truffle deploy --reset --network <network name>	//deploy the contract
