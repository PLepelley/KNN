# KNN
Création du modèle de knn

### Partie 1. Prétraitement des données  
1. Remplacement des valeurs nulles par le mode  
    - Vérification des valeurs nulles par colonnes du dataframe en faisant des sommes  
    - Remplacement des valeurs nulles par le mode avec la méthode .fillna()  
    -  Vérification des valeurs nulles
	 
2. Remplacement des valeurs erronées par le mode  
	- Remplacement des valeurs erronées des colonnes Q1 à Q4 avec la méthode where()  
	- Remplacement des valeurs erronées de la colonne Q5 avec la méthode where()  
	- Remplacement des valeurs erronées des colonnes Q6 à Q10 avec la méthode where() 
	 
3. Encodage des variables avec ordinary encoder  
	 - Conversion des données en int  
	 - Encodage  
	 - Vérification des valeurs (avec value_counts)  
	 
4. Fractionnement du jeu de données  

### Partie 2. Développement IA  
1. KNN from scratch
    - Fonction distance
    - Fonction KNN
    - Accuracy

2. KNN avec Scikit Learn
    - Réalisation d’une gridsearch
    - Calcul de l’accuracy
    - Matrice de confusion	
 
