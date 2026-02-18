# Overview
This project presents an integrated speech-enabled service that allows third-party applications to interact with users through voice input. The system converts speech into actionable commands, enabling more natural human–computer interaction and improving accessibility.

The service demonstrates how voice interfaces can be embedded into existing applications to enhance user experience, automation, and accessibility.

## Objectives
-  Develop a voice extraction system:
-  Build a Natural Language Processing System
-  Integrate Speech Recognition into a Web Application 

## System Architecture
The system follows a structured pipeline:
Voice Input Capture – *User speech is captured through a microphone.*
Speech Processing – *Audio is converted into text using speech recognition.*
Command Interpretation – *Text is analysed and mapped to application commands.*
Application Response – *The third-party application executes the requested action.*
Output Delivery – *Response is returned to the user.*

### Technologies Used
-  Python 
-  HTML 

## Project Structure

```
├── src/                 # Core application logic
├── templates/           # HTML interface files
├── static/              # Frontend assets
├── models/              # Processing modules
├── txt                  # Project dependencies
└── README.md            # Project documentation
```

## Results
The system successfully demonstrates reliable speech recognition using the whisper model and command execution, improving interaction efficiency and enabling seamless integration with external applications.

## Index
**How to Run**
The Jupyter notebook (.ipynb file) in this folder guides you through training a fine-tuned Whisper model. Running the notebook on Google Colab with a GPU will successfully train the model.

**Downloading the Model**
After training, the model and its processor can be downloaded for further use.

**Updating the Python Scripts**
In the provided Python scripts (.py files), replace the existing links with the links to the downloaded trained model and processor.
