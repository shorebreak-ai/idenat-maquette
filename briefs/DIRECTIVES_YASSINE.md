# Directives — sprint congrès idenat.fr (Yassine)

> Doc de cadrage pour exécuter le site avant le **12 juin**. Tout l'essentiel est ici ; le détail page par page est dans les autres briefs (même dossier). **Rien ne se publie sans le QG.**

---

## ⚑ À MÉMORISER — ton Claude enregistre ces faits *(ils ne doivent jamais dériver)*

> Demande à ton Claude de **sauvegarder ce bloc en mémoire** au démarrage. C'est le socle non négociable.

- **RÈGLE D'OR CONGRÈS : on fait du premium AVEC les codes actuels d'IDENAT. On ne change NI la palette, NI le logo, NI le thème Divi.** La nouvelle direction artistique (ivoire/bleu académique) = la **refonte d'APRÈS le congrès**, jamais maintenant. Le « cheap » à corriger ne vient pas des couleurs, il vient du **slider, de la bande verte vide, des icônes, de l'absence de vraies images, du vert fluo en aplats**.
- **Codes IDENAT** : vert tilleul `#a1bf15`, teal `#0099a1`, charbon, logo existant, thème Divi. Premium = les utiliser avec **discipline** : teal + charbon + blanc en avant, **vert en accent** (filet, logo), beaucoup de blanc, jamais d'aplats fluo.
- **Positionnement** : IDENAT = **continuation directe du DUMENAT** (Faculté de médecine de Bobigny, **1982**), **réservé aux soignants diplômés d'État**. Naturothérapie ≠ naturopathie. On dit « continuation », **jamais « la source »**.
- **H1 home (tranché)** : « La naturothérapie clinique, enseignée aux soignants depuis 1982 ». **Jamais publié sans 1982 / DUMENAT à côté.**
- **Volume horaire** : **480 h** (confirmé, affichable).
- **CONFORMITÉ (non négociable, risque juridique réel)** : le sujet d'une phrase clinique est **IDENAT ou le soignant, JAMAIS la discipline**. **Termes bannis** : soigner, guérir, guérison, traiter, **soins intégratifs**, médecine douce, **tarif réduit**, **patient** (au sens médical → personne), holistique, bien-être. Toujours « **en appui du suivi médical** ». **Enseigner ≠ exercer** (L.4161-1). **Aucun titre de formateur** publié sans preuve (RPPS / ADELI ou diplôme + statut) ; un pharmacien ne porte pas « Dr ». **Ne pas afficher « DPC »** sans statut ODPC.
- **Les 7 vrais formateurs** : **Alain · Jencikova · Erika · Sabrina · Philippe · Martine · Rodolphe**. La liste actuelle du site (10 noms) **est fausse**. Page Équipe **GELÉE** jusqu'aux fiches (titre exact + module + photo + consentement RGPD).
- **Méthode WP = BROUILLON-ONLY** : `./wp.sh duplicate <id>` → travailler le brouillon → remettre l'id au QG. **Tu ne publies JAMAIS.** Publication, mise en ligne, changement d'URL = QG uniquement. Snapshot JetBackup avant toute session.
- **Journal des modifs** : toute modif (brouillon ET publiée) se consigne (avant → après) dans `JOURNAL_MODIFS_SITE.md`.
- **Ne jamais dégrader** : SSL A, PageSpeed SEO 100, les 11 URLs canoniques (pas de changement de slug). Images en **WebP + lazy-load**.

---

## 1. La règle d'or, développée
Premium **sans sortir des codes IDENAT**. On corrige le cheap dans **leurs** couleurs : slider → hero fixe, bande verte vide → supprimée, icônes → vraies images, vert fluo en aplats → vert en accent + blanc + teal. On ne réinvente pas l'identité (ça, c'est la refonte d'après).

