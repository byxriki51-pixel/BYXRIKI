
cd ~ && rm -rf bot-wa-riki && mkdir bot-wa-riki && cd bot-wa-riki && echo '{ "name": "bot-wa-riki", "version": "1.0.0", "description": "Bot WA by Byxriki", "main": "index.js", "scripts": { "start": "node index.js" }' > package.json && echo 'node_modules/
session/
*.log
.env' > .gitignore && echo '#!/bin/bash
clear
echo "INSTALL BOT WA RIKI BYXRIKI"
pkg update && pkg upgrade -y
pkg install git nodejs ffmpeg imagemagick -y
npm install
echo "SELESAI! Jalankan: npm start"' > install.sh && chmod +x install.sh && echo '# BOT-WA-RIKI 🤖
Bot WhatsApp by **Byxriki**

### 📥 CARA INSTALL 1 KLIK
`pkg update && pkg upgrade -y && pkg install git nodejs ffmpeg imagemagick -y && git clone https://github.com/byxriki51-pixel/bot-wa-riki && cd bot-wa-riki && bash install.sh && npm start`

Terus scan QR

### 👨‍💻 AUTHOR
Byxriki - https://github.com/byxriki51-pixel' > README.md && git init && git add . && git commit -m "Rilis v1.0 Lengkap" && git branch -M main && git remote add origin https://github.com/byxriki51-pixel/bot-wa-riki.git && git push -u origin main
