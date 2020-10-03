# telegram-bot in Termux
TelegramBot API
script:
$pkg update -y && pkg install curl proot tar -y && curl https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu/Ubuntu.sh | bash 
$./start-ubuntu.sh
root@localhost:~#apt install git
root@localhost:~#git clone https://github.com/iCat21/telegram-bot
root@localhost:~#apt install nano
root@localhost:~#apt install npm
root@localhost:~#cd telegram-bot
root@localhost:~#nano index.js
Nah disini pas buka index.js nya ada disitu const Token: "masukantokenbot kalian yg sudah dibuat @botfather copy disini";
lepas sdh klik ctrl x terus ctrl y
root@localhost:~#npm install --save node-telegram-bot-api
root@localhost:~#node index.js
nah seterusnya cek bot kalian ketik /start
Selamat Mencoba :)
