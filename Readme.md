# Search Logos
Search for similar logos if an image is uploaded or provide one if used the input text.

## Install requirements 
use the command line

`pip install -r requirements.txt`

## App - Streamlit
To run the streamlit app run:

`steamlit run main.py`

Note: you will need a weaviate server running, so if you have not one, you can use the Docker instructions.

## Docker
To run the Weaviate server use the command: 

`docker compose -f docker-compose-weaviate.yml build`

And then run:
`docker compose -f docker-compose-weaviate.yml up -d`


## Basic Run
 1. Put the logos under a folder named `data_source`
 2. On the app, running in `http://localhost:8501/`, press the `Reload data` button
 3. Describe a logo or upload a similar one
 4. Get results