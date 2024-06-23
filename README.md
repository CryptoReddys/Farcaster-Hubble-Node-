
# Farcaster Hubble Node Setup Guide

![far](https://github.com/CryptoReddys/Farcaster-Hubble-Node-/assets/59482451/27a4f7d7-a761-4836-b5f6-dbc2f7ba7f51)


## Lets Start
## Requirements :

### STEP 1

-- For Better node performance, select a Highend VPS with a high-frequency CPU and RAM.

- 16 GB RAM
- 4 CPU cores or vCPUs
- 40 GB of free space

### STEP 2

- Register on Warpcast - ( Require $5 Setup fees )
 -- Link to Register : https://warpcast.com/~/invite-page/673854?id=c9d6bf41

- Navigate to your profile, select About, and note down your FID

  ![id](https://github.com/CryptoReddys/Farcaster-Hubble-Node-/assets/59482451/b5913e11-117c-4c96-b33a-711c7a767f74)


### STEP 3
- Create RPC ENDPOINTS using INFURA - https://app.infura.io
-  choose Ethereum & Optimism ENDPOINTS

  ![rpc](https://github.com/CryptoReddys/Farcaster-Hubble-Node-/assets/59482451/6cfa1c86-59d9-4550-95a6-1127ece8397e)


## Lets install Farcaster Hubble NODE :

- Login ur IP using Putty OR Termius Software

- just copy and paste Below CMDs in ur Terminal


#### #Install Screen
~~~bash
sudo apt update -y
sudo apt install screen -y
screen -S Hubble
~~~
Remember Screen name : Hubble

#### #Farcaster Installation Script

~~~bash
curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash
~~~

- its takes 5 mins to Installing Script

- After Script Succesfully installed

- just copy & paste RPC ENDPOINTS one by one
    - Ethereum RPC
    - Optimism RPC
    - Farcaster FID

- #### Now node start Running & Start Syncing

- u must Deattach ur Screen : #Press CTRL + A + D

#### Re-Enter ur Node Screen-Execute the below CMD

~~~bash
screen -r Hubble
~~~

- #### Access ur Farcaster Dashboard : http://your_VPS_iP:3000

  ![dash](https://github.com/CryptoReddys/Farcaster-Hubble-Node-/assets/59482451/01bbf49b-8be9-475d-95ac-0a347715700f)


### Additional

#### if ur Node Stop Working use Below CMD

~~~bash
cd ~/hubble && ./hubble.sh upgrade
~~~

#### Thats it🧑‍💻

DISCLAIMER : *DYOR* There is no Guarantees Rewards or Future Airdrops :  This are all Speculations.Please consider carefully before participating.
