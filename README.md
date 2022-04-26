Introduction
A CNN based model has been made for distracted driver detection. The dataset consists of 10 categories that classify the main 10 ways a driver gets distracted.
Files to be found: (the folder submitted on NESS)
1. Structured Abstract
2. Report on main notebook(.ipynb) notebook
3. There are 2 more ipynb notebooks in miscellaneous folder if in case other models and there shortcomings are to be verified. But if it is needed to be executed and checked it is recommended to run just the main ipynb notebook.
3. Snapshot of git log from github
4. test images in test folder

Steps to replicate:

1. Download the ipynb file and directly run in google colaboratory.
2. You first need the access of the dataset as it is not publicly available, you need to participate in kaggle competition and generate a token to download kaggle .json file which can then directly be used to access datset in google colab.
3. After the dataset is uploaded to the colab notebook or placed in the folder of jupyter, rename the zip folder to driverData.Then upload images from test images folder to your runtime.
4. Just press run all button and the full models would run and get the accuracy in front of you.
5. As per google colab to save this file you can download it as ipynb and can also view it in vs code.

Platform used:
This project has been made and tested on google colab, with 25GB ram and 225gb hardisk space. It would easily be replicated in a similar or better environment. It may need some additional encoding for different OS.


Miscellaneous:
If your environment doesn't have any packages installed for these libraries:
1. Pandas
2. MatplotLib
3. Pandasql
4. tensorflow
5. cv2
6. OS
7. Keras

just run pip install (name of the library)


