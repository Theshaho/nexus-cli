# nexus-cli

contribute to Nexus through cli

## System Requirements

```bash
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```

then install Nexus cli

```bash
curl https://cli.nexus.xyz/ | sh
```

## Initial Setup

Run the CLI for the first time

You'll be prompted to accept the Terms of Use

for Configuring your Prover ID you have two options 

![Screenshot 2024-12-09 223715](https://github.com/user-attachments/assets/e1221bba-87c8-4eb4-af61-2a9a245d03fc)


1. Link to Web Account (Recommended)

Get your ID from beta.nexus.xyz (it can be found in the left corner of the dashboard )left and then enter it when prompted your CLI contributions will sync with your web account.


![Screenshot 2024-12-09 222254](https://github.com/user-attachments/assets/e45c593f-7943-470a-b301-715ccab0c339)


2. Generate Random ID

Skip the ID prompt a random ID will be generated


# If you encounter any error use these steps

```bash
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all

sudo apt update
sudo apt install rustup
rustup install nightly
rustup default nightly

sudo apt update
sudo apt install -y protobuf-compiler
protoc --version
```

```bash
screen -S nexus
```

```bash
curl https://cli.nexus.xyz/ | sh
```

stop prover with ctrl + c and then change Prover Id

```bash
cd .nexus
```

```bash
nano prover-id
```

Change with your prover-id provided on beta.nexus.xyz

then Rerun it again

```bash
curl https://cli.nexus.xyz/ | sh
```
then detach with Ctl + A + D

If you encounter this error "warning: nexus-network@0.4.0: Failed to run protoc: No such file or directory (os error 2)" Run this command:

```bash
sudo apt install -y protobuf-compiler
```
