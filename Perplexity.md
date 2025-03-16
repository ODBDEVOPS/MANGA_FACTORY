# MANGA_FACTORY
Bien sûr ! Voici la version mise à jour du prompt sans la colonne "Description" :

---

**Prompt pour Perplexity.ai :**

Je souhaite que vous recherchiez ou interprétiez les informations nécessaires pour remplir un modèle Django représentant un personnage de manga. Voici les champs à remplir, organisés sous forme de tableau. Pour chaque champ, fournissez une estimation ou une interprétation basée sur les informations disponibles. Si certaines informations ne sont pas disponibles, indiquez "N/A".

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `name`                | "Naruto Uzumaki"               |
| `alternate_title`     | "Child of the Prophecy"        |
| `manga`               | "Naruto"                       |
| `Voix_japonaise`      | "Junko Takeuchi"               |
| `voix_française`      | "Céline Melloul"               |
| `race`                | "Humain"                       |
| `Rank`                | "Principal"                    |
| `Carac`               | "Déterminé, courageux"         |
| `Apparence`           | "Cheveux blonds, yeux bleus..."|
| `Age`                 | 17                             |
| `Age_estime`          | "16-18 ans"                    |
| `Anniversaire`        | "10 octobre"                   |
| `Sexe`                | "M"                            |
| `Taille`              | "180 cm"                       |
| `Poids`               | "60 kg"                        |
| `Signe`               | "Balance"                      |
| `strength`            | 85                             |
| `agility`             | 90                             |
| `intelligence`        | 75                             |
| `Type_Magie`          | "Chakra"                       |
| `image`               | "N/A"                          |
| `Role`                | "Protagoniste"                 |
| `Interprétation`      | "Un héros déterminé..."        |
| `Personnalité`        | "Optimiste, têtu"              |
| `Objectifs`           | "Devenir Hokage"               |
| `Inspirations`        | "Son père, Minato"             |
| `Evolution`           | "Passe de cancre à héros..."   |
| `relationships`       | "Ami de Sasuke, rival de Sakura"|
| `abilities`           | "Rasengan, Multi-Clonage"      |
| `is_complete`         | "False"                        |
| `updated_at`          | "2023-10-05"                   |

**Instructions supplémentaires :**
- Si certaines informations ne sont pas disponibles, laissez la cellule vide ou indiquez "N/A".
- Pour les champs comme `strength`, `agility`, et `intelligence`, fournissez une estimation sur une échelle de 0 à 100.
- Pour les relations (`relationships`), listez les personnages clés et la nature de leur relation.
- Pour les capacités (`abilities`), listez les principales compétences ou pouvoirs du personnage.

---

Ce prompt est maintenant plus concis et se concentre uniquement sur les champs nécessaires. Vous pouvez l'utiliser pour guider Perplexity.ai dans la recherche ou l'interprétation des données.

# 2
Voici un prompt structuré pour Perplexity.ai afin de rechercher ou d'interpréter les informations nécessaires pour remplir les modèles Django liés à `MediaAdaptation` et ses classes associées. Le tableau est organisé pour chaque modèle, en omettant les colonnes de description comme demandé.

---

### **Prompt pour Perplexity.ai :**

Je souhaite que vous recherchiez ou interprétiez les informations nécessaires pour remplir les modèles Django suivants liés à une adaptation média (anime, live-action, etc.). Voici les champs à remplir, organisés sous forme de tableau. Pour chaque champ, fournissez une estimation ou une interprétation basée sur les informations disponibles. Si certaines informations ne sont pas disponibles, indiquez "N/A".

---

#### **Modèle : `MediaAdaptation`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `adaptation_type`     | "anime"                        |
| `title`               | "Naruto: Shippuden"            |
| `alternate_title`     | "Naruto Hurricane Chronicles"  |
| `release_date`        | "2007-02-15"                   |
| `studio`              | "Studio Pierrot"               |
| `crunchyroll`         | "https://www.crunchyroll.com/naruto-shippuden" |
| `animze`              | "N/A"                          |
| `teen`                | 13                             |
| `audio`               | "Japonais, Anglais"            |
| `sous_titrage`        | "Français, Espagnol"           |
| `themes`              | "Amitié, Combat, Grandir"      |
| `story_arcs`          | "Arc de la Quête d'Itachi"     |
| `genres`              | "Action, Aventure, Comédie"    |
| `tags`                | "Ninja, Shonen"                |
| `episode`             | 500                            |
| `seasons`             | 21                             |
| `Dernier_Episode`     | "Épisode 500"                  |
| `score`               | 8.5                            |
| `votes`               | 150000                         |
| `views`               | 1000000                        |
| `followers_count`     | 50000                          |
| `popularity_score`    | 95.2                           |
| `average_story`       | 8.7                            |
| `average_animation`   | 8.5                            |
| `average_sound`       | 8.6                            |
| `average_character`   | 9.0                            |
| `total_watch_time`    | 5000000                        |

