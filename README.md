 This is simple eye_detector from images.we used dlib , opencv, utils for detecting eyes from images.

#installation

conda install -c conda-forge opencv 

pip install dlib

pip install argparse

pip install numpy

#Run the below commands

git clone https://github.com/Aryann-rajnish/eye_detector

cd /detect_eyes/

python detect_face_parts.py --shape-predictor shape_predictor_68_face_landmarks.dat --image images/face.jpg
