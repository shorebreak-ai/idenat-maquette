# Règles communes — refonte du site idenat.fr (sprint pré-congrès)

> À lire avant chaque brief. On fait une **refonte de l'EXPÉRIENCE** (structure, parcours, hiérarchie, conversion), **pas du style**, et **pas un simple changement de texte**. Fondation comportementale : `COMPORTEMENTS_PROFILS.md`.

## Le cadre
- **Pas de nouveau style à faire valider par IDENAT.** On garde le thème Divi, les couleurs (vert tilleul `#a1bf15`, teal `#0099a1`, charbon), les composants et les images existants. On **réorganise** : ordre des sections, hiérarchie, labels de nav, CTA, parcours.
- **Refonte ≠ relooking et ≠ retouche de texte.** On change la **manière dont chaque page travaille** pour les 4 profils.
- **Méthode : brouillon uniquement.** Dupliquer la page (`./wp.sh duplicate <id>`), restructurer le brouillon, remettre l'id au QG. **Publication = QG.**
- Échéance : avant le congrès (12 juin). Priorité **structure + conformité**.
- **Fait confirmé (affichable) : 480 h de formation.**

## L'angle identitaire (le WHY, à incarner partout sans le nommer en slogan)
IDENAT **modifie le regard clinique du soignant** ; elle n'ajoute pas une pratique de plus. C'est le **second regard clinique** (signature V8, à verrouiller au QG). Chaque page doit le faire ressentir dans sa fonction. Résultat attendu : le visiteur comprend qu'IDENAT change une **façon de lire** le terrain, pas qu'elle vend une méthode. Sans cet angle, le site est conforme mais générique.

## Conformité — s'applique à TOUTES les pages (non négociable)
1. **Le sujet d'une phrase clinique est IDENAT ou le soignant, JAMAIS la discipline.** Bannir « la naturothérapie agit / traite / soigne / corrige / **s'adresse à** ». Écrire « IDENAT forme… », « le praticien… ».
2. **Termes bannis partout** : soigner, guérir, guérison, traiter, traitement (de la maladie), **soins intégratifs**, médecine douce / alternative, **tarif réduit** (→ dire « tarif anticipé »), **patient** au sens médical (→ personne, consultant, apprenant), holistique, bien-être.
3. **« En appui du suivi médical »**, jamais « en complément du traitement ».
4. **Aucun titre de formateur publié sans preuve** (RPPS / ADELI ou diplôme) **+ statut réel**. Un **pharmacien** ne porte pas « Dr » (écrire « D. Nom, pharmacien »).
5. Pas de promesse de résultat. **La preuve précède la promesse.**
6. **Enseigner ≠ exercer (L.4161-1).** L'école enseigne à des soignants ; elle ne se substitue jamais au soin. À tenir surtout sur le corps enseignant et la Master Classe.
7. **Ne pas mobiliser le DPC (L.4021-1)** tant qu'IDENAT n'est pas confirmé ODPC. Publier « DPC » sans ce statut = promesse trompeuse (L.121-2).

## Les 3 zones éditoriales (classer chaque page avant rédaction)
- **Zone 1** — pages réservées aux soignants en formation : marge large ; le vocabulaire clinique est admissible **si une caution (formateur titulaire) est citée** dans le bloc.
- **Zone 2** — grand public (accueil, filiation, programme, inscription : accessibles à tous) : L.121-2 plein ; aucune promesse de soin ; vocabulaire en **compétences**.
- **Zone 3** — Master Classe (non-soignants) : prudence maximale, description en compétences pédagogiques uniquement.

## Positionnement (aligné carto V8) — ne pas sur-revendiquer
IDENAT est la **continuation directe du DUMENAT** (source = Pr Cornillot / DUMENAT / Bobigny, 1982). « Maison mère » = place **à prendre**, pas un titre acquis : on **énonce l'origine, on ne la plaide pas**. Garder l'**interruption de 2013** visible (honnêteté = crédibilité).
**Nom Cornillot** : citation **brève et factuelle** (le fondateur), jamais une figure tutélaire ; le visible s'ancre sur le **DUMENAT / Bobigny**. Fondateurs et sigle = **une seule version sourcée** à verrouiller avec IDENAT avant publication (risque bloquant R7) ; dire « la filière naturothérapie du DUMENAT », pas « le DUMENAT » tout court.

## Données que SEUL IDENAT confirme (ne jamais inventer)
Qualiopi + n° · statut ODPC / financement (FIF-PL, FAF-PM) · dates de session · coût · voie d'inscription · titres + n° d'ordre des formateurs · dates de filiation · développé exact du sigle DUMENAT · archive DUMENAT.
→ Donnée non confirmée = **repère « à confirmer » dans le brouillon, jamais en ligne**.

## Garde-fous techniques (audit E-130) — à respecter sur chaque page
- **Pré-requis avant toute session : snapshot JetBackup confirmé** (sinon, arrêt).
- **Ne jamais dégrader** : Qualys SSL **A**, PageSpeed SEO **100**, ni les **11 URLs canoniques** indexées (pas de changement de slug ; une nouvelle page publiée = nouvelle URL à valider).
- Chaque image ajoutée/modifiée → **WebP + lazy-load** ; vérifier PageSpeed mobile après (cible ≥ 85, LCP < 2,5 s).
- **Hors périmètre de ces briefs** (chantiers parallèles, non Divi, à ne pas oublier) : en-têtes HTTP de sécurité (M1, site en F Observatory tant que non faits), DMARC `p=quarantine` (M2), encart événementiel SYNAMIEF sur la home (M11).
- **Zones à ne jamais toucher** : préfixe BDD, salts/`wp-config`, logo Yoast, schema, code Divi parent. Pas de nouveau plugin sans validation QG.

## Le fil rouge (ordre de captation)
Un médecin comprend en ~30 s : **(1)** qui est IDENAT (la **continuation du DUMENAT**, 1982) · **(2)** ce qu'est la naturothérapie (≠ naturopathie) · **(3)** ce que ça lui apporte (le second regard clinique) · **(4)** comment s'inscrire.

## Les pages (priorité congrès, par impact conversion)
1. **Accueil** (id 31) — refonte · brief 01 *(dans le SCOPE)*
2. **Corps enseignant** (id 1578) — refonte · brief 03 *(dans le SCOPE)*
3. **Programme & Inscription** (id 201 / 198) — refonte · brief 04 *(201 = Formation, dans le SCOPE ; 198 Inscription à valider au SCOPE)*
4. **Filiation** — créer (base 1732) · brief 02 *(hors SCOPE E-130 actuel : brouillon non publié tant que le SCOPE n'est pas élargi)*