---

#### **Modèle : `MediaAdaptation_Generique`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `name`                | "Opening 1"                    |
| `mediaAdaptation`     | "Naruto: Shippuden"            |
| `Titre`               | "Hero's Come Back"             |
| `Episodes`            | "1-30"                         |
| `type_Generique`      | "start"                        |
| `Artistes`            | "Nobodyknows+"                 |

---

#### **Modèle : `MediaAdaptation_Saison`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `name`                | "Saison 1"                     |
| `NumSaison`           | 1                              |
| `Episodes`            | 32                             |
| `First_released`      | "2007-02-15"                   |
| `Last_released`       | "2007-09-27"                   |
| `mediaAdaptation`     | "Naruto: Shippuden"            |

---

#### **Modèle : `MediaAdaptation_Arc`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `name`                | "Arc de la Quête d'Itachi"     |
| `NumStoryArc`         | 1                              |
| `mediaAdaptation`     | "Naruto: Shippuden"            |
| `saison`              | "Saison 1"                     |
| `description`         | "Naruto et Sasuke combattent Itachi..." |
| `start_chapter`       | "Chapitre 1"                   |
| `end_chapter`         | "Chapitre 10"                  |
| `main_characters`     | "Naruto Uzumaki, Sasuke Uchiha"|
| `themes`              | "Vengeance, Amitié"            |
| `StoryArc`            | "Arc de la Quête d'Itachi"     |

---

#### **Modèle : `MediaAdaptation_Episode`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `anime`               | "Naruto: Shippuden"            |
| `title`               | "Le Retour de Naruto"          |
| `episode_number`      | 1                              |
| `release_date`        | "2007-02-15"                   |
| `duration`            | 23                             |
| `Directed`            | "Hayato Date"                  |
| `Written`             | "Masashi Kishimoto"            |
| `Storyboarded`        | "N/A"                          |
| `Chief_animation_directed` | "N/A"                     |
| `Original_release_date`| "2007-02-15"                   |
| `description`         | "Naruto revient après 2 ans..."|
| `thumbnail`           | "N/A"                          |
| `views`               | 100000                         |
| `crunchyroll`         | "https://www.crunchyroll.com/naruto-shippuden-episode-1" |
| `Other`               | "N/A"                          |

---

#### **Modèle : `MediaAdaptation_Rating`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `user`                | "Utilisateur123"               |
| `anime`               | "Naruto: Shippuden"            |
| `story_score`         | 9                              |
| `animation_score`     | 8                              |
| `sound_score`         | 9                              |
| `character_score`     | 10                             |
| `comment`             | "Un excellent épisode !"       |

---

#### **Modèle : `MediaAdaptation_Statistic`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `anime`               | "Naruto: Shippuden"            |
| `date`                | "2023-10-05"                   |
| `daily_views`         | 10000                          |
| `watch_time`          | 230000                         |

---

#### **Modèle : `MediaAdaptation_Review`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `anime`               | "Naruto: Shippuden"            |
| `user`                | "Utilisateur123"               |
| `comment`             | "Une adaptation fidèle au manga !" |

---

#### **Modèle : `AdaptationStatistic`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `adaptation`          | "Naruto: Shippuden"            |
| `date`                | "2023-10-05"                   |
| `daily_views`         | 10000                          |
| `daily_followers`     | 500                            |

---

**Instructions supplémentaires :**
- Si certaines informations ne sont pas disponibles, laissez la cellule vide ou indiquez "N/A".
- Pour les champs comme `score`, `votes`, et `views`, fournissez des estimations réalistes.
- Pour les relations (`main_characters`, `themes`, etc.), listez les éléments clés.

---

# 3. 
Voici un prompt structuré pour Perplexity.ai afin de rechercher ou d'interpréter les informations nécessaires pour remplir les modèles Django liés à `Manga`, `MangaStatistic`, `MangaFormat`, et autres classes associées. Le tableau est organisé pour chaque modèle, en omettant les colonnes de description comme demandé.

---

### **Prompt pour Perplexity.ai :**

Je souhaite que vous recherchiez ou interprétiez les informations nécessaires pour remplir les modèles Django suivants liés à un manga. Voici les champs à remplir, organisés sous forme de tableau. Pour chaque champ, fournissez une estimation ou une interprétation basée sur les informations disponibles. Si certaines informations ne sont pas disponibles, indiquez "N/A".

---

#### **Modèle : `MangaStatistic`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `date`                | "2023-10-05"                   |
| `daily_views`         | 10000                          |
| `daily_followers`     | 500                            |

---

