# Atelier IA — Supports pédagogiques (Atelier 1)

Kit de 5 fiches HTML autonomes destinées aux PME, freelances et indépendants qui
veulent utiliser l'IA générative de façon **utile, efficace et conforme au RGPD**.

Chaque fichier est une page HTML unique (CSS et JS inclus, aucune dépendance
externe) : il suffit de l'ouvrir dans un navigateur, ou de l'imprimer en PDF pour
la distribuer en atelier.

👉 **Point d'entrée : [`index.html`](index.html)** — page d'accueil avec une carte
par fiche et le fil rouge pédagogique.

---

## Les 5 supports

| # | Fichier | Sujet | Type |
|---|---------|-------|------|
| 01 | [`01-Checklist-IA-Saine.html`](01-Checklist-IA-Saine.html) | Les 3 commandements d'un usage IA sans risque | Checklist |
| 02 | [`02-Template-RCTFE.html`](02-Template-RCTFE.html) | La méthode de briefing R.C.T.F.E. | Outil interactif |
| 03 | [`03-Liste-Outils-Liens-2026.html`](03-Liste-Outils-Liens-2026.html) | Panorama 2026 des outils IA & confidentialité | Comparatif |
| 04 | [`04-Top10-Pires-Prompts.html`](04-Top10-Pires-Prompts.html) | Top 10 des pires prompts (avant / après) | Étude de cas |
| 05 | [`05-Mes-3-Prompts-Perso.html`](05-Mes-3-Prompts-Perso.html) | 3 prompts prêts à l'emploi | Copier-coller |

### 01 — Checklist IA Saine 🛡️
Les trois commandements — **Transparence**, **Consentement**, **Sécurité** —
déclinés en « à faire » / « à ne jamais faire ». Inclut la liste des données
**interdites** dans une IA (noms, emails, SIRET, IBAN, données de santé, RH,
contrats) face aux données **autorisées avec prudence**, plus un tableau
« quel outil pour quel cas ». Se termine par un rappel légal RGPD (guide
pédagogique, pas un conseil juridique).

### 02 — Template R.C.T.F.E. 📋
La méthode de briefing en 5 blocs : **Rôle**, **Contexte**, **Tâche**,
**Format**, **Exemples**, avec description, exemples et champ de saisie pour
chacun. Un bouton **« Générer le Prompt Complet »** (JavaScript embarqué)
assemble les cinq champs en un prompt prêt à coller dans l'IA.

Introduit aussi la technique du **Canarie 🐦** : demander à l'IA de commencer
chaque réponse par 🐦. Tant que l'émoji est là, le contexte est vivant ; s'il
disparaît, il faut re-briefer.

### 03 — Panorama 2026 des outils IA 🛠️
Comparatif **ChatGPT / Claude / Gemini / Vibe (Mistral)** sous l'angle
confidentialité et RGPD : matrice de décision rapide (origine, point fort,
données sensibles, note RGPD entreprise, hébergement), puis une fiche détaillée
par outil (forces, politique de données compte perso vs offre pro,
recommandations d'usage, liens officiels). Se termine par une matrice de
décision par profil (PME France, données clients sensibles, parc Google
Workspace, simple test, code propriétaire).

> ⏰ Contenu daté du **25 septembre 2026**. Les modèles, prix et politiques de
> données évoluent vite : à revérifier auprès des éditeurs avant chaque atelier.

### 04 — Top 10 des pires prompts 🚫
Dix erreurs fréquentes de débutant, chacune en format **❌ mauvais prompt →
✓ bon prompt → 📚 leçon** : prompt flou, prompt fleuve, données sensibles en
clair, format non spécifié, absence d'itération, implicite, malhonnêteté,
absence de vérification des faits, demandes impossibles (« connecte-toi à mon
CRM »), acceptation de la première réponse. Conclusion : les **10 règles d'or**.

### 05 — 3 prompts prêts à l'emploi 🚀
Trois prompts complets à copier-coller, avec zones `[CROCHETS]` à remplir :

1. **Reformulation Pro** — transformer un brouillon en 3 versions stylistiques.
2. **Email de relance** — reconquérir un client inactif (version humble / version assertive).
3. **Analyse concurrence** — benchmark rapide de 2-3 concurrents et axes de différenciation.

Chacun est accompagné du « pourquoi ça marche » (lecture R.C.T.F.E.), d'un
conseil d'itération et d'adaptations rapides selon le cas d'usage.

---

## Fil rouge pédagogique

Les cinq documents se lisent dans l'ordre et se répondent :

```
01 Checklist   →  ce qu'on a le droit de faire (cadre RGPD)
02 R.C.T.F.E.  →  comment bien briefer (la méthode)
04 Top 10      →  ce qui casse la méthode (les erreurs)
05 Prompts     →  la méthode appliquée (les modèles prêts)
03 Panorama    →  avec quel outil l'appliquer (le choix technique)
```

Deux notions transverses reviennent partout : la **méthode R.C.T.F.E.** et le
**Canarie 🐦**.

## Utilisation

```bash
# Ouvrir le hub (macOS)
open index.html
```

- **En atelier** : projeter `index.html`, ou imprimer chaque fiche en PDF (`Cmd+P` → Enregistrer en PDF).
- **En autonomie** : les fichiers 02 et 05 sont interactifs (saisie, génération
  de prompt, copie en un clic) et fonctionnent hors ligne.
- **Modification** : tout est dans le fichier (`<style>`, contenu, `<script>`).
  Éditer directement le HTML ; aucun build, aucune installation.

## Avertissement

Ces supports sont **pédagogiques** et ne constituent pas un conseil juridique.
La conformité RGPD d'un usage IA relève de la responsabilité de l'utilisateur,
de son manager ou de son DPO. En cas de doute sur des données personnelles ou
sensibles, consulter le service juridique ou un expert RGPD.
