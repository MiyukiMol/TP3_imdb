# TP3_imdb

Conclusion:

<b>J'ai utilisé 2 modèles, LogisticRegression et svc.</b>
<b>Je constate qu'il a fallu 40 heures pour le grid search pour le modèle svc et que je ne pouvais pas règler bien car il me demande trop de temps. C'est pour cela que le résultat avec mon modèles svc est over fitting et je n'ai pas eu de temps pour aller loin. Je pense que le modèle avec LogisticRegression est mieux même si j'aurai du temps.</b>
<b>J'ai obtenue le meilleur test accuracy score 0.88 avec LogisticRegression(C=0.01, class_weight='balanced', random_state=42, warm_start=True)</b>

Projet
Le but de ce brief est de s'approprier certains fondamentaux du traitement automatique du langage naturel sur un exemple d'application : 
l'analyse de sentiments avec  Internet Movie Database (IMDb) 

Contexte du projet

La base de données Internet Movie Database (IMDb) est considérée le "Hello World" du traitement automatique du langage naturel. Les données d'entrée sont des critiques de film rédigées en anglais par les spectateurs. La critique est labellisée 0 si elle est négative, 1 si elle est positive. On parle alors d'analyse de sentiments. L'objectif de ce travail est d'utiliser cette base de données pour acquérir certains fondamentaux du traitement automatique du langage naturel. Pour cela, il va falloir tout d'abord construire une présentation de type Powerpoint se déroulant selon le plan suivant :

    Qu'est-ce-que le traitement automatique du langage naturel ?
    Quelles sont ses applications ? (une diapositive)
    Qu'est-ce-que l'analyse de sentiments ? (une diapositive)
    Décrire la base de données IMDb (une diaposivite). La base de données IMDb peut se charger selon deux manières :
        Avec les données d'entrée stockées sous forme textuelle ;
        Avec les données d'entrée stockées sous forme de suite de nombres entiers, chaque nombre entier encodant un mot. C'est cette version que nous allons utiliser dans un premier temps avec la ligne TensorFlow/Keras suivante : (train_samples, train_labels), (test_samples, test_labels) = imdb.load_data(num_words=10000). Décrire dans la présentation ce principe d'encodage de mots par des nombres entiers.
    Cette séquence de nombres entiers peut ensuite être encodée à son tour en utilisant l'encodage One-Hot. Décrire dans la présentation ce principe.

Entrainer ensuite dans un (enfin trois !) Jupyter Notebooks un ou plusieurs modèle(s) de Machine Learning de votre choix en utilisant la librairie scikit-learn sur les données IMDb que vous aurez encodées au format One-Hot.


