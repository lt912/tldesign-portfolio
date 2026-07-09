# TL DESIGN · Portfolio

Portfolio de **Lounès Taïbi**, chef de projet créatif. De la stratégie de marque au projet livré.

Site vitrine statique, bilingue FR / EN, présentant 20 études de cas au format Situation → Tâche → Action → Résultat : projets Orange, transformation digitale (SAP), produits SaaS (EstateSync, Cribbz), UX/UI (ReMap, Karl Kani) et créations de marque.

## Aperçu local

Aucune dépendance, aucun build. Servez le dossier avec n'importe quel serveur statique :

```bash
# Python
python3 -m http.server 4173

# ou Ruby
ruby -run -e httpd . -p 4173
```

Puis ouvrez <http://localhost:4173>.

## Structure

- `index.html` — page unique (routeur par hash, i18n FR/EN, données des projets)
- `assets/` — logo, favicon et visuels des projets

## Contact

- Email : lounestaibipro@gmail.com
- LinkedIn : [lounestaibi-pro](https://www.linkedin.com/in/lounestaibi-pro/)
