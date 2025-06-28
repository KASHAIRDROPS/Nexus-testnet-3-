## Hardware Requirement
* 8 GB Ram

## Nexus-testnet - 3
***

# Install dependencies
```
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential pkg-config libssl-dev git protobuf-compiler
```
## Only For VPS Users
```
sudo apt update
sudo apt install screen -y
```

## Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
```

# Install cli
```
curl https://cli.nexus.xyz/ | sh
source ~/.bashrc
```

# Create a Screen Session (Only For VPS Users)
```
screen -s nexus
```

# Start Nexus Node
```
nexus-network start --node-id <your-node-id>
```

## Only For VPS Users
* Exit the screen session (Ctrl+A+D)

## Watch Node Logs And Activity
```
  Screen -r nexus
```
## JOIN OUR TELGRAM IF YOU FACE ANY TYPE OF ERROR-- https://cryptoaabid

  
