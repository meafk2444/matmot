# 🦒 La Girafe Disco

Un petit site rigolo : une girafe animée qui danse en boucle, et qui déclenche
une action aléatoire différente (confettis, rotation, flip, moonwalk, pluie
d'emojis, flash...) à chaque clic.

## Fichiers

- `index.html` — la page (HTML + CSS + JS, tout est dedans, aucune dépendance)
- `assets/giraffe.png` — la girafe détourée (fond transparent)

## Publier le site sur GitHub Pages (gratuit)

1. Va sur [github.com/new](https://github.com/new) et crée un nouveau dépôt,
   par exemple `girafe-disco`. Laisse-le public.
2. Sur ta machine, ouvre un terminal dans ce dossier (`site/`) et tape :

   ```bash
   git init
   git add .
   git commit -m "Girafe disco 🦒"
   git branch -M main
   git remote add origin https://github.com/TON-PSEUDO/girafe-disco.git
   git push -u origin main
   ```

   (Remplace `TON-PSEUDO` par ton nom d'utilisateur GitHub.)

3. Sur GitHub, va dans **Settings** → **Pages**.
4. Dans "Build and deployment", choisis la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Après ~1 minute, ton site sera en ligne à l'adresse :

   ```
   https://meafk2444.github.io/matmot/
   ```

C'est tout — pas de serveur, pas de build, ça marche directement.

## Astuce

Si tu préfères ne pas utiliser le terminal, tu peux aussi juste glisser les
fichiers `index.html` et le dossier `assets/` directement dans l'interface
GitHub ("Add file" → "Upload files") sur la page du nouveau dépôt.