#### **Modèle : `Manga`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `title`               | "Naruto"                       |
| `alternate_title`     | "Naruto: Hurricane Chronicles" |
| `start_date`          | "1999-09-21"                   |
| `end_date`            | "2014-11-10"                   |
| `cover_image`         | "N/A"                          |
| `logo_image`          | "N/A"                          |
| `source_wiki`         | "https://en.wikipedia.org/wiki/Naruto" |
| `source_fandom`       | "https://naruto.fandom.com/wiki/Naruto" |
| `followers_count`     | 50000                          |
| `views`               | 1000000                        |
| `StoryArcs_is_full`   | True                           |
| `is_published`        | True                           |
| `is_featured`         | True                           |
| `is_archived`         | False                          |

---

#### **Modèle : `MangaFormat`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `media_type`          | "manga"                        |
| `author`              | "Masashi Kishimoto"            |
| `illustrateur`        | "Masashi Kishimoto"            |
| `editeur`             | "Shueisha"                     |
| `publisher`           | "Viz Media"                    |
| `serialization`       | "Weekly Shōnen Jump"           |
| `demographic`         | "Shōnen"                       |
| `category`            | "Action"                       |
| `genres`              | "Action, Aventure, Comédie"    |
| `tags`                | "Ninja, Shonen"                |
| `start_date`          | "1999-09-21"                   |
| `end_date`            | "2014-11-10"                   |
| `total_volumes`       | 72                             |
| `tirage`              | "1 million"                    |
| `total_tirage`        | 250000000                      |
| `publication_date`    | "1999-09-21"                   |
| `status`              | "completed"                    |
| `cover`               | "N/A"                          |
| `amazon`              | "https://www.amazon.com/Naruto-Vol-1-Masashi-Kishimoto/dp/1569319006" |

---

#### **Modèle : `SlideshowImage`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `image`               | "N/A"                          |
| `image_url`           | "https://example.com/naruto-slide.jpg" |
| `order`               | 1                              |

---

#### **Modèle : `Manga_Review`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `anime`               | "Naruto"                       |
| `user`                | "Utilisateur123"               |
| `comment`             | "Un classique du shonen !"     |

---

#### **Modèle : `Manga_Statistic`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `anime`               | "Naruto"                       |
| `date`                | "2023-10-05"                   |
| `daily_Read`          | 5000                           |
| `Read_time`           | 120000                         |

---

#### **Modèle : `Manga_Rating`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `user`                | "Utilisateur123"               |
| `anime`               | "Naruto"                       |
| `story_score`         | 9                              |
| `Manga_score`         | 8                              |
| `character_score`     | 10                             |
| `comment`             | "Des personnages mémorables !" |

---

#### **Modèle : `Volume`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `title`               | "Volume 1: Uzumaki Naruto"     |
| `Couverture`          | "N/A"                          |
| `volume_number`       | 1                              |
| `ChapterResume`       | "Naruto commence son aventure..." |
| `release_date`        | "2003-03-03"                   |
| `cover_image`         | "N/A"                          |
| `japanese_release_date` | "1999-09-21"                 |
| `japanese_isbn`       | "978-4-08-872840-7"            |
| `japanese_isbn_url`   | "https://example.com"          |
| `french_release_date` | "2003-03-03"                   |
| `french_isbn`         | "978-2-7234-4529-9"            |
| `french_isbn_url`     | "https://example.com"          |
| `category`            | "Action"                       |

---

#### **Modèle : `Chapter`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `volume`              | "Volume 1: Uzumaki Naruto"     |
| `chapter_number`      | 1                              |
| `title`               | "Uzumaki Naruto"               |
| `pages`               | 192                            |

---

#### **Modèle : `Translation`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `manga`               | "Naruto"                       |
| `language`            | "Français"                     |
| `publisher`           | "Kana"                         |
| `release_date`        | "2003-03-03"                   |

---

#### **Modèle : `SpinOff`**

| Champ                 | Exemple de valeur ou estimation |
|-----------------------|---------------------------------|
| `title`               | "Naruto: The Seventh Hokage"   |
| `original_manga`      | "Naruto"                       |
| `author`              | "Masashi Kishimoto"            |
| `release_date`        | "2015-05-01"                   |

---

**Instructions supplémentaires :**
- Si certaines informations ne sont pas disponibles, laissez la cellule vide ou indiquez "N/A".
- Pour les champs comme `story_score`, `Manga_score`, et `character_score`, fournissez des estimations sur une échelle de 1 à 10.
- Pour les relations (`author`, `publisher`, etc.), listez les éléments clés.

---

Ce prompt est conçu pour guider Perplexity.ai dans la recherche ou l'interprétation des données nécessaires pour remplir les modèles Django. Vous pouvez l'adapter en fonction des besoins spécifiques de votre projet.

Ce prompt est conçu pour guider Perplexity.ai dans la recherche ou l'interprétation des données nécessaires pour remplir les modèles Django. Vous pouvez l'adapter en fonction des besoins spécifiques de votre projet.
