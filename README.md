# microservice-APIs
Code from Microservices API book.  my version with corrections.


To run the environment, make sure pipenv is installed. Navigate to source folder and ensure the Pipfile.lock file is at the root.


python3 -m pipenv install --dev
python3 -m pip install uvicorn 
python3 -m pipenv shell
uvicorn orders.app:app --reload

defaults to 
http://127.0.0.1:8000/docs#/