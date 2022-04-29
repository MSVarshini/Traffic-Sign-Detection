# TRAFFIC SIGN DETECTION
TRAFFIC SIGN DETECTION is a project which detects the Traffic Signs. It will take the input and recognises what sign it belongs to and produces output in the form of audio.

### DATASET :
we used German Traffic Sign Recognition Benchmark(GTSRB) Dataset. It contains around 40,000 images classified into 43 labels( 43 different traffic signs).
Dataset link : https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

### RUN THE PROJECT :
1. Get all the data from the GitHub, Open Command prompt or any other Terminal and run the command :    
&nbsp;  \$git clone https://github.com/MSVarshini/Traffic-Sign-Detection
2. Open Google Colab and open the Traffic_Detection.ipynb notebook <br>
      1. Run cells in the order change paths to your local paths where ever needed.
      2. traffic_detector.h5 will be downloaded in Models folder. Running "Traffic_Detection.ipynb" can be skiped as there is our trained model already present in the folder
3. Run the GUI.py file using the command prompt or Spyder
      1. New window will be opened with an upload button
      2. You can upload any image and it will give the traffic sign in audio format


