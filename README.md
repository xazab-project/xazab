Copyright (c) 2014-2020 The Dash Core developers

Copyright (c) 2020-2021 The Xazab Core developers

Xazab Core staging tree 0.18
===========================

`master:` [![Build Status](https://travis-ci.org/xazab/xazab.svg?branch=master)](https://travis-ci.org/xazab/xazab) `develop:` [![Build Status](https://travis-ci.org/xazab/xazab.svg?branch=develop)](https://travis-ci.org/xazab/xazab/branches)

What is Xazab?
-------------

Xazabs gives its users a faster means of transferring crypto with the use of x11 algorithm based on dash technology. Cryptocurrencies have played a vital role in empowering power with various opportunities particularly technologies which have been driving the world economy. Businesses are now implementing various crypto technologies to boost their diverse opportunities where opportunities are profitable in both the rural and urban communities. Xazab comes into play here to take its own opportunity in the digital space where crypto is driving the present economy directly and indirectly. Xazab uses the technology of Duff that is Dash because it follows our own ideas of what a cryptocurrency features should look like. We are separately going to build off our own from this technology just as we have started. Xazab transactions are faster, easier and transactions can be privately sent if you so want. The unique features have been built on this platform just like what dash did from litecoin. Our foundations and services range in different sections which range from providing the world with latest technologies to advertising your platforms in our XAZAB world class advertising platforms.  Our wallets range from all platforms including androids and IOS devices which you can download from the Android play stores etc. Xazab utilizes a decentralized system to provide a peer-to-peer connection between people and business owners. For our services, we will only want to be paid in xazab.

Two platforms we will launch are masternode monitor and our major dynamic website were you can sell your products with the use of xazab

# Xazab Road
 Multi algorithm: Lyra, X11, Sha256d, scrypt, yespower

### Usernames
Users will have the ability to register a personalized username of their choice. It will also be possible to set a display name, bio info and profile picture.

### Connect with contacts
Users will be able to request contacts by username and create a list of users they want to transact with.

### Pay and get paid by username
Users can exchange Dash with friends, family and merchants by username or cryptographic address.

### Invitations
Users will be able to sponsor registrations for new users using the invitations process.

### Core height consensus
Establishing consensus between L1 and L2 chains based on height of L1.

### Validator set rotation
Implementation and rotation of quorums used for consensus on L2 chain.

### State trees
Storage of data state in Merkle trees for use with light clients.

### BLS platform block signing
Inclusion of BLS signatures in L2 blocks.

### Identity funding
Ability to fund identities without ability to double spend.



XAZAB SPECIFICATION


- Name: Xazab
- Ticker: XAZAB
- Algorithm: X11 YESPOWER SHA256D LYRA2 SCRYPT 
- Supply: 21 million
- P2P: 30303
- RPC: 31313
- Block Time: 60 seconds
- Reward:  4 XAZAB [ 1.948 Miners + 2.052 for Masternodes]
- Premine blocks: 578,000 (from block height 2 and block height 3)
- Confirmation: 100 blocks

### Increase in masternode reward will take the following periods. First period is at block 16616
 
Period 1:  51.3%  X 4  = 2.05   XAZAB

Period 2:  52.6%  X 4  = 2.104 XAZAB

Period 3:  53.3%  X 4  = 2.132 XAZAB

Period 4:  54%     X 4  = 2.16  XAZAB

Period 5:  54.6%  X 4  = 2.184 XAZAB

Period 6:  55.2%  X 4  = 2.208 XAZAB

Period 7:  55.7%  X 4  = 2.228 XAZAB

Period 8:  56.2%  X 4  = 2.248 XAZAB

Period 9:  56.7%  X 4  = 2.268 XAZAB

Period 10: 57.2% X 4 =  2.288 XAZAB

Period 11: 57.7% X 4 =  2.308 XAZAB

Period 12: 58.2% X 4 =  2.328 XAZAB

Period 13: 58.5% X 4 =  2.34  XAZAB

Period 14: 58.8% X 4 =  2.352 XAZAB

Period 15: 59.1% X 4 =  2.364 XAZAB

Period 16: 59.4% X 4 =  2.376 XAZAB

Period 17: 59.7% X 4 =  2.388 XAZAB

Period 18: 59.9% X 4 =  2.396 XAZAB

Period 19: 60%    X 4 =  2.40  XAZAB

## Building XAZAB on Linux
```
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt update
sudo apt upgrade

sudo apt install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils git libdb4.8-dev libdb4.8++-dev curl libgmp3-dev
sudo apt install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev libzmq3-dev
```

Optional QT
```
sudo apt install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
```

```
wget https://github.com/dashpay/bls-signatures/archive/v20181101.zip 

unzip v20181101.zip 

cd bls-signatures-20181101

mkdir build

cd build

cmake ..

cmake --build .

sudo make install 
```

Download Xazab

```
git clone https://github.com/xazab/xazab

cd xazab

./autogen.sh
./configure
make
```


## Links

### Social Media

- [Discord](https://discord.gg/U6uBeAV)

- [Telegram](https://t.me/xazabcoin)

### Pool

- [https://https://pool.rplant.xyz/](https://pool.rplant.xyz/)


### Explorer 

- [Official Explorer](https://explorer.xazab.xyz/insight/)

### Explorer Api

- [Official Api](https://insight.xazab.xyz/insight-api/blocks)


License
-------

Xazab Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/xazab/xazab/tags) are created to indicate new official,
stable release versions of Xazab Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

## Masternode Setup

To set up a xazab masternode you need 1000 XAZAB, VPS and s Xazab wallet.

# SetUp 

1. Go to the Desktop wallet Click Tools > Debug console and enter the command into the console section

```shell

getnewaddress
```

From the address generated above send `15,000` XAZAB to the address and wait for 15 confirmation

Check the masternode output with this command

```shell
masternode outputs

```

## Setting up the VPS


With a vps, linux operating system, login to your user terminal with 

ssh root@your-vps-ip

Once you are login, create two new users, one to administer the server and one to run the `xazabd` service.

```shell

useradd -m -c xazab xazab -s /bin/bash
useradd -m -c "Xazab Admin" xazabadmin -s /bin/bash -G sudo,xazab

```

NOTE: # The xazab user password can be very long and you are not expected to remember it since we will not use it

```shell

< /dev/urandom tr -dc A-Za-z0-9 | head -c${1:-32};echo
passwd xazab

```


 For the xazabadmin user, choose a long password and write it down, this is the password you will use from now on to login into the VPS and administer the masternode.

```shell

passwd xazabadmin

```

Once you are done with the above, simply close the terminal by typing `exit` which will automatically close the window. Log again into the terminal and use 
use `whoami` to check that you are login in to the admin user account.

Next is to total disable root login for security purposes. Use the below code to do it. just copy and pass it in the terminal at once. Do not copy one at a time but
paste all at once. 

``NOTE:``` Do not run it in the root user but in the xazab admin user

```shell
if [ `id -u` -ne 0 ]; then
sudo bash -c \
"grep -q \".*PermitRootLogin [ny][oe].*\" /etc/ssh/sshd_config &&\
sed -i 's/.*PermitRootLogin [ny][oe].*/PermitRootLogin no/g' /etc/ssh/sshd_config||\
echo \"PermitRootLogin no\">>/etc/ssh/sshd_config"
else echo "Only run this block as your xazabadmin user, not root."; fi


```

Now update the system and install other needed packages. Copy all and paste at once into the terminal


```shell
sudo apt update -y \
sudo apt upgrade -y \
sudo apt install ufw python virtualenv git unzip pv speedtest-cli -y
```

Configure a firewall. Copy all and paste at once into the terminal

```shell

sudo ufw allow ssh/tcp &&\
sudo ufw limit ssh/tcp &&\
sudo ufw allow 30303/tcp &&\
sudo ufw logging on &&\
sudo ufw enable

```

# Add swap space to your VPS.

```shell

if [ $(free -m|grep Swap|awk '{print $2}') -lt 2048 ]
then
  echo "Adding 2GB swap..."
  sudo bash -c "fallocate -l 2G /var/swapfile&&\
  chmod 600 /var/swapfile&&\
  mkswap /var/swapfile&&\
  swapon /var/swapfile&&\
  grep -q \"^/var/swapfile.none.swap.sw.0.0\" /etc/fstab ||\
  echo -e \"/var/swapfile\tnone\tswap\tsw\t0\t0\" >>/etc/fstab"
else
  echo "You already have enough swap space."
fi
```
Change the default login port of 22 to any port number your like and kindly remember the new port, this is to add more security to your server. Open the ssh port file with the nano or vi 

```bash
sudo /etc/ssh/sshd_config
```

Locate the line where you see 

```bash 
#Port 22
```
Remove the leading character `#` and and remove the `22` and change it to a new port you can remember, lets say i want port 11212 it will now look like this 

```bash 
Port 11212

```

After changing the above port like that, restart the ssh with the below command

```bash
systemctl restart sshd
```

IMPORTANT: Make sure you allow your new port if not you will be lock out of your server. Use 

```bash 
sudo ufw allow 11212
```
 

# To allow the VM to use memory more effectively and prevent crashes due to low memory. Run the below to set this parameter.

```shell
sudo bash -c "echo \"vm.overcommit_memory=1\">>/etc/sysctl.conf"

```

Now after the above steps is completed reboot your system with the below method

```shell
sudo reboot
```

After few seconds kindly log back to your xazabadmin panel and check to see if you are now login. Remember that root login is disabled so you cannot login again into the terminal.

```bash 

ssh xazabadmin@your-vps-ip -p your-new-vps-port

```

Download the xazab wallet with the below command. Copy the below code at once and paste it in your terminal 

```bash
cd /tmp/ &&
wget https://github.com/xazab/xazab/releases/download/v0.17.0.1/xazabcore-0.17.0.1-x86_64-linux-gnu.tar.gz

```

Install the xazab wallet with the below command 

```bash 

sudo bash -c "cd /opt&& rm -f xazab 2>/dev/null;tar xvf /tmp/xazabcore-0.17.0.1-x86_64-linux-gnu.tar.gz&& ln -s xazabcore-0.17.0.1 xazab"

```

 Xazab package comes with user manuals, run the below command.

```bash 

sudo bash -c "echo -e \"MANPATH_MAP\t/opt/xazab/bin\t\t/opt/xazab/share/man\">>/etc/manpath.config"
```

 Configure the PATH environment variable for the xazab user so it can run xazab commands, eg `xazabd` and `xazab-cli` etc

```bash 

sudo bash -c "echo 'PATH=/opt/xazab/bin:\$PATH'>>/home/xazab/.profile"

```

 Configure the xazab.conf file by running this code on your terminal and remeber to enter your own masternodeblsprivkey=XXXXXXXXX gotten from above.

```bash 

sudo -u xazab bash -c "mkdir -p /home/xazab/.xazabcore&&cat >/home/xazab/.xazabcore/xazab.conf<<\"EOF\"
#----
rpcuser=rpcuser$(< /dev/urandom tr -dc A-Za-z0-9 | head -c${8};echo)
rpcpassword=rpcpassword$(< /dev/urandom tr -dc A-Za-z0-9 | head -c${8};echo)
rpcallowip=127.0.0.1
#----
listen=1
server=1
daemon=1
#----
masternodeblsprivkey=XXXXXXXXXXXXXXXXXXXXXX
externalip=$(curl http://ipecho.net/plain)
#----
EOF"

``` 

```bash

sudo -i -u xazab bash -c "nano ~/.xazabcore/xazab.conf"

```

 Register the `xazabd` deamon as a system process so that is starts automatically when the VPS boots and shutdown automatically when the VPS shutsdown, it will also restart the process if it should crash for some reason.

```bash 

sudo mkdir -p /etc/systemd/system&&\
sudo bash -c "cat >/etc/systemd/system/xazabd.service<<\"EOF\"
[Unit]
Description=Xazab Core Daemon
After=syslog.target network-online.target

# Notes:
#
# Watch the daemon service actions in the syslog journal with:
# sudo journalctl -u xazabd.service -f

[Service]
Type=forking
User=xazab
Group=xazab

# Make xazabd less likely to be killed when RAM is low.
OOMScoreAdjust=-1000

ExecStart=/opt/xazab/bin/xazabd -pid=/home/xazab/.xazabcore/xazabd.pid
# Time that systemd gives a process to start before shooting it in the head
TimeoutStartSec=10m

# If ExecStop is not set, systemd sends a SIGTERM, which is \"okay\", just not ideal
ExecStop=/opt/xazab/bin/xazab-cli stop

# Time that systemd gives a process to stop before shooting it in the head
TimeoutStopSec=120

Restart=on-failure
# If something triggers an auto-restart, let's wait a bit before taking further action
# Note: This value is in addition to the stop sleep time
RestartSec=120

# In this interval span of time, we allow systemd to start xazabd "burst" number
# of times. With Xazab we really only want one instance started, so... let's
# really limit this. But we want to give systemd some room to attempt to
# correct things. To be honest, I think the way things are configured between
# these settings and TimeoutStartSec, only one instance will be initiated.
StartLimitInterval=300
StartLimitBurst=3

[Install]
WantedBy=multi-user.target
EOF"

```

The next thing to do is to enable xazabd

```bash 

sudo systemctl daemon-reload &&\
sudo systemctl enable xazabd &&\
sudo systemctl start xazabd &&\
echo "Xazab is now installed as a system service and initializing..."

```

# To see the status of the `xazabd` process issue the below command.

```bash 

systemctl status xazabd.service
```

# You should see it running. To view systemd logs for xazab, issue:

```bash
sudo journalctl -u dashd.service -f
```

# Press 'CTRL+C' to quit.

# View the xazabd logs, issue the below command CTRL+C to quit, the logs should be streaming past very quickly.

```bash

sudo tail -300f ~/../xazab/.xazabcore/debug.log
```
 To see that xazabd is running correctly, we need to configure and run `top`

The below steps for configuring `top` are optional, but if you do it will make the UI much more user friendly. Copy & paste the block below into the terminal.

```bash 
echo "H4sICKY9SFsCAy50b3ByYwCt01tv0zAUB/Dn+lP4ibUQRhMnoYNmG2vVXVjHZRuXcQle4qQecRPZ
iRo+EGziCWlD1VoKQ7TfCwdVcvbYiZfoHCU+/v90lDROlgRsxf2AhrBDIwKru7Sf5TDhsUeEIAIO
aNqTj74fD0QNbPsPqAa7sU9cHKXC40593lJO80Q4ugbbJMKf3JQy4qBl+bqVcXneqYM2CSoBJZEv
vIw7n8/OL76Pf0yupsPR5ezWUu32He3u8r26btiN1bVHG63O5tb2zuPd7t6Tp8+e7x8cvnj56vXR
m7fv3rsf8LHnkyDs0RNQkbODCIfyahsZlqFBEfNU5s0dvaFBhvMUi4+iyBlynPRcL8lKHSNMdqAi
Msa8iBf5mQjFvOwR7Bcl0mAxpSgNsBMflxlfLoej6vnFdDxZb57OlMK6KWMFNUyzxKgvrrCVwlaK
+0phgy5hZcVo3Jz8/HX1u7ux96eNzKFcSPWaZWXuuKnC0BdnWIphKYapGBY4FPzaMk7Pvn6TC5nO
av+y6wYyZfiHTWd1bf1/LAMtrkBKgZTCUAoEOjQnvjugPhFpMWhfHnWZ8HBEivZAflhqjwiPXZEl
CZe/qLwJ/AVPpBK+xwMAAA=="|\
base64 -d|zcat >~/.toprc
```

# You can view the .toprc with the below command

```bash

cat ~/.toprc
```

 Test `top` with the below command. This will show you what is running on the VPS, processes using the most CPU will appear at the top of the list. You should see `xazab` at the top of the list, it should be running as the `xazab` user. You can also monitor memory usage. Once done press 'q' to quit.

```bash 
top

```

# From now on to start/stop `xazabd` use the below commands and the final one is to monitor its present status. Do not run the below commands now, keep them for your reference.

```bash 

sudo systemctl start xazabd
sudo systemctl stop xazabd
sudo systemctl status xazabd

```
# The next few commands should be run as the xazab user, login as the xazab user now:

```bash 

sudo su - xazab

# Verify you actually are the xazab user by typing in `whoami` is should display xazab.

```bash

whoami
```

# Sentinel Installation.

```bash 

cd &&\
git clone https://github.com/xazab/sentinel &&\
cd sentinel &&\
virtualenv venv &&\
venv/bin/pip install -r requirements.txt &&\
venv/bin/py.test test &&\
venv/bin/python bin/sentinel.py

```

 You will see a message reading xazabd not synced with network! Awaiting full sync before running Sentinel. Add sentinel to crontab to make sure it runs every 10 minutes to check on your masternode:


```bash 

echo "*/10 * * * * { test -f ~/.xazabcore/xazabd.pid&&cd ~/sentinel && venv/bin/python bin/sentinel.py;} >> \
~/sentinel/sentinel-cron.log 2>&1" \
|crontab -&&echo "Successfully installed cron job."

```

We now need to wait for 15 confirmations of the collateral transaction to complete, and wait for the blockchain to finish synchronizing on the masternode. You can use the following commands to monitor progress:

```bash 

xazab-cli mnsync status
xazab-cli getblockcount
xazab-cli masternode status
```


# Register your masternode

From your desktop wallet go to Click Tools > Debug console and enter the command below:

```bash 

masternode outputs
```

The above command will output the following:

```bash
{
"14547a28f4e5edf39f4dceac60e2327931a25fdee1fb4b94b63eeacf0d5879e3" : "1",
}
```

collateralHash = `14547a28f4e5edf39f4dceac60e2327931a25fdee1fb4b94b63eeacf0d5879e3`
collateralIndex = `1`

# Generate a BLS key pair

In the console type in 

```bash
bls generate
```
that will generate the follow :

```bash 

{
  "secret": "395555d67d884364f9e37e7e1b29536519b74af2e5ff7b62122e62c2fffab35e",
  "public": "99f20ed1538e28259ff80044982372519a2e6e4cdedb01c96f8f22e755b2b3124fbeebdf6de3587189cf44b3c6e7670e"
}

```


You will put the one with `secret` into `masternodeblsprivkey` in your ubuntu server. Go back to your VPS and add it. Run this commands

```bash
sudo systemctl stop xazabd

````

After that do this 

```bash 

nano ~/.xazabcore/xazab.conf
```

Then add the value of the `secret` into `masternodeblsprivkey`

```bash

masternodeblsprivkey=395555d67d884364f9e37e7e1b29536519b74af2e5ff7b62122e62c2fffab35e

```


Save  and then run

```bash 
sudo systemctl start xazabd

```

# Prepare a ProRegTx transaction


Use the value of the `public` key generated above as the `operatorPubKey`. Get a new address which will be use as `ownerKeyAddr`

```bash 

getnewaddress 

```
The address above is called your `ownerKeyAddr`

The generate another address and call it `votingKeyAddr`

```bash 

getnewaddress 

```

Generate an owner’s masternode payouts  address called `payoutAddress`.

```bash 

getnewaddress 

```


Unlock your wallet  and after that We will now prepare an unsigned `ProRegTx` special transaction using the `protx register_prepare` command. This command has the following syntax


```shell 

protx register_prepare collateralHash collateralIndex ipAndPort ownerKeyAddr
  operatorPubKey votingKeyAddr operatorReward payoutAddress (feeSourceAddress)
  
```

You will get an output of 

```shell

{
  "tx": "030001000175c9d23c2710798ef0788e6a4d609460586a20e91a15f2097f56fc6e007c4f8e0000000000feffffff01a1949800000000001976a91434b09363474b14d02739a327fe76e6ea12deecad88ac00000000d1010000000000e379580dcfea3eb6944bfbe1de5fa2317932e260acce4d9ff3ede5f4287a34160100000000000000000000000000ffff2d4ce6ef4e1fd47babdb9092489c82426623299dde76b9c72d9799f20ed1538e28259ff80044982372519a2e6e4cdedb01c96f8f22e755b2b3124fbeebdf6de3587189cf44b3c6e7670ed1935246865dce1accce6c8691c8466bd67ebf1200001976a914fef33f56f709ba6b08d073932f925afedaa3700488acfdb281e134504145b5f8c7bd7b47fd241f3b7ea1f97ebf382249f601a0187f5300",
  "collateralAddress": "yjSPYvgUiAQ9AFj5tKFA8thFLoLBUxQERb",
  "signMessage": "yjZVt49WsQd6XSrPVAUGXtJccxviH9ZQpN|0|yfgxFhqrdDG15ZWKJAN6dQvn6dZdgBPAip|yfRaZN8c3Erpqj9iKnmQ9QDBeUuRhWV3Mg|ad5f82257bd00a5a1cb5da1a44a6eb8899cf096d3748d68b8ea6d6b10046a28e"
}

```

# Sign the ProRegTx transaction

The command takes the following syntax to sign the proregtx:

```shell

signmessage collateralAddress signMessage

```

You will get an output of 

```shell

II8JvEBMj6I3Ws8wqxh0bXVds6Ny+7h5HAQhqmd5r/0lWBCpsxMJHJT3KBcZ23oUZtsa6gjgISf+a8GzJg1BfEg=

```

# Submit the signed message

```shell

protx register_submit tx sig

```
`sig` = `signMessage`









