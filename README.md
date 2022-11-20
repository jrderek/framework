# BIRD Cookiecutter streamlit-fastapi-model-serving-monitoring

Step 1: Install and run docker desktop
Step 2: Go to Azure Git DevOps and sync this code
Step 3: Open VS Code

When developing simple APIs that serve machine learning models, it can be useful to have _both_ a backend (with API documentation) for other applications to call and a frontend for users to experiment with the functionality.

In this cookie cutter , we serve an [image semantic segmentation model](https://pytorch.org/hub/pytorch_vision_deeplabv3_resnet101/) using `FastAPI` for the backend service and `streamlit` for the frontend service. `docker-compose` orchestrates the two services and allows communication between them.

Step 4: Run
To run the example in a machine running Docker and docker-compose, run:

    docker-compose build
    docker-compose up

To visit the FastAPI documentation of the resulting service, visit http://localhost:8000/docs with a web browser.  
To visit the streamlit UI, visit http://localhost:8501.

Logs can be inspected via:

    docker-compose logs

Step : Ctrl C to close 

Step : docker-compose down 
to stop the containers


Cheatsheet for streamlit can be found here:
https://daniellewisdl-streamlit-cheat-sheet-app-ytm9sg.streamlitapp.com


