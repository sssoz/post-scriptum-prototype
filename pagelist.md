# Pages uniques
Accueil `home`
Liste des actualités `all-news`
Liste des parutions `all-issues`
Liste des entretiens `all-interviews`
Liste des compte rendus `all-reports`
À propos (statique) `about`

# Pages multiples (« gabarits »)
Nouvelles `news-item`
  Possiblement même gabarit qu'`article` mais avec une photo (donc `interview`)
Parutions `issue`
Articles `article`
Articles de type compte rendu `interview`
  Possiblement même gabarit qu'`article` mais avec une photo

# Structure
Accueil
      |
      |-- Liste des actualités
      |                      |
      |                      `-- [Une nouvelle]
      |                                      
      |-- Liste des parutions
      |                     |
      |                     `-- [Une parution]
      |                                    |-- Une parution régulière (avec présentation)
      |                                    |                        |
      |                                    |                        `-- Un article
      |                                    |                                     |
      |                                    |                                     |-- [Un article régulier]
      |                                    |                                     |
      |                                    |                                     |-- [Un compte rendu]
      |                                    |                                     |
      |                                    |                                     `-- [Un entretien]
      |                                    |                        
      |                                    |
      |                                    `-- Un supplément à une parution
      |                                                                   |
      |                                                                   `-- Un article
      |                                                                                |
      |                                                                                 `-- ...
      |-- Liste des entretiens
      |                      |
      |                      `-- [Un entretien]
      |
      `-- Liste des compte rendus
                                |
                                `-- [Un compte rendu]



# Metadata
Parution
  Titre
  Numéro
  Date (mois et année)
  Saison
  Introduction / présentation
  Auteur de la présentation
  Crédit de photographie
  Sommaire des articles

Article
  Catégories : [none], compte rendu, entretien
  Titre
  Sous-titres
    Déterminer le nombre de niveaux (max 3?)
  Auteur
  Affiliation
  Date
  Contenu de l'article
    Résumé
    Titres
    Corps du texte
    Citations
    Vidéos
    Images
    Bibliographie
      Titre de la bibliographie
    Références
    Notice biographique
    Fichiers attachés

Nouvelle
  Titre
  Sous-titre
  Date de la nouvelle
  Contenu de la nouvelle
  Fichiers attachés
