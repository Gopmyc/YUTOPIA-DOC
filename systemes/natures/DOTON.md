# Natures de Chakra - Doton (Terre)

## Sommaire
1. [Informations Générales sur les Sweps](#informations-generales-sur-les-sweps)
2. [RANG C](#rang-c)
   - [Protection des silex](#protection-des-silex)
   - [Mur de boue](#mur-de-boue)
   - [Série de pierre](#serie-de-pierre)
   - [Armure de boue](#armure-de-boue)
   - [Entrave de boue](#entrave-de-boue)
3. [RANG B](#rang-b)
   - [Eboulement de terre](#eboulement-de-terre)
   - [Demi Dôme](#demi-dome)
   - [Motte de terre](#motte-de-terre)
   - [Marécage](#marecage)
   - [Vers de terre](#vers-de-terre)
4. [RANG A](#rang-a)
   - [Pierre écrasante](#pierre-ecrasante)
   - [Geôle de terre](#geole-de-terre)
   - [Empalement](#empalement)
   - [Cercueil de pierre](#cercueil-de-pierre)
   - [Armure de pierre](#armure-de-pierre)
5. [RANG S](#rang-s)
   - [Tremblement de terre](#tremblement-de-terre)
   - [Météores](#meteorites)
   - [Absorption des coups](#absorption-des-coups)

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

### 2. Mur de boue

**### DESCRIPTION ###**

L’utilisateur forme un mur de boue à 'x' unités de lui.  
Le mur possède des points de vie et est destructible.  

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

L’utilisateur forme une série de 6 pierres qui sont propulsées en ligne.  
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

### 4. Armure de boue

**### DESCRIPTION ###**

L’utilisateur crée une armure de boue qui octroie 50% de résistance pendant 'x" secondes.

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

### 5. Entrave de boue

**### DESCRIPTION ###**

L’utilisateur bloque son adversaire avec de la boue pendant 'x' secondes.  
La boue, se contractant, inflige des dommages petit à petit (comme une brûlure).

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

### 1. Eboulement de terre

**### DESCRIPTION ###**

L’utilisateur attire une multitude de cailloux depuis son dos, les projetant en face de lui pendant 'x' secondes.  
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

### 3. Motte de terre

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
Bloque et aspire toute personne pendant x temps.

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

### 1. Pierre écrasante

**### DESCRIPTION ###**

L’utilisateur fait tomber une grande masse de pierre du ciel.  
La masse de pierre possède des points de vie et est destructible.

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

### 2. Geôle de terre

**### DESCRIPTION ###**

L’utilisateur forme un dôme de terre qui l’enveloppe

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

L’utilisateur fait sortir une multitude de pointes de terre de la surface pour empaler son adversaire.

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

L’utilisateur recouvre son adversaire de plusieurs rochers qui le maintiennent en place.  
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

L’utilisateur crée une armure de pierre sur son corps, augmentant de 'x'% ses points de vie.

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

L’utilisateur fait trembler la terre autour de lui, créant des secousses puissantes qui endommagent tout sur leur passage.

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

### 3. Absorption des coups

**### DESCRIPTION ###**

L’utilisateur absorbe une quantité de dégâts, les transformant en chakra et les régénérant petit à petit.  
Les dégâts absorbés ne sont pas directement convertis en chakra, mais sont divisés par 'x' pour obtenir la quantité absorbée.

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
