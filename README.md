# MovieMatchMaker
Une plateforme de recommandation de films, développée avec Python et Streamlit, qui permet aux utilisateurs de rechercher des films par nom et de découvrir des suggestions de films similaires, basées sur des caractéristiques communes et la similarité de contenu.

🌟 Introduction: Projet Machine Learning
MovieMatchMaker est une plateforme de recommandation de films en fonction des préférences des utilisateurs. Ce projet inclut des étapes complètes de prétraitement, de nettoyage, d’entraînement de modèles en Python, puis d’interface via Streamlit pour offrir une expérience utilisateur simple et agréable.

⚙️ Fonctionnalités
Filtres de Recommandation : Basé sur la similarité des genres, évaluations, et historiques.
Interface Intuitive : Interface utilisateur créée avec Streamlit pour une utilisation facile.
Recommandations : Génération rapide de suggestions de films.


🚀 Technologies Utilisées
Python : Pour le traitement des données, le nettoyage, et l’entraînement des modèles.
Machine Learning : Algorithmes de similarité de contenu et autres caractéristiques
Streamlit : Pour concevoir une interface utilisateur interactive.


📂 Structure du Projet
data/ : Ensemble des fichiers de données utilisés pour l’entraînement et la validation des modèles.
movies.pkl : Modèle de machine learning pré-entraîné dans ce projet.
app.py : Fichier principal pour lancer l’application Streamlit.
README.md : Documentation complète du projet.


📖 Guide d’Utilisation:
Cloner le dépôt :
git clone https://github.com/mdtech100/MovieMatchMaker.git
cd MovieMatchMaker

Installer les dépendances :
pip install -r requirements.txt

Lancer l’application :
streamlit run app.py


📈 Modèles de Machine Learning
Le modèle de recommandation inclus dans ce projet est basé sur :
-Système de Similarité de Contenu : Recommandations basées sur les genres et caractéristiques des films.
