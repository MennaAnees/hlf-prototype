# hlf-prototype

## Setting up the hyperledger fabric network 

1. setting the config and bin folder paths: 
    - ``` cd fabric ```
    - ``` export FABRIC_CFG_PATH=<config-path> ```
    - ``` export PATH=<path_to_bin_directory>:$PATH ```

2. starting network: 
    - ``` cd fabric/fabcar ```
    - ``` ./startFabric.sh ```