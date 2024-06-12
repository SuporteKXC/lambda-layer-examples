cd layers/

pip install -t python/lib/python3.11/site-packages -r ./aws_requirements.txt

sls deploy

cd ../app

sls deploy