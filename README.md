# python

cd python/layers/dependencies/

pip install -t python/lib/python3.11/site-packages -r ./aws_requirements.txt

cd ../

sls deploy

cd ../app

sls deploy


# node

cd node/layers/dependencies/nodejs/node18

npm install

sls deploy

cd ../../../../app

sls deploy