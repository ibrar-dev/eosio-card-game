# Elemental Battles

- *Account*: `player1`
- *Private Key*: `5KFyaxQW8L6uXFB6wSgC44EsAbzC7ideyhhQ68tiYfdKQp69xKo`
The account information is available in [eosio_docker/scripts/accounts.json](eosio_docker/scripts/accounts.json). The key pair in this file is generated **FOR TESTING ONLY** so please **DO NOT** use them for any other purposes.

## Prerequisites

Make sure Docker and Node.js are installed

* Install Docker: https://docs.docker.com/docker-for-mac/install/
* Install Node.js: https://nodejs.org/en/

The DApp and eosio will occupy the ports 3000, 8888 and 9876. Make sure nothing else is already running on these ports.

Clone the repository:
```sh
git clone https://github.com/EOSIO/eosio-card-game-repo.git
```

The following guide assumes you are using macOS.

## Quick start - Run the DApp

In this section we provide a single command script to run all the commands needed to start both the blockchain and UI. For more detail on each component see the `Detailed guide` below.

**To start**
```sh
./quick_start.sh
```

The above command will execute the following in sequence:

1. `first_time_setup.sh`
2. `start_eosio_docker.sh`
3. `start_frontend.sh`

- Login with the following credentials:

**To stop**, press `ctrl+c` on your keyboard, and execute:
```sh
docker stop eosio_cardgame_container
```

## Detailed guide

Please refer to [eosio-project-boilerplate-simple - Detailed guide](https://github.com/EOSIO/eosio-project-boilerplate-simple/blob/master/README.md#detailed-guide) for more information. This repository is using the similar structure as that.

