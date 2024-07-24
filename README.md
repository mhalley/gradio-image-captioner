In order to use this code, you must first create a Python virtual environment and install Gradio using the following commands in the terminal:

```
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
```

Then, you'll need to install the required libraries in the environment:

```
# installing required libraries in my_env
pip install langchain==0.1.11 gradio==4.21.0 transformers==4.38.2 bs4==0.0.2 requests==2.31.0 torch==2.2.1
```

To run this file, type the following command in the terminal: 

```
python3 image_captioning_app.py
```

The web app should start running and display a URL where you can access the interface. Open the provided URL in a web browser (in the terminal). 

You should see an interface with an image upload box. Upload an image and click Submit. You should see an AI generated caption in the Output box.

To quit the application, type `ctrl + c` .
