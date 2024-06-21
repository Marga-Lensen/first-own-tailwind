André Rühmling
8:32 AM
Ed Sheeran als WebDev
Dursel Türkan
8:33 AM
morgeeen
André Rühmling
8:34 AM
i cant help pfolen in love viss shuh
Doris Pasic
8:34 AM
oooooookay... da kommt man mal paar minuten zu spät ... XD
Mame Angelique Guisse
8:34 AM
Maleika
Dursel Türkan
8:35 AM
woow :D
Manfred Berginski
8:38 AM
Ab sofort singen wir unsere Codes :D
Doris Pasic
8:38 AM
Das ist dann wie die "Band" der Hörakustik-Lehrer von vor knapp 20 Jahren ;)
Torben-Michael Frömke
8:38 AM
^^
André Rühmling
8:40 AM
Bandname?
h -> hight 
t -> talented
m -> music
l -> lover
Torben-Michael Frömke
8:41 AM
haha
André Rühmling
8:42 AM
C -> Crazy
S -> Singer
S -> Songwriter
Torben-Michael Frömke
8:42 AM
oder CSS = Casual Style Singers^^
André Rühmling
8:42 AM
👍
André Rühmling
8:46 AM
heißt es nicht circulum vitae
?
Chaima Mnasri
8:50 AM
CV meinst du ?
André Rühmling
8:51 AM
Ja, habs aber schon das richtige gefunden: Curriculum Vitae
😅
Chaima Mnasri
8:51 AM
ahh ok hhhhhhh :D
André Rühmling
8:57 AM
--md-center
Torben-Michael Frömke
9:29 AM
wie heute morgen angekündigt, muss ich jetzt leider jetzt zu einem termin. Bis später.
Dursel Türkan
10:15 AM
hat schritt 8 bei euch geklappt?
Sonja Linhard
10:16 AM
rebuilding    done in 2378ms   ....
steht bei mir...
Dursel Türkan
10:17 AM
bei mir steht wieder mal syntax error komisch
André Rühmling
10:19 AM
Auch nach dem update bin ich noch auf v12.22.9
Dursel Türkan
10:20 AM
ich habe dieselbe version
Ndimofor Aretas
10:22 AM
sudo npm install -g --force node@latest
Ndimofor Aretas
10:24 AM
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
Sonja Linhard
10:27 AM
v18.20.3
André Rühmling
10:28 AM
bei einigen ist node schon volljährig ^^
Ndimofor Aretas
10:28 AM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
Manfred Berginski
10:29 AM
Bei mir hats geklappt! Hab jetzt Version 20.15.0
Anca-Mihaela Burlacu
10:30 AM
bei mir auch
Ndimofor Aretas
10:31 AM
nvm install 20.11.0
Se-A Yang
10:35 AM
bei mir hat es jetzt auch nach terminal closing geklappt wie bei andré
Ndimofor Aretas
10:35 AM
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
André Rühmling
10:46 AM
Mamas Tee?
André Rühmling
10:51 AM
rm -rf Tailwind
Dursel Türkan
10:53 AM
endlich sind alle Schritte durch
nzb-cvdn-fqn


sudo rm -rf /usr/local/bin/npm /usr/local/share/man/man1/node* ~/.npm
sudo rm -rf /usr/local/lib/node*
sudo rm -rf /usr/local/bin/node*
sudo rm -rf /usr/local/include/node*

sudo apt-get purge nodejs npm
sudo apt autoremove

Magdalena Karolina Okroj
11:28 AM
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# download and install Node.js (you may need to restart the terminal)
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.15.0`

# verifies the right NPM version is in the environment
npm -v # should print `10.7.0`
