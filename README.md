# memoire_covid_uvs
detection zones covid sur des images xray de covid ieee https://github.com/ieee8023/covid-chestxray-dataset.
les annotation utilent pour la segmention des poumons proviennent de la meme source annote par le docteur cohen. ils ont servient pour contruire les models de segmenetations pour les tests en inferences. 
D'autres source de données sont aussi utilisées pour d'autre methodes de segmentatons celles-ci avec une multiclassification sur trois channels, toujours avec UNET choisis pour ce travail de memeoire
La segmentation est faite avec un model unet de segmentation_models pour nous predire le mask d'un poumon une fois que le model est entrainer 
