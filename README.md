# bfgminer-with-gridseed-support
bfgminer 5.5 with support for Gridseed G-blade

ps. Don't do autogen just configure.

./configure --enable-scrypt

Works well with 40chip x2 Gridseed blades on puppy Linux Xenial7.5/x86-64

My configuration  -: exec bfgminer --scrypt -S noauto -S gridseed:all --set-device gridseed:clock=850 --scrypt -o stratum+tcp://eu.bsod.pw:2316 -u <your_wallet_address> -p x

