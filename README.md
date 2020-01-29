# opencv-r

1)installez l'ensemble des librairies avecla commande suivante 

pip install -r requirements.txt


2) Premier exemple :

python recognize.py --detector face_detection_model \
	--embedding-model openface_nn4.small2.v1.t7 \
	--recognizer output/recognizer.pickle \
	--le output/le.pickle \
	--image images/adrian.jpg


3) Deuxiéme exemple:


python recognize.py --detector face_detection_model \
	--embedding-model openface_nn4.small2.v1.t7 \
	--recognizer output/recognizer.pickle \
	--le output/le.pickle \
	--image images/trisha_adrian.jpg 
