# Set up Environment
pip install -r requirements.txt

# RUN
python style_transfer.py

# Change the path to the input and style image in the config file

contentImage = os.path.sep.join(["inputs", "input.png"])

styleImage = os.path.sep.join(["inputs", "starry_night.jpg"])
