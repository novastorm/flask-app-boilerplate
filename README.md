Activate Python virtualenv

virtualenv .venv
virtualenv .venv --python=python2.7

source .venv/bin/activate

install python requirements

pip install -r requirements.txt


Activate Node.js virtualenv

nodeenv .nodeenv

source .node_env/bin/activate

install node requirements

npm install -g yarn

yarn add --dev webpack babel-core babel-loader babel-preset-react babel-preset-es2015 node-sass css-loader sass-loader style-loader

yarn add react react-dom

yarn install

# build UI

npm run build
npm run build-dev
npm run watch