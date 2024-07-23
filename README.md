# Fingerprint_Matching
This Python program implements fingerprint matching using the Scale-Invariant Feature Transform (SIFT) algorithm and the FLANN (Fast Library for Approximate Nearest Neighbors) matcher from OpenCV (cv2). It's designed to work with the SOCOFing dataset from Kaggle, which contains over 11,000 real and altered fingerprint images.

Features:

SIFT Keypoint Detection: Identifies distinctive features within fingerprint images that are robust to scaling and rotation.
FLANN Matching: Efficiently finds the closest matching keypoints between two fingerprint images.
Matching Score: Calculates a score based on the number of successful keypoint matches, indicating the similarity between fingerprints.
Kaggle SOCOFing Dataset Support: Designed to work seamlessly with the SOCOFing dataset structure.

# Requirements:

Python 3.x

OpenCV (cv2) library (install using pip3 install opencv-python)

# Usage:
Download the SOCOFing dataset from Kaggle. (https://www.kaggle.com/ruizgara/socofing)

Modify the fingerprint_path variable in the script to point to the directory containing your fingerprint images.

Run the script: python main.py

The program will prompt you to enter the path to a query fingerprint image.

It will compare the query image to all other images in the dataset and display the fingerprint with the highest matching score.

# Results:
![image](https://github.com/user-attachments/assets/edd2ecea-aa05-4264-849b-51c67c5e82aa)
![image](https://github.com/user-attachments/assets/5b33cb6d-abfb-4085-bf18-959f1f3b55ce)

Note:

This program provides a basic implementation of fingerprint matching. More advanced techniques and optimizations can be explored for real-world applications.
Fingerprint matching accuracy depends on factors like image quality and fingerprint alterations.
