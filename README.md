# memo-app

> A Vue.js project

## Build Setup

``` bash
#init submodules
git submodule init
git submodule update

# build vue.js
cd ./vue-proj
npm run build
cd ..

# start express
cd ./express-proj
pm2 start ./bin/www 
