# memoire_covid_uvs
Detection des zones d'interet covid sur des images xray de covid ieee https://github.com/ieee8023/covid-chestxray-dataset apres entrainement du model de detection notebook detecetion.ipynb . 
les annotation utilent pour la segmention des poumons proviennent de la meme source annote par le docteur cohen. ils ont servient pour contruire les models de segmenetations pour les tests en inferences. 
D'autres source de données sont aussi utilisées pour d'autre methodes de segmentatons celles-ci avec une multiclassification sur trois channels, toujours avec UNET choisis pour ce travail de memeoire
La segmentation est faite avec un model unet de segmentation_models pour nous predire le mask d'un poumon une fois que le model est entrainer 
Lien dataset https://drive.google.com/drive/folders/1vFJ8r8QHkfXR_OqSrF1PWCY_snNTV015 des images et des mask avec comme refenece
