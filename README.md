
# Cervical Cancer Risk Analysis ⚕💻

![Licence](https://img.shields.io/badge/Licence-MIT-green.svg) ![Statut](https://img.shields.io/badge/Status-Terminé-green.svg) ![Langage](https://img.shields.io/badge/Language-R-blue.svg)

##  Description

Ce projet a pour objectif d'effectuer une analyse statistique du risque de développer un cancer du col de l'utérus.  
Un rapport statistique détaillé est disponible sur la page GitHub : [👉 Statistical Report](https://andreaboniffay.github.io/statistical_report/about-this-work.html)  

<img src="https://github.com/user-attachments/assets/1b4aa078-1cbd-4de3-8b48-1e9ee2b2d05c" width="500"/>  

Un résumé de ce rapport est disponible sous forme d'article dans le repo : [👉 Article](https://github.com/AndreaBoniffay/statistical_report/blob/main/Article_cervical_cancer.pdf)  
<img src="https://github.com/user-attachments/assets/4bb6a126-8f62-44a4-9297-d2ba6c12e447" width="500"/>  



##  Dataset

Pour ce projet, nous utilisons la base de données : *Breast Cancer Wisconsin (Diagnostic)* fournie par le UCI Machine Learning Repository.  
- **URL :** [🔗 UCI Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data)  
- **Référence :** [📖 Wolberg, William, Mangasarian, Olvi, Street, Nick, et Street, W. (1995).](https://doi.org/10.24432/C5DW2B)



##  Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/AndreaBoniffay/statistical_report.git
   ```
2. Accéder au dossier du projet :
   ```bash
   cd statistical_report
   ```
3. Installer les dépendances :

Le script `main.rmd` installe automatiquement les packages manquants.

##  Utilisation

Pour exécuter le projet et générer le rapport statistique :

1. 📝 Ouvrir le fichier `pilotage.rmd`
2. 🚀 Lancer le chunk suivant :
   ```r
   library(bookdown)
   render_book("_bookdown.yml")
   ```

##  Licence

Ce projet est sous licence MIT - voir le fichier [📄 LICENSE](LICENSE) pour plus de détails.

##  Contact

Créé par [📩 Andréa Boniffay](https://andreaboniffay.github.io) - N'hésitez pas à me contacter ! 

