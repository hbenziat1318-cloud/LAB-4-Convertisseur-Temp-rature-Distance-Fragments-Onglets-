# README - Convertisseur Température & Distance (Fragments + Onglets)

##  Description du projet
Application Android développée en Java permettant de convertir des températures entre Celsius et Fahrenheit, et des distances entre Kilomètres et Miles. L'interface utilise un système d'onglets avec des fragments pour une navigation fluide.

##  Objectifs pédagogiques
- Maîtriser les **Fragments** Android
- Implémenter un système d'**onglets** avec TabLayout et ViewPager2
- Gérer les **interactions utilisateur** (boutons, radio buttons, saisie)
- Intercepter les **événements système** (touche retour)
- Créer des **boîtes de dialogue** de confirmation

##  Technologies utilisées
- **Langage** : Java
- **SDK Minimum** : API 24 (Android 7.0)
- **Architecture** : Fragments + ViewPager2
- **Composants Material Design** : TabLayout, AlertDialog

##  Structure du projet

### Fichiers principaux
```
app/
├── java/com/example/converttabsjava/
│   ├── MainActivity.java          # Activité principale avec onglets
│   ├── ViewPagerAdapter.java      # Adaptateur pour les fragments
│   ├── TempFragment.java          # Fragment conversion température
│   └── DistanceFragment.java      # Fragment conversion distance
│
├── res/layout/
│   ├── activity_main.xml          # Layout principal avec onglets
│   ├── fragment_temp.xml          # Interface conversion température
│   └── fragment_distance.xml      # Interface conversion distance
│
└── manifests/AndroidManifest.xml  # Configuration de l'application
```



##  Fonctionnalités implémentées

###  Onglet Température
- Conversion **Celsius → Fahrenheit** : `(1.8 × val) + 32`
- Conversion **Fahrenheit → Celsius** : `(val − 32) / 1.8`
- Interface : Radio buttons, champ de saisie, bouton de calcul
- Affichage du résultat avec 2 décimales

###  Onglet Distance
- Conversion **Km → Miles** 
- Conversion **Miles → Km** 
- Même structure d'interface que l'onglet température

### Fonctionnalités globales
- **Menu Quitter** : Fermeture de l'application
- **Touche Retour** : Boîte de dialogue de confirmation
- **Gestion des erreurs** : Message Toast si saisie vide


##  Guide d'utilisation

1. **Lancer l'application**
2. **Choisir l'onglet** désiré (Température ou Distance)
3. **Sélectionner le sens** de conversion avec les radio buttons
4. **Saisir la valeur** numérique dans le champ prévu
5. **Cliquer sur "Calculer"** pour obtenir le résultat
6. **Changer d'onglet** pour effectuer d'autres conversions
7. **Quitter** avec la touche retour ou le menu

##  Formules de conversion

### Température
- **Celsius vers Fahrenheit** : `°F = (1.8 × °C) + 32`
- **Fahrenheit vers Celsius** : `°C = (°F - 32) / 1.8`

### Distance
- **Kilomètres vers Miles** : `miles = km × 0.6214`
- **Miles vers Kilomètres** : `km = miles ÷ 0.6214`

### Démonstration



https://github.com/user-attachments/assets/13b7accc-ded3-4cce-9049-c33ddfa52879



## Encadrement & Réalisation
**Encadré par**:Mr.LACHGAR Mohammed
<br>
**Réalisée par**:BENZIAT hana
