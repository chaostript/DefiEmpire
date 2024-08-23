# DefiEmpire

# DeFi Empire: Setup Guide

## Overview

This guide will help you set up an Ubuntu environment on Windows Subsystem for Linux (WSL), install the Avalanche CLI, and create and deploy a subnet. Follow these steps to get your DeFi Empire project up and running.

## Prerequisites

- Windows 10 or later
- WSL installed and set up with Ubuntu

## Step 1: Install WSL and Ubuntu

1. **Enable WSL**:
Open PowerShell as Administrator and run:
```sh
   wsl --install
``` 
2: Update and Upgrade Ubuntu
  Open the Ubuntu terminal and run the following commands to update and upgrade your system:
  ```sh
  sudo apt update
  sudo apt upgrade -y
 ```
3: Install Required Dependencies
Install necessary packages:
 ```sh
sudo apt install -y build-essential git curl

 ```

4: Avalance Download
 ```sh
curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
 ```
### Create a Subnet
1. Creation
 ```sh
avalanche subnet create
 ```
### Deploy Subnet 

 ```sh
avalanche subnet deploy
 ```

### Interacting with Smart Contract 
```sh
deploy ERC20.sol file first 
```

![image](https://github.com/user-attachments/assets/243b35f8-02ba-4b83-9a55-20ff4dc585d7)

![image](https://github.com/user-attachments/assets/32aff21b-bfd7-4d5f-975d-fe00812ab32f)

