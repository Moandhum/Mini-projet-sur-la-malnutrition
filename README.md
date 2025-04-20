# Analyse de l'anémie chez les enfants ghanéens

L’anémie touche près de 43 % des enfants dans le monde et jusqu’à 68 % en Afrique, constituant un indicateur majeur de malnutrition infantile. Ce projet vise à identifier les facteurs associés à l’anémie chez les enfants de moins de cinq ans au Ghana.

## 📊 Données

Les données proviennent de l’Enquête Démographique et de Santé du Ghana (2019), incluant des mesures d’hémoglobine et des informations sur l’environnement, la nutrition, l’éducation des mères, et l’exposition au paludisme. 

## 🧪 Méthodologie

1. **Analyses univariées** : Examen individuel de nombreuses variables.
2. **Analyses croisées** : Études des relations entre plusieurs variables.
3. **Analyses des Correspondances Multiples (ACM)** : Exploration approfondie des relations complexes entre les variables.

## ✅ Résultats 

Les facteurs les plus associés à l’anémie sont :
- Les conditions socio-économiques
- Les facteurs géographiques
- Le niveau d'éducation des mères
- Les habitudes alimentaires
- Les conditions sanitaires et environnementales
- La prévalence du paludisme

## ⚙️ Utilisation

1. Cloner ce dépôt :  
   ```bash
   git clone https://github.com/ton-utilisateur/ton-depot.git
   ```
2. Ouvrir et exécuter le fichier `.Rmd` dans RStudio  
3. Exécuter l'analyse en tricotant le document (`Knit`)

### 📦 Librairies R nécessaires

```r
library(ggplot2)
library(dplyr)
library(tidyverse)
library(haven)
library(FactoMineR)
library(factoextra)
library(labelled)
library(openxlsx)
library(gmodels)
library(ade4)
```
