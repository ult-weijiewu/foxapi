# Ripplefox Api

## REST market price lastest 24hours

### GET /v2/exchanges


### GET /v2/exchanges/pair/:pair

request parameters:

name:   pair 	
Ranges: xrpcny, xlmcny, ultcny, ultxrp, xlmxrp


# Install

## install nvm
sudo curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

## install node
nvm install node

# install yarn

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt-get update && sudo apt-get install yarn




