# KAGEarchives
KAGEarchives, développée par Guy Kouakou, est une application de gestion d'archives.
# KAGEarchives

KAGEarchives est une application complète de gestion d'archives développée par **Guy Kouakou**. Elle permet de cataloguer, organiser et suivre des archives physiques ou numériques grâce à une interface graphique conviviale, un serveur API REST, et une base de données SQLite robuste.

## Fonctionnalités principales

- **Authentification et rôles** : Gestion des utilisateurs avec trois rôles (Admin, Editor, Viewer) et restrictions d'accès basées sur les permissions.
- **Interface multilingue** : Support du français et de l'anglais avec traduction dynamique des éléments UI.
- **Gestion des archives** :
  - Ajout, modification, suppression et duplication des archives.
  - Validation des champs (titre, référence, dates).
  - Historique des modifications et gestion des versions avec possibilité de restauration.
- **Recherche** : Recherche simple et avancée avec filtres (type de document, statut, dates).
- **Exportation et importation** : Export vers CSV, JSON, PDF, XML, et Excel ; importation depuis CSV (partiellement implémentée).
- **Notifications** : Alertes pour les archives proches de leur date de destruction (7 jours).
- **Pagination** : Affichage paginé des archives pour une meilleure performance.
- **Sauvegardes** : Sauvegardes automatiques planifiées de la base de données.
- **API REST** : Interface Flask pour interagir avec les archives via des requêtes HTTP.
- **Personnalisation** : Thèmes clair/sombre et ajustement de la taille de la police.

## Prérequis

- **Python 3.8+**
- **Dépendances** :
  - `bcrypt` : Pour le hachage des mots de passe.
  - `reportlab` : Pour l'exportation PDF (optionnel).
  - `matplotlib` : Pour les rapports graphiques (optionnel).
  - `openpyxl` : Pour l'exportation Excel (optionnel).
  - `flask` : Pour le serveur API REST.
  - `dearpygui` : Pour l'interface graphique.

Installez les dépendances avec :
```bash
pip install bcrypt reportlab matplotlib openpyxl flask dearpygui
