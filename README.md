# ETHstorage V1 Trusted Setup Ceremony Guide :
Detailed guide to contribute to the ceremony which is conducted for our Groth16 zk-SNARK circuits
ETHstorage is L2 that lets you store data and use it for games, socials, AI. It makes sure no one can fake data or pretend to store
This ceremony is about making sure ETHstorage stays secure and decentralized
Ceremony will last from August 13 to 22
## Requirements :
## **Local PC Ubuntu 22.04**

or VPS : 2 vCPU, 4GB RAM, 30GB+ SSD recommended

GitHub account : for authentication
Github account age: ≥ 1 month
At least 1 public repository
Followings ≥ 5 accounts and atleast 1 or more followers
Trick : if you don't want to miss the ceremony at any cost i will recommend to purchase a vps from Xorek for 2-3 days

cost around : $1 only

this will save you from keeping your pc on for 2-3 days continuously
you won't miss the shot on your contribuiton's time
## Follow The Guide :
## Update & Install Dependencies
```
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl git build-essential
```
## Install Node.js
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs
sudo npm install -g npm@9.2
```
## Check Versions
```
node -v
npm -v
```
## Create Temporary Directory
```
mkdir ~/trusted-setup-tmp && cd ~/trusted-setup-tmp
```

## Install Phase2 CLI
```
sudo npm install -g @p0tion/phase2cli
```
## Verify CLI Installation
```
phase2cli --version
```
## Authenticate with GitHub
```
phase2cli auth
```
**Follow the link shown in the your terminal**-
**Login to GitHub & authorize p0tion to access Gists**-
**Return to terminal**- <img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/afb2b9a5-eae4-4f77-9631-ebbfc80c66ae" />

 WhatsApp Image 2025-08-15 at 18 36 42_07f2d159
## Contribute to the Ceremony
```
screen -S ceremony
```
```
phase2cli contribute -c ethstorage-v1-trusted-setup-ceremony
```
-### it will ask for randomly/manually - just press enter button
# Final Step
Now wait for your queue
When your turn will come the tool will process your contribution
You have successfully contributed to the EThstorage V1 Trusted Setup Ceremony
IMP: if it asks you to wait for 10 days don't worry it won't take exactly 10 days you should get in before 22 Aug
many are running locally on PC :
if their pc shuts down they will be removed from the list
so we vps users have more chances to get in
## **Important Points**
## Screen Session Controls
Detach screen: CTRL + A, then D
Reattach screen: `screen -r ceremony`
Let it run until your time of contribution comes up
Once the work after 2-3 days is done follow the below steps :
Remove The Login Permissions After Contribution From vps :
```
phase2cli clean
phase2cli logout
cd ~ && rm -rf ~/trusted-setup-tmp
# ETHstorage-V1
```
