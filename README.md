# Boot2Root - École 42

## 🎯 Objectifs

Boot2Root est un projet de cybersécurité conçu pour découvrir les domaines de la sécurité informatique à travers des défis multiples. L'objectif principal est de **devenir utilisateur root** sur un serveur en utilisant différentes méthodes d'exploitation.

## 📋 Description du Projet

Ce projet est un exercice pratique de sécurité informatique où il faut :
- Exploiter les vulnérabilités d'un serveur pour obtenir les privilèges root
- Utiliser des méthodes plus ou moins complexes selon les choix
- Comprendre l'environnement et ne rien sous-estimer
- Découvrir qu'il existe souvent plusieurs chemins pour atteindre l'objectif

## 🔧 Configuration Requise

- **Machine Virtuelle 64 bits**
- **ISO fournie** (ne peut pas être modifiée)
- Environnement de test isolé

Au démarrage de l'ISO, vous verrez ce prompt :
```
____
_______
_____
| _ \
| __ __ | / ____|
| |_) | ___ _ __ _ __ | | ___| (___ ___ ___
| _ < / _ \| '__| '_ \| |/ _ \\___ \ / _ \/ __|
| |_) | (_) | | | | | | | (_) |___) | __/ (__
|____/ \___/|_| |_| |_|_|\___/_____/ \___|\___|
Good luck & Have fun
BornToSecHackMe login: _
```

**Note importante :** Il n'y aura pas d'adresse IP visible, et c'est volontaire...

## 📝 Partie Obligatoire

### Objectif Principal
Devenir utilisateur root (UID = 0) avec un vrai shell fonctionnel où vous pouvez exécuter des commandes comme `whoami`.

### Exigences
- **Minimum 2 méthodes différentes** pour devenir root
- **Write-up complet** pour chaque méthode expliquant toutes les étapes
- Exploitation du **SERVEUR uniquement** (pas de l'ISO directement)

### ⚠️ Restrictions Importantes
- ❌ **Pas de bruteforce** des utilisateurs
- ❌ **Pas d'exploitation directe de l'ISO**
- ❌ **Pas d'exploitation du GRUB** ou du processus de chargement
- ❌ **Pas de modification de l'ISO**

### Note Spéciale - Binary Bomb
Si le mot de passe trouvé est `123456`, le mot de passe à utiliser est `123546`.

## 📁 Structure de Rendu

Votre dossier de rendu doit respecter cette structure :
```
├── writeup1          # Premier write-up (méthode 1)
├── writeup2          # Deuxième write-up (méthode 2)
├── scripts/          # (Optionnel) Scripts utilisés
└── bonus/            # (Optionnel) Méthodes bonus
```

### Contenu des Write-ups
- **Langue :** Anglais
- **Détail :** Chaque étape doit être décrite
- **Clarté :** Vous devez pouvoir expliquer tout le contenu

### Dossier Scripts (Optionnel)
- Scripts utilisés pour l'exploitation
- **Aucun binaire autorisé**
- Vous devez pouvoir expliquer chaque script en détail

## 🏆 Partie Bonus

### Opportunités
- Découvrir d'autres méthodes pour devenir root
- Chaque nouveau write-up fonctionnel = **1-2 points bonus** (sur 5)
- Étudier le serveur de près pour découvrir des solutions fascinantes

### Condition
La partie bonus n'est évaluée **que si la partie obligatoire est PARFAITE**.

## 🛠️ Conseils et Bonnes Pratiques

### Méthodologie
1. **Reconnaissance** : Scanner et analyser le serveur
2. **Énumération** : Identifier les services et vulnérabilités
3. **Exploitation** : Tester différentes méthodes d'attaque
4. **Documentation** : Enregistrer chaque étape pour les write-ups

### Outils Recommandés
- Scanner de ports (nmap)
- Analyseurs de vulnérabilités
- Outils de reverse engineering
- Scripts d'exploitation personnalisés

### Environnement
- Configurez un environnement dédié (VM, Docker, Vagrant)
- Téléchargez les fichiers nécessaires pendant l'évaluation
- Préparez vos scripts pour travailler plus efficacement

## 🤝 Travail en Équipe

Ce projet est conçu pour être fait **en groupe** :
- Échangez pour progresser et comprendre
- Partagez vos découvertes
- Apprenez les uns des autres

## 📚 Évaluation

### Critères
- Capacité à reproduire les exploits
- Compréhension approfondie des méthodes
- Qualité des explications
- Respect des contraintes

### Préparation
- Soyez prêt à prouver vos résultats
- Expliquez chaque étape en détail
- Démontrez votre compréhension des vulnérabilités

## 🎉 Mot de la Fin

**Amusez-vous !** Ce projet est une excellente opportunité d'apprendre la cybersécurité de manière pratique. N'hésitez pas à explorer, tester et découvrir les multiples facettes de la sécurité informatique.

---

*Projet Boot2Root - École 42 - Version 4*