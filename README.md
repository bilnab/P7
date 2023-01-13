# P7  
<img src="/img/cs.png" width="150"> <img src="/img/aml.png" width="150"> <img src="/img/keras.png" width="150">   
<img src="/img/hug.png" width="150"> <img src="/img/bert.png" width="150">   
 
**Projet de NLP consistant à prédire le sentiment associé à un tweet**  
  
L'enjeu consiste à concevoir un modele fonctionnel récupérant le tweet et fournissant le sentiment prédit selon 3 approches:     
* API étagère de azure cognitives services  
* modèle bespoke simple utilisant une regression logistive mettant en oeuvre le designer de azure ML
* modèle bespoke avancé type deep learning à deployer avec 3 niveaux de complexité testés:  
	* modèle keras de base  
	* modèle keras avec couche LSTM  
	* modèle transformer type BERT  


## Ressources:    
[Jeu de données annotées](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/AI+Engineer/Project+7%C2%A0-+D%C3%A9tectez+les+Bad+Buzz+gr%C3%A2ce+au+Deep+Learning/sentiment140.zip)      
  
Autres ressources utiles:  
[Deploiement API de prediction](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Webinars/Data/API_Dec_2020/corrige%CC%81_deploy_ml_api.zip)  
* Librairie BERT HuggingFace:   
[Principe de BERT](https://lesdieuxducode.com/blog/2019/4/bert--le-transformer-model-qui-sentraine-et-qui-represente)  
[Exemple de code](https://swatimeena989.medium.com/bert-text-classification-using-keras-903671e0207d)  
[Librairie huggingface](https://huggingface.co/transformers/)  
[Github bert](https://github.com/google-research/bert)  
* Azure:  
[Text analytics](https://docs.microsoft.com/fr-fr/azure/cognitive-services/text-analytics/quickstarts/client-libraries-rest-api?tabs=version-3-1&pivots=programming-language-python)  
[Azure Machine Learning](https://docs.microsoft.com/fr-fr/learn/paths/build-ai-solutions-with-azure-ml-service/)  
[Jupyter dans Azure Machine Learning](https://docs.microsoft.com/fr-fr/azure/machine-learning/tutorial-1st-experiment-sdk-setup)  
[Exemple de notebook dans Azure ML](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Ing%C3%A9nieur_IA_P7/img-classification-part2-deploy.ipynb)  
[Deployer un modèle dans Azure Machine Learning](https://docs.microsoft.com/fr-fr/azure/machine-learning/tutorial-deploy-models-with-aml)  
[Exemple designer Azure ML](https://docs.microsoft.com/fr-fr/azure/machine-learning/samples-designer)  
* KERAS:  
[Analyse de sentiment : Modèle simple](https://docs.microsoft.com/fr-fr/learn/modules/analyze-review-sentiment-with-keras/2-build-and-train-a-neural-network)  
[Analyse de sentiment : modèle LSTM](https://towardsdatascience.com/understanding-lstm-and-its-quick-implementation-in-keras-for-sentiment-analysis-af410fd85b47)  
 
  

## Script   
[un notebook mettant en oeuvre azure cognitive services](/P7%20azure%20cognitive%20services.ipynb)  
[un notebook mettant en oeuvre l'entrainement sur azure ML](/P7%20azure%20training.ipynb)  
[un notebook mettant en oeuvre les modeles deep leraning ltsm et bert en local](/P7%20LTSM-Bert-local.ipynb)  
[un notebook mettant en oeuvre le deploiement du modèle bert](/P7%20azure_bert_deploiement.ipynb)  
 
 
## Présentation PDF:  
[pdf complet](/P7.pdf)  
<img src="/img/P7%20pres.png" height="300">  
