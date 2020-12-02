# memo-app

> A Vue.js project

## Let's see
https://youtu.be/hO4PuVK_v64

## Build Setup

``` bash
#init submodules
git submodule init
git submodule update

#set vue.js
cd ./vue-proj
npm install
npm run build
cd ..

#set express
cd ./express-proj
npm install

# start express
pm2 start pm2.config.js --env production