## 2. Le hero de la home *(priorité n°1 — perception)*
- **Hero fixe** (pas slider), sur une **vraie image forte** : archive DUMENAT (amphi Bobigny / 1982) ou visuel clinique-académique sobre. **Pas la fleur floue.** Overlay **charbon** pour la lisibilité.
- **Teal + charbon + blanc** portent le hero ; vert tilleul en **accent** (filet, logo).
- **1982 en monument** typographique · **H1** « La naturothérapie clinique, enseignée aux soignants depuis 1982 » · sous-titre « Réservé aux professionnels de santé diplômés d'État » · **un seul CTA : « Candidater »**.
- **Supprimer la bande verte vide** au-dessus du hero.
- *Image en attente d'IDENAT → placeholder sobre (aplat charbon/teal), jamais une image stock de fleur.*

## 3. Les 3 piliers — la barre
1. **Perception** — en 2 s, « académie clinique », pas « wellness ». Test : confondable avec une école de naturo lambda ? → recalé.
2. **Sécurité juridique** — un confrère ne trouve aucune faille. **Binaire** : une seule page oubliée (un « guérison », un titre non prouvé) = tout tombe.
3. **Facilité d'inscription** — « Candidater » à **≤ 2 clics** du hero, formulaire minimal **sans bug**, confirmation immédiate. Pas de « Nous contacter » comme accès principal.

## 4. TOUTES les pages — tu fais les 12
Le site = 12 URLs. Tu les prépares **toutes** en brouillon, de bout en bout. Direction en une ligne ; le détail est dans les briefs (diffs + statut fait / reste).
1. **Accueil (1727)** — hero (cf. §2) · bande de légitimité (480 h · 1982) · icônes → images · encart SYNAMIEF.
2. **Définir la naturothérapie (1756)** — définition OK ; corriger l'historique (fondateurs sourcés · « fermé en 2013 par la faculté » · adresse) · icône → image.
3. **Filiation (1732)** — construire la page (origine sourcée) ; **prête, mais sa mise en ligne = décision QG** (données à verrouiller).
4. **La formation, 3 ans (1757)** — « élargir le regard du soignant » en tête · coquille « Un nouvelle approche ».
5. **Programme (1752)** — **syllabus en compétences** (le gros morceau) · CTA « Recevoir le programme (PDF) ».
6. **Inscription (1754)** — confirmation enrichie + interlocuteur · formulaire sans bug · trancher « Bac +5 scientifique ».
7. **Corps enseignant (1750)** — **reconstruire** avec les **7 vrais formateurs** (placeholders jusqu'aux fiches).
8. **Master Classe (1394)** — à **retirer** : préparer la redirection 301 (le retrait du live, cf. §5).
9. **Blog — articles 1235 / 1145** — à **retirer** : préparer la 301. Listing (1081) masqué de la nav.
10. **Contact (211)** — interlocuteur nommé · mention RGPD · pas de claim clinique.
11. **Mentions légales + confidentialité (209)** — clarifier éditeur / A2N · RGPD des nouveaux formulaires · pas de « DPC ».

Partout : **icônes → vraies images**, codes IDENAT tenus, conformité, WebP + lazy-load.

## 5. Tu fais tout — 2 dépendances externes à gérer *(pas des exceptions)*
1. **Les données qu'IDENAT seul détient** : titres + fiches des 7 formateurs · image d'archive DUMENAT · interlocuteur / coût / dates d'inscription. Personne dans l'équipe ne peut les inventer (risque usurpation de titre). → **Tu construis la page complète avec des placeholders sobres + repères « à confirmer », et tu intègres dès réception.** Tu ne te bloques jamais dessus.
2. **La mise en ligne et le retrait** : aujourd'hui `wp.sh` refuse d'écrire sur une page publiée (garde-fou QG). Tu **prépares tout** (brouillons + redirections 301) ; le passage en ligne / le retrait se fait soit par le QG en un clic, soit **par toi si tu reçois les droits de publication**.

## 6. Quand c'est prêt
Tu remets les **id de brouillons** au QG avec une note de ce qui a changé (pour le journal). Le QG inspecte le **rendu réel** (desktop + mobile), recadre si besoin, puis publie.
