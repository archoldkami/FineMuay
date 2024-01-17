FineMuay - 2023

This project is part of TFM for Visual Analytics and Big Data Master course.

The purpose of this work is to propose a system to support Muay Thai judging training,  to new people interested on this contact sport, based on both pre-recorded and real-time video analysis.

To this the FineMuay dataset has been built and is available on a zip file through the link https://drive.google.com/file/d/1PNIsTprpgqWu6MXyEq4dO7n-wcnbkScK.

A reduced frame (16fps) version is available on zip
https://drive.google.com/file/d/1q3S7A-qOnwQuRdLoQ7ioFiseHJaCGQbh

These datasets contains videos of Muay Thai knees that have been recorded from one guard and then flipped to achieve videos with the opposite guard. Initially the system only recognizes knees and the guard position of a person. 

This work uses Google Colab, PYSKL and OpenMMLab to train the PoseC3D and ST-GCN++ models, which are used for pose inference. Please visit their webpages

OpenMMLab  https://github.com/open-mmlab
PYSKL      https://github.com/kennymckormick/pyskl
Colab      https://colab.google/


For video processing, a client was developed in a Jupyter notebook on a local machine.  Real-time video streaming is implemented by NGROK and Imagezmq. 

NGROK      https://ngrok.com/
Imagezmq   https://github.com/jeffbass/imagezmq


The code is available for Educational or commercial purposes

The video files are for educational and research purposes only
Commercial use for video matherial is not authorized.
Any questions you can contact by email finemuay@gmail.com or camilozano@yahoo.com

Thanks to Ramakien Academy in Bogota-Colombia and their students to share this videos to the Community.


