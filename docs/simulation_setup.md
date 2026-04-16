# Ansys HFSS Simulation Setup

Ce document détaille la configuration de base utilisée dans **Ansys Electronics Desktop (HFSS)** pour générer les fichiers `.s1p` de ce dataset.

## Configuration de la simulation
* **Logiciel / Solveur :** Ansys HFSS
* **Impédance de référence ($Z_0$) :** 50 Ohms
* **Paramètre extrait :** Coefficient de réflexion ($S_{11}$) à 1 port.

## Méthode d'extraction
Les données fournies sont les mesures S11 brutes. Le lien théorique entre ce paramètre mesuré et l'impédance d'entrée $Z_{in}$ du matériau est :

$$S_{11} = \frac{Z_{in} - 50}{Z_{in} + 50}$$

L'objectif de ce dataset est d'utiliser ces données pour retrouver la permittivité complexe ($\epsilon^*$) et la tangente de perte ($\tan \delta$) du matériau simulé.

*(Note : Les dimensions exactes de l'échantillon et les conditions aux limites du modèle 3D dépendent du fichier projet Ansys d'origine).*
