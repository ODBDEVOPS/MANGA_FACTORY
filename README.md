# MANGA_FACTORY
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

Ce prompt est conçu pour guider Perplexity.ai dans la recherche ou l'interprétation des données nécessaires pour remplir les modèles Django. Vous pouvez l'adapter en fonction des besoins spécifiques de votre projet.
