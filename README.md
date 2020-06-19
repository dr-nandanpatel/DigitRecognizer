# DigitRecognizer

<b><h2>Contents</h2></b>

This repo contains:
- pretrained model(Digit_Recognizer.h5)
- model training file (train_model.py)
- model loading file (load_model.py)
- Universal GUI (gui_model.py)
- GUI for windows user (gui_windows.py)
- reuirements.txt file

<b><h2>Approach</h2></b>

Install the requirements in a virtul environment and the run load_model.py and then run gui_model.py! (using pre-trained model)

For training the model use train_model.py and make necessary modifications!

For using gui_windows.py (only for Windows users); firstly, install pywin32 using **pip install pywin32**.
This will install win32gui alongside modules for interfacing with windows.

Then run gui_windows.py!

For loading different model into the load_model.py, simply, change the value of **backend_model** as the name of your trained model and run the gui_model.py file!

Ensure that **canvas.png** file exists in the same directory!

**Query??** Email me at nandan.patel951@gmail.com
