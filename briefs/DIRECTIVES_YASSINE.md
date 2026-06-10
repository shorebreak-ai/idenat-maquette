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

## 4. Le reste, page par page
Suivre les briefs (diffs + statut **fait / reste**). Le gros qui reste, par ordre d'impact :
- **Hero accueil** (perception) · **icônes → vraies images** partout.
- **Programme (1752)** : reformuler le **syllabus en compétences** (« à l'issue de ce module, le praticien sait… »).
- **Naturothérapie (1756)** : corriger l'historique (fondateurs sourcés · « fermé en 2013 par la faculté » · adresse).
- **Formation (1757)** : remonter « élargir le regard du soignant » en tête · coquille « Un nouvelle approche ».

## 5. Ce qui n'est PAS à toi *(ne pas t'y bloquer)*
- **Dépublier** Master Classe (1394) + blog (1235 / 1145) : action sur le live = **QG** (ton `wp.sh` la refuse).
- **Image d'archive DUMENAT · 7 fiches formateurs · données d'inscription** (interlocuteur, email, coût, dates) : **IDENAT**. En attendant, placeholders sobres + repères « à confirmer », jamais en ligne.
- **Publication** : QG.

## 6. Quand c'est prêt
Tu remets les **id de brouillons** au QG avec une note de ce qui a changé (pour le journal). Le QG inspecte le **rendu réel** (desktop + mobile), recadre si besoin, puis publie.
