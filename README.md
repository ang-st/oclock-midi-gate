# MIDI Clock Multisortie avec 4 CV Gates, 4 MIDI DIN et 4 USB
![image](https://github.com/user-attachments/assets/7775f123-70a8-401c-ad07-2ef79dc74737)



## Description

Ce projet est un contrôleur MIDI  capable de générer une horloge MIDI stable et synchronisée avec plusieurs sorties, y compris 4 sorties CV gate, 4 sorties MIDI DIN, et 4 connexions MIDI USB. Le projet est basé sur une carte **Teensy 4.1** qui offre une puissance de calcul suffisante pour gérer simultanément plusieurs flux MIDI tout en générant des signaux CV précis.

## Fonctionnalités

- **4 sorties CV Gate** : Pour contrôler des modules analogiques via des tensions variables.
- **4 sorties MIDI DIN** : Pour la synchronisation de périphériques MIDI traditionnels.
- **4 ports USB MIDI** : Pour contrôler et synchroniser des appareils MIDI USB modernes.
- **Interface utilisateur intuitive** : Comprend un écran pour afficher les BPM, des boutons pour démarrer/arrêter la synchronisation, et des contrôles pour ajuster le tempo.
- **Configuration flexible** : Permet de configurer chaque sortie individuellement via une interface simple.

## Matériel requis

- **Teensy 4.1** : Carte microcontrôleur principale.
- **DAC MCP4728** (ou équivalent) : Pour les sorties CV.
- **Connecteurs MIDI DIN** : Pour les sorties MIDI.
- **Hub USB** : Pour connecter plusieurs périphériques MIDI USB.
- **Composants passifs** : Résistances, condensateurs, optocoupleurs (pour les sorties MIDI).
- **Écran OLED/LCD** : Pour l'affichage des informations.
- **Boutons et potentiomètres** : Pour le contrôle de l'interface utilisateur.
- **Boîtier** : Pour l'intégration des composants.

## Dépendances logicielles

- **Arduino IDE** : Pour programmer le Teensy.
- **Teensyduino** : Extension pour l'IDE Arduino afin de programmer les cartes Teensy.
- **Bibliothèque MIDI** : Pour la gestion des messages MIDI (disponible dans l'IDE Arduino).
- **Bibliothèque DAC** : Pour le contrôle des sorties CV (selon le DAC utilisé).

## Installation

1. **Cloner ce dépôt** :
   ```bash
   git clone https://github.com/votre-utilisateur/midi-clock-multisortie.git
   cd midi-clock-multisortie
