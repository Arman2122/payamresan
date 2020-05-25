# payamresan
This repository
Pull requests
Issues
Gist
 @Arman2122
 Watch 3
  Star 4
  Fork 8 Mrhalix/lua-pmrsn
 Code  Issues 0  Pull requests 0  Wiki  Pulse  Graphs
No description or website provided.
 16 commits
 1 branch
 0 releases
 3 contributors
 Lua 97.6%	 Shell 2.4%
Lua	Shell
Clone or download  Create new file Upload files Find file Branch: master New pull request
Latest commit 8316657  4 days ago @Mrhalix Mrhalix Merge pull request #2 from MRAHS/patch-1  …
LICENSE	First Commit!	5 days ago
README.md	Update README.md	4 days ago
bot.lua	Update bot.lua	4 days ago
dkjson.lua	First Commit!	5 days ago
launch.sh	First Commit!	5 days ago
 README.md
lua-pmrsn
Bot commands =>

/setdn <done msg>
will set auto response message

/setid 
will set realm id

/block
block user by reply

/unblock
unblock user by reply

/blocklist
will send blocked users list

/getid
get realm id (for test)

/users
list users count

/setst <start msg>
set start text you can use {USERNAME} and {FIRSTNAME} for info of user started bot

/id
send group id

/init
reload bot!

installation
# Download and install LuaSocket, LuaSec, Redis-Lua, ansicolors and serpent

 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz
 tar zxpf luarocks-2.2.2.tar.gz
 cd luarocks-2.2.2
 ./configure; sudo make bootstrap
 sudo luarocks install luasocket
 sudo luarocks install luasec
 sudo luarocks install redis-lua
 sudo luarocks install lua-term
 sudo luarocks install serpent
 cd ..

 #Launch BOT!
 git clone https://github.com/Mrhalix/lua-pmrsn
 cd lua-pmrsn
 chmod +x ./launch.sh
 ./launch.sh
then add bot to your realm and send

/setid
and set your start text and done text by

/setdn <msg>
/sets <your text> you can use {USERNAME} and {FIRSTNAME}
