# Installer Atelier Bouclé sur ton téléphone

Tout se fait depuis un navigateur : aucun logiciel ni IDE à installer.

## 1. Mettre l'appli en ligne (une seule fois, gratuit, ~10 min)

1. Crée un compte sur **github.com**.
2. Bouton **+** en haut à droite → **New repository** → nom : `atelier` → **Public** → **Create repository**.
3. Clique sur **uploading an existing file**, puis glisse les fichiers de ce dossier (pas le dossier lui-même) → **Commit changes**.
4. Va dans **Settings → Pages**. Sous *Branch*, choisis `main` et `/ (root)` → **Save**.
5. Après 1 à 2 minutes, ton appli est en ligne à l'adresse `https://TON-PSEUDO.github.io/atelier/`.

Le code est public, mais **tes photos ne sont jamais envoyées** : elles restent uniquement dans la mémoire de ton téléphone.

## 2. Installer l'appli sur le téléphone

- **Android (Chrome)** : ouvre l'adresse → menu **⋮** → **Installer l'application**.
- **iPhone (Safari)** : ouvre l'adresse → bouton **Partager** → **Sur l'écran d'accueil**.
- **PC (Chrome ou Edge)** : ouvre l'adresse → icône d'installation dans la barre d'adresse.

L'appli s'ouvre ensuite en plein écran, a accès à l'appareil photo et fonctionne hors ligne.

## 3. Installer l'IA locale

Dans l'appli : **Moi → IA locale → Installer**.

- Le téléchargement fait environ 130 Mo, une seule fois. Fais-le en Wi-Fi.
- Ensuite, tout se calcule sur ton appareil, même sans internet.

L'IA utilise deux modèles open source :
- **RMBG-1.4** retire le fond des photos, même sur un lit ou un parquet.
- **CLIP** reconnaît le type de pièce, propose les moods et permet la recherche par description (« jupe plissée noire »).

## 4. Importer ta garde-robe (200 pièces et plus)

1. Touche **+ → Galerie** et sélectionne jusqu'à 100 photos d'un coup.
2. L'IA détoure, classe et range chaque pièce. Compte quelques secondes par photo.
3. Ouvre l'onglet **À vérifier** du dressing : corrige le type si besoin, puis touche **Valider**.

Conseils photo :
- une pièce par photo ;
- à la lumière du jour ;
- la pièce entière dans le cadre.

## Bon à savoir

- **Chaque appareil a sa propre garde-robe.** Pour passer du PC au téléphone, utilise **Moi → Exporter**, puis **Importer** sur l'autre appareil.
- **Fais un export de temps en temps** : c'est ta sauvegarde si tu changes ou perds ton téléphone.
- **Sur iPhone**, ouvre toujours l'appli depuis son icône, pas depuis Safari. Les données d'un site non installé peuvent être effacées après quelques semaines sans visite.
- **Téléphone ancien ou lent** : fais le gros import sur ton PC, puis transfère avec Exporter / Importer.
- **Mettre à jour l'appli** : sur GitHub, **Add file → Upload files**, et remplace `index.html`. Tes données ne sont pas touchées.
- **Avoir une vraie appli Android (.apk)** : va sur **pwabuilder.com**, colle ton adresse, puis **Package for stores → Android**.
