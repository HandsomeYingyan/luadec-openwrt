# luadec-openwrt
A Work Tools To Decompile OpenWRT Lua Bytecode (LUCI.

a bigthanks to http://storypku.com/2015/07/how-to-decompile-bytecoded-openwrt-lua-files/

To do
 
 sudo apt-get install libncurses-dev libreadline-dev
 
 
cd lua-5.1


make linux

sudo make install




cd ../luadec


make LUAVER=5.1


sudo cp luadec /usr/local/bin/


sudo cp luaopswap /usr/local/bin/



sudo cp luareplace /usr/local/bin/


 
 
