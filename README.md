# Atomatic-Attendence-System
## Atomatic Attendence System using face recognition
## <br><b>Steps to follow:</b>
#### Step 0)Create a python environment with version 3.5.0(Compulsory step) 
        Then,
        Install the all packages use following command
        pip install -r requirements.txt
#### Step 1)Create Dataset (refer Videotoimg.ipynb)
        Divide the images like folderstructure.png
#### Step 2)Working with google Colab(if you don't know refer this https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d)
        Upload the dataset to google Drive and face_detection_model folder
        Now the colab folder structure should look like colabstructure.png
#### step 3)Crop the faces and save them to original paths.(refer facex.ipynb)
        For better results I'm doing this.
#### step 4)Train the model(refer vggface.ipynb)
        Colab work is done.
        Now download the filename.hdf5 file from the google drive,which is saved using model.save(filename.hdf5)
#### step 5)Integrate the trained model with openCV to recognize the faces(refer output.ipynb) locally.
        The folder structure should be project.png
        Run the output.ipynb locally
