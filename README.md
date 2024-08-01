# Projet de Prédiction de maladie d'Asthme en utilisant SparkMLlib
----

Ce projet vise à développer un **modèle prédictif pour l'asthme** en utilisant des techniques avancées d'analyse de données avec Apache Spark. En se basant sur les algorithmes de **RandomForestClassifier**, **Régression Linéaire**, et **Régression Logistique**, le modèle intégrera des variables importantes pour améliorer la précision de la prédiction des épisodes symptomatiques. 

L'utilisation de **SparkMLlib** permettra de traiter de grandes quantités de données de manière efficace et rapide, exploitant la puissance de calcul parallèle d'Apache Spark.

L'objectif est de créer un outil qui puisse mieux prévoir les épisodes d'asthme et ainsi améliorer la gestion de cette maladie chronique.

---
                                                                                        
![spark](spark.png)


----
Les variables de dataset sont :
## Variables 

- **Tiredness** : Fatigue générale, sensation de lassitude
- **Dry-Cough** : Toux sèche
- **Difficulty-in-Breathing** : Difficulté à respirer
- **Sore-Throat** : Mal de gorge
- **None_Symptom** : Absence de symptômes
- **Pains** : Douleurs corporelles générales
- **Nasal-Congestion** : Congestion nasale
- **Runny-Nose** : Écoulement nasal
- **None_Experiencing** : Absence d'expérience de symptômes
- **Age_0-9** : Catégorie d'âge : 0-9 ans
- **Age_10-19** : Catégorie d'âge : 10-19 ans
- **Age_20-24** : Catégorie d'âge : 20-24 ans
- **Age_25-59** : Catégorie d'âge : 25-59 ans
- **Age_60+** : Catégorie d'âge : 60 ans et plus
- **Gender_Female** : Genre : Féminin
- **Gender_Male** : Genre : Masculin
- **Severity_Mild** : Sévérité : Légère
- **Severity_Moderate** : Sévérité : Modérée
- **Severity_None** : Absence de sévérité (Aucun symptôme ou très léger)




