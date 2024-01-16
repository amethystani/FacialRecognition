# FacialRecognition using Eigen Values
To run the program, follow these steps:

1. Ensure you have the following prerequisites installed:
   - Python 3.x
   - OpenCV (`pip install opencv-python`)
   - NumPy (`pip install numpy`)
   - Matplotlib (`pip install matplotlib`)
   - scikit-learn (`pip install scikit-learn`)

2. Download the face image dataset and save it as "attface.zip" in the same directory as the program.

3. Open a text editor and create a new file. Copy and paste the code provided into the file.

4. Save the file with a ".py" extension, for example, "eigenfaces.py".

5. Open a terminal or command prompt and navigate to the directory where the file is saved.

6. Run the program by executing the command: `python eigenfaces.py`.

The program will perform the following actions:
- Read the face images from the "attface.zip" file and display a sample of 16 face images.
- Print information about the dataset, including the shape of the face images, the number of classes, and the number of images.
- Perform PCA on the dataset and extract the first 50 eigenfaces.
- Display a sample of 16 eigenfaces.
- Generate weight vectors for each face image based on the eigenfaces.
- Test the recognition algorithm on two out-of-sample images, displaying the query image and the best match image along with their Euclidean distance.

Note: Make sure the "attface.zip" file contains the correct dataset with face images organized in folders named "s1" to "s40".
