# BeautéRdv — Landing de capture (fondatrices)

Page unique, autonome (`index.html`), pour capter la liste d'attente des 50 fondatrices.
Brand rose→prune, responsive, formulaire waitlist, tarifs, témoignages, FAQ.

## Aperçu local
```bash
cd ~/Developer/beauterdv-landing
python3 -m http.server 4321
# ouvrir http://localhost:4321
```

## Brancher le formulaire (2 min)
Le formulaire affiche déjà un message de succès en mode démo. Pour **recevoir vraiment les e-mails** :

**Option A — Formspree (le plus simple)**
1. Crée un formulaire gratuit sur https://formspree.io → copie ton endpoint (`https://formspree.io/f/xxxx`).
2. Dans `index.html`, remplace la ligne `var ENDPOINT = "";` par `var ENDPOINT = "https://formspree.io/f/xxxx";`.

**Option B — Tally**
Remplace les 2 `<form>` par ton embed Tally (https://tally.so).

## Déployer (gratuit)
- **Netlify** : glisse le dossier sur https://app.netlify.com/drop → en ligne en 10 s.
- **Vercel** : `npx vercel` dans le dossier.
- **GitHub Pages** : push le dossier dans un repo, active Pages sur la branche `main`.

Pense à pointer ton domaine (ex. `getbeauterdv.fr`) vers l'hébergeur, et à mettre l'URL **dans la bio Insta/TikTok**.

## Assets
`assets/` = captures de l'app (agenda, clientes, IA). Remplaçables par de nouvelles captures 1242×2688.

## À personnaliser avant lancement
- `ENDPOINT` du formulaire (obligatoire pour capter les e-mails).
- Remplacer les 2 témoignages fictifs par de vrais dès que possible.
- Vérifier le lien App Store (déjà : id6786079483) et la page légale.
