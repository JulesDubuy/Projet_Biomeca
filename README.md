# 🏀 Projet Biomécanique — Analyse du tir en basket-ball

Analyse biomécanique du geste de tir en basket-ball (Jump Shot et Lancer Franc) à partir de données de capture de mouvement (`.c3d`).

---

## 📁 Structure du projet

```
Groupe_3/
│
├── Projet.ipynb          ← Notebook principal (analyse des données)
├── liste_marker.txt      ← Liste des marqueurs corporels utilisés
│
├── Jump_Shot/            ← Données de capture de mouvement — Tir en extension
│   ├── Tirext1.c3d
│   ├── Tirext2.c3d
│   ├── Tirext3.c3d
│   ├── Tirext4.c3d
│   └── Tirext5.c3d
│
├── LF/                   ← Données de capture de mouvement — Lancer Franc
│   ├── Lancer1.c3d
│   ├── Lancer2.c3d
│   ├── Lancer3.c3d
│   ├── Lancer4.c3d
│   └── Lancer5.c3d
│
├── AIM_REF.qam           ← Fichier de référence AIM
└── ANAT_REF.qtm          ← Fichier de référence anatomique
```

---

## 🛠️ Prérequis — Ce qu'il faut installer


### 1. Les bibliothèques Python nécessaires

Ouvre un terminal (invite de commandes ou PowerShell) et tape :

```bash
pip install jupyter numpy matplotlib ezc3d
```

> 💡 **C'est quoi `pip` ?** C'est le gestionnaire de paquets de Python, il permet d'installer des bibliothèques (comme des extensions).

### 2. Git (pour récupérer le projet)

Télécharge et installe Git depuis :
👉 https://git-scm.com/downloads

Laisse toutes les options par défaut pendant l'installation.

---

## 🚀 Récupérer le projet depuis GitHub 

### Étape 1 — Va dans le dossier où tu veux mettre le projet

Par exemple, pour aller dans ton dossier `Documents` :

```bash
cd Documents
```

### Étape 2 — Clone le projet

```bash
git clone https://github.com/JulesDubuy/Projet_Biomeca.git
```

Cette commande télécharge tout le projet dans un nouveau dossier `Projet_Biomeca`.

### Étape 3 — Entre dans le dossier du projet

```bash
cd Projet_Biomeca
```

---

## ▶️ Lancer le notebook

Dans le terminal, depuis le dossier du projet, tape :

```bash
jupyter notebook
```

Une page va s'ouvrir automatiquement dans ton navigateur. Clique sur **`Projet.ipynb`** pour ouvrir le notebook.

Pour exécuter le code, clique sur une cellule puis appuie sur **`Shift + Entrée`**.

---

## 💾 Contribuer au projet — Envoyer ses modifications sur GitHub

Si tu fais des modifications et que tu veux les partager avec le reste du groupe, voici la procédure complète.

> **Vocabulaire Git :**
> - **commit** = enregistrer une "photo" de tes modifications
> - **push** = envoyer tes modifications sur GitHub
> - **pull** = récupérer les dernières modifications de tes collègues

### Étape 1 — Voir ce que tu as modifié

```bash
git status
```

Cette commande te montre les fichiers que tu as modifiés (en rouge = non enregistré).

### Étape 2 — Ajouter tes fichiers modifiés

Pour ajouter **tous** les fichiers modifiés :

```bash
git add .
```

Ou pour ajouter un fichier en particulier :

```bash
git add nom_du_fichier
```

### Étape 3 — Créer un commit (enregistrer tes modifications)

```bash
git commit -m "Description de ce que tu as fait"
```

> Exemple : `git commit -m "Ajout de l'analyse du lancer franc"`

### Étape 4 — Récupérer les modifications de tes collègues (bonne pratique !)

Avant d'envoyer, toujours récupérer les dernières modifications pour éviter les conflits :

```bash
git pull origin main
```

### Étape 5 — Envoyer tes modifications sur GitHub

```bash
git push origin main
```

Git va te demander ton **nom d'utilisateur GitHub** et ton **mot de passe** (ou un token d'accès). Demande-le à Jules si tu n'en as pas.

---

## 🔄 Récupérer les mises à jour du projet

Si quelqu'un du groupe a envoyé de nouvelles modifications, récupère-les avec :

```bash
git pull origin main
```

---

## ❓ Problèmes fréquents

| Problème | Solution |
|---|---|
| `pip` n'est pas reconnu | Relance le terminal après avoir installé Python, ou réinstalle Python en cochant "Add to PATH" |
| `git` n'est pas reconnu | Relance le terminal après avoir installé Git |
| `jupyter` ne s'ouvre pas | Tape `pip install notebook` puis réessaie |
| Erreur lors du `git push` | Assure-toi d'avoir les droits sur le dépôt (contacte Jules) |
| Conflit lors du `git pull` | Ne panique pas — contacte un membre du groupe pour résoudre ensemble |

---

## 👥 Groupe 3

Projet réalisé dans le cadre du cours de Biomécanique — Master 1.

> Pour toute question sur le dépôt GitHub, contacte **Jules Dubuy** (jules.dubuy1810@gmail.com).
