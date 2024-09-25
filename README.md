***SMART-ROAD***

> Resume 

*Description pour le dépôt GitHub du projet de simulation d'intersection*

Ce projet est un système de simulation de gestion du trafic visant à contrôler les intersections sans feux de signalisation, en se concentrant sur les véhicules autonomes (AV). Inspiré par un exercice réalisé pendant la piscine Rust, l'objectif est de créer une stratégie de gestion intelligente des intersections pour permettre aux véhicules autonomes de traverser sans collisions tout en minimisant les embouteillages.

**Fonctionnalités principales :**

    * Gestion des véhicules autonomes : Les véhicules doivent respecter un certain itinéraire (tourner à droite, aller tout droit, tourner à gauche) et ajuster leur vitesse pour maintenir une distance de sécurité avec les autres véhicules.
    * Simulation physique : Chaque véhicule suit une logique de distance, vitesse et temps. Les véhicules ralentissent ou accélèrent en fonction de leur environnement.
    * Animation : L'intersection est animée, et les véhicules changent de direction selon leur itinéraire, créant une simulation visuelle réaliste.
    * Commandes interactives : Les véhicules peuvent être générés à partir de différentes directions à l'aide des touches du clavier. Il est également possible de générer des véhicules de manière aléatoire et continue.
    * Statistiques : À la fin de la simulation, des statistiques sont affichées, telles que la vitesse maximale atteinte, le nombre total de véhicules passés, et le temps minimum et maximum pour traverser l'intersection.

**Objectifs du projet :**

Ce projet permet d'explorer plusieurs concepts :

    * Programmation en Rust
    * Utilisation de SDL2 pour la gestion graphique
    * Animation et simulation d'un environnement dynamique
    * Conception d'algorithmes pour la gestion du trafic
    * Mathématiques appliquées aux systèmes de contrôle

Il s'agit d'une introduction pratique à la gestion des intersections pour les véhicules autonomes, en tenant compte des défis liés à la sécurité et à l'efficacité.

> Usage 

```sh
cargo run 
```

> Auteurs

    * Armand Auvray
    * Jean-Frederic Nangy
    * Kevin Batomene

> Licence

MIT License

Copyright (c) 2024 Kevin BATOMENE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.