# Comparaison entre **npm**, **yarn**, et **pnpm** (avec installation via npm)

## 1. **npm (Node Package Manager)**  
- **Description** : Le gestionnaire de paquets inclus avec Node.js.  
- **Installation** : Aucune installation supplémentaire n'est nécessaire ; npm est déjà inclus avec Node.js.  
- **Commandes de base** :  
  - `npm install` : Installe toutes les dépendances d’un projet.  
  - `npm install <nom-du-paquet>` : Ajoute une dépendance spécifique.

---

## 2. **yarn**  
- **Description** : Une alternative rapide et stable à npm, développée par Facebook.  
- **Installation via npm** :  
  ```bash
  npm install -g yarn
  ```
  *(L'option `-g` signifie que l'installation est globale et que tu pourras utiliser Yarn partout.)*  
- **Commandes de base** :  
  - `yarn install` : Installe toutes les dépendances.  
  - `yarn add <nom-du-paquet>` : Ajoute une dépendance spécifique.

---

## 3. **pnpm (Performant npm)**  
- **Description** : Une version améliorée et plus performante de npm, qui économise de l’espace disque.  
- **Installation via npm** :  
  ```bash
  npm install -g pnpm
  ```
- **Commandes de base** :  
  - `pnpm install` : Installe toutes les dépendances.  
  - `pnpm add <nom-du-paquet>` : Ajoute une dépendance spécifique.

---

## Résumé des installations :  
1. **npm** : Pas besoin d’installation, livré avec Node.js.  
2. **yarn** : Installe avec `npm install -g yarn`.  
3. **pnpm** : Installe avec `npm install -g pnpm`. 
