# Règles communes — refonte du site idenat.fr (sprint pré-congrès)

> À lire avant chaque brief. On fait une **refonte de l'EXPÉRIENCE** (structure, parcours, hiérarchie, conversion), **pas du style**, et **pas un simple changement de texte**. Fondation comportementale : `COMPORTEMENTS_PROFILS.md`.

## Le cadre
- **Pas de nouveau style à faire valider par IDENAT.** On garde le thème Divi, les couleurs (vert tilleul `#a1bf15`, teal `#0099a1`, charbon), les composants et les images existants. On **réorganise** : ordre des sections, hiérarchie, labels de nav, CTA, parcours.
- **Refonte ≠ relooking et ≠ retouche de texte.** On change la **manière dont chaque page travaille** pour les 4 profils.
- **Méthode : brouillon uniquement.** Dupliquer la page (`./wp.sh duplicate <id>`), restructurer le brouillon, remettre l'id au QG. **Publication = QG.** (voir `kit_claude_wordpress/GUIDE_CLAUDE_WORDPRESS.md`)
- Échéance : avant le congrès (12 juin). Priorité **structure + conformité**. Aucun chantier technique lourd.

## Conformité — s'applique à TOUTES les pages (non négociable)
1. **Le sujet d'une phrase clinique est IDENAT ou le soignant, JAMAIS la discipline.** Bannir « la naturothérapie agit / traite / soigne / corrige ».
2. **Termes bannis partout** : soigner, guérir, guérison, traiter, traitement (de la maladie), **soins intégratifs**, médecine douce / alternative, **tarif réduit**.
3. **« En appui du suivi médical »**, jamais « en complément du traitement ».
4. **Aucun titre de formateur publié sans preuve** (RPPS / ADELI ou diplôme) **+ statut réel**.
5. Pas de promesse de résultat. **La preuve précède la promesse.**

## Données que SEUL IDENAT confirme (ne jamais inventer)
Volume horaire (432 h ?) · Qualiopi + n° · financement (DPC/FIF-PL/FAF-PM) · dates de session · coût · voie d'inscription · titres + n° d'ordre des formateurs · dates de filiation · archive DUMENAT.
→ Donnée non confirmée = **repère « à confirmer » dans le brouillon, jamais en ligne**.

## Le fil rouge (ordre de captation)
Un médecin comprend en ~30 s : **(1)** qui est IDENAT (la source, filiation DUMENAT 1982) · **(2)** ce qu'est la naturothérapie (≠ naturopathie) · **(3)** ce que ça lui apporte · **(4)** comment s'inscrire.

## Les pages (priorité congrès, par impact conversion)
1. **Accueil** (id 31) — refonte · brief 01
2. **Corps enseignant** (id 1578) — refonte · brief 03 *(conversion profil C / prescripteur)*
3. **Programme & Inscription** (id 201 / 198) — refonte · brief 04 *(conversion profil B)*
4. **Filiation** — créer (base 1732) · brief 02 *(crédibilité profil C, rétention A)*
