## How to Run

Download the Keypad folder. Open a terminal and run following commands in anaconda prompt-

C:> conda create -n tf_app pip python=3.7

C:> activate tf_app

(tf_app) C:>python -m pip install --upgrade pip

(tf_app) C:>pip install tensorflow-object-detection-api

(tf_app) C:> pip install flask

(tf_app) C:> pip install tensorflow==1.13.1

(tf_app) C:> conda install -c anaconda protobuf

(tf_app) C:> pip install pillow

(tf_app) C:> pip install lxml

(tf_app) C:> pip install Cython

(tf_app) C:> pip install contextlib2

(tf_app) C:> pip install jupyter

(tf_app) C:> pip install matplotlib

(tf_app) C:> pip install pandas

(tf_app) C:> pip install opencv-python

Now test the web application by running following commands-

(tf_app) C:> cd C:\my_repo

(tf_app) C:\my_repo> python main_app.py

Web app can be accessed from http://127.0.0.1:5000/