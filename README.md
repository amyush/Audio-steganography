# Audio-steganography
**_Hiding the message in an audio file. LSB-Steganography is used in this project_**

# Pre-requisite
-   Git-Hub account
-   Python 3
-   pip

# Inputs
**Encoding the messgae**
  -   **Filename** - This takes the name of the file alongwith the extension where the message is to be encoded(hidden).
  -   **Key** - This is the secret key which is used to encode the message. Here, key is used to decide the bits where the message bits are to be encoded.
  -   **Message** - This is the message which is to be hidden in the audio.

**Extracting the message**
- **Key** - This is the secret key which is used to encode the message. Here, key is used to decide the bits where the message bits are to be encoded.

# How-to-run
  - Step-1 Open the .ipynb file in colab or jupyter notebook.
  - Step-2 Run all the cells from the beginning.
  - Step-3 Finally run the **result** segment to see the results of both encoding the message in the audio file and extracting the message from the audio file.

![image](https://user-images.githubusercontent.com/19607227/150329261-46265f3d-72be-492b-ac4f-b833ed63dc23.png)

# For running encoding and extracting separately

**Run the Encode the message part only to encode the message**
![image](https://user-images.githubusercontent.com/19607227/150329303-a6a6352c-756c-46a0-bcbb-e63d61b35995.png)

**Run the Extract the message part only to extract the message from the encoded audio**
![image](https://user-images.githubusercontent.com/19607227/150329325-24681ced-b8b7-4480-b57e-6f8e92dd88c1.png)

# Downloading the encoded audio
After running the encode function, click on the panel and open the Files(local storage) in Colab. Go to the Audio-steganography folder. The required file will be named as **encodedAudio.wav**.
