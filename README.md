Install Node Js - 

# Using Ubuntu

curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs


Install NVM - 
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
source ~/.profile
nvm ls-remote


Install Angular 6
sudo npm install -g @angular/cli@6.0.7


Git Clone - 
git clone https://atique12@bitbucket.org/atique12/mongocrud_application_frnt_end.git
git clone https://atique12@bitbucket.org/atique12/mongocrud_application_back_end.git

Edit Backend Repo Code - 
db.js & index.js

Edit Frontend Repo Code - 
src/app/shared/person.services.ts 

Install PM2 Global - 
sudo npm install pm2 -g


pm2 start index.js
pm2 save

Output

[PM2] Saving current process list...
[PM2] Successfully saved in /home/ubuntu/.pm2/dump.pm2


For Running Frontend Application If you are getting Node Sass Issue

Here's the solution:

sudo npm install --save-dev  --unsafe-perm node-sass


If thist doesn't work try to install from a mirror

npm install -g mirror-config-china --registry=http://registry.npm.taobao.org
npm install node-sass --save

Enjoy!!

