# Natures de Chakra - Doton (Terre)

## Sommaire
1. [Informations Générales sur les Sweps](#informations-generales-sur-les-sweps)
2. [RANG C](#rang-c)
   - [Protection des silex](#protection-des-silex)
   - [Mur de pierre](#mur-de-pierre)
   - [Série de pierre](#serie-de-pierre)
   - [Ecrasement terrestre](#ecrasement-terrestre)
   - [Entrave de pierre](#entrave-de-pierre)
3. [RANG B](#rang-b)
   - [Projection terrestre](#projection-terrestre)
   - [Demi Dôme](#demi-dome)
   - [Motte de pierre](#motte-de-pierre)
   - [Marécage](#marecage)
   - [Vers de terre](#vers-de-terre)
4. [RANG A](#rang-a)
   - [Pilier terrestre](#pilier-terrestre)
   - [Geôle de pierre](#geole-de-pierre)
   - [Empalement](#empalement)
   - [Cercueil de pierre](#cercueil-de-pierre)
   - [Armure de pierre](#armure-de-pierre)
5. [RANG S](#rang-s)
   - [Tremblement de terre](#tremblement-de-terre)
   - [Météores](#meteorites)

---

## Informations Générales sur les Sweps

- **Utilisation des sweps :**  
  Tous les sweps décrits dans ce document se contrôlent principalement via un **clic gauche** (sauf mention contraire). Chaque action peut correspondre à un effet immédiat ou à une durée d'action en fonction de la nature de la technique.

- **Temps d'affichage des éléments visuels :**  
  Tous les effets visuels créés lors de l'utilisation des sweps doivent impérativement être contrôlés et **supprimés après un certain temps** afin de maintenir une expérience de jeu fluide.  
  La durée d'affichage et de vie de chaque élément visuel est à définir, mais elle ne doit pas excéder **10 secondes** pour éviter l'encombrement de la scène et l'impact sur la performance du serveur.

- **Gestion des éléments destructibles :**  
  Pour les techniques générant des objets destructibles (roches, murs de terre, etc.), chaque élément visuel doit etre une **entité** et avoir des **points de vie** qui lui sont attribués. Lorsqu'un élément atteint 0 points de vie, il doit être détruit automatiquement, et ce processus doit être fluide et visible par l'utilisateur.

- **Consommation de chakra :**  
  Chaque technique consomme du **chakra** lors de son activation. La quantité de chakra utilisée dépend de la puissance et de la complexité de la technique. Les techniques puissantes, telles que les attaques de zone (ex : Météores), consommeront plus de chakra. Les utilisateurs doivent gérer leurs ressources pour maximiser leur efficacité dans un combat.

- **Cooldown des techniques :**  
  Un **cooldown** est appliqué après l'utilisation de chaque technique. Cela permet de réguler l'utilisation abusive des techniques puissantes et d'encourager une stratégie réfléchie. La durée du cooldown varie en fonction de la puissance de la technique.

- **Interactions et effet sur l'environnement :**  
  Les techniques Doton peuvent avoir des interactions uniques avec l'environnement, comme déformer le terrain (ex : vers de terre) ou créer des obstacles (ex : mur de boue). Ces interactions doivent être correctement gérées pour que l'expérience de jeu reste immersive et cohérente avec l'univers du jeu.

---

## RANG C

### 1. Protection des silex

**### DESCRIPTION ###**

L’utilisateur forme une multitude de silex qui tournent autour de lui, empêchant son adversaire d’approcher.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 2. Mur de pierre

**### DESCRIPTION ###**

L’utilisateur forme un mur de pierre à 'x' unités de lui.  
Le mur possède des points de vie et est destructible.
Le mur peut etre desactivé via clique molette.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 3. Série de pierre

**### DESCRIPTION ###**

L’utilisateur envoie une serie de 6 pierre en raffale.
Les pierres possèdent des points de vie et sont destructibles.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 4. Écrasement Terrestre

**### DESCRIPTION ###**

L'utilisateur érige un mur de pierre devant lui avant de le faire s’effondrer violemment vers l’avant, écrasant tout sur son passage sous un poids écrasant de roche.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|
---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 5. Entrave de pierre

**### DESCRIPTION ###**

L’utilisateur lance un projectile, si l'adversaire est tocuhé il est immobilisé pendant 'x' temps.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

## RANG B

### 1. Projection Terrestre

**### DESCRIPTION ###**

L’utilisateur attire une multitude de cailloux depuis son dos, les projetant en face de lui.  
Les cailloux possèdent des points de vie et sont destructibles.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 2. Demi Dôme

**### DESCRIPTION ###**

L’utilisateur forme un demi-dôme de terre.  
Le dôme possède des points de vie et est destructible.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 3. Motte de pierre

**### DESCRIPTION ###**

L’utilisateur soulève une parcelle de terre afin de la projeter sur son adversaire.  
La motte possède des points de vie et est destructible.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 4. Marécage

**### DESCRIPTION ###**

L’utilisateur change la surface du sol créant alors une zone marécageuse.  
Ralentit toute personne dans la zone pendant x temps.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 5. Vers de terre

**### DESCRIPTION ###**

Clique gauche : L’utilisateur rentre dans le sol afin de s’y déplacer pendant 'x' secondes.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

## RANG A

### 1. Pillier Terrestre

**### DESCRIPTION ###**

L’utilisateur fait sortir de sous c'est pieds un pillier terrestre et le projetant vers le haut.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 2. Geôle de pierre

**### DESCRIPTION ###**

L’utilisateur forme un dôme de pierre qui l’enveloppe, la geaolle pocede des point de vie et est destructible.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 3. Empalement

**### DESCRIPTION ###**

L’utilisateur fait sortir une multitude de pointes de terre les uns apres les autres de la surface pour empaler son adversaire.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 4. Cercueil de pierre

**### DESCRIPTION ###**

L’utilisateur recouvre son adversaire de plusieurs rochers qui maintiennent en place l'utilisateur.  
Les rochers sont destructibles.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 5. Armure de pierre

**### DESCRIPTION ###**

L’utilisateur crée une armure de pierre sur son corps, augmentant de 'x'% son armure.
L'utilisateur est ralentit, modification la formes phisique de l'utilisateur > a voir avec Tres

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

## RANG S

### 1. Tremblement de terre

**### DESCRIPTION ###**

L’utilisateur fait trembler la terre autour de lui, créant des secousses puissantes qui endommagent tout sur leur passage et
creant des vagues de degats. Tremblement de la visions dans la PVS

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---

### 2. Météores

**### DESCRIPTION ###**

L’utilisateur invoque plusieurs météores venant du ciel pour frapper son adversaire.  
Les météores possèdent des points de vie et sont destructibles.

---

**### DONNÉES ###**

| PROPRIETE             | VALEUR           | ÉCHELLE         |
|-----------------------|------------------|-----------------|
| **DÉGÂTS**            |0|None|
| **CHAKRA**            |0|None|
| **COOLDOWN**          |0|secondes|

---

**### REFS/ILLUSTRATION ###**  
*None*

---
