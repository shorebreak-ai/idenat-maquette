# Brief 04 — Programme & Inscription (id 201 / 198) — REFONTE

> **Conversion du profil B** (prêt à s'engager). Règle centrale : **chaque friction non nécessaire = une inscription perdue.** Lire `00_REGLES_COMMUNES` + `COMPORTEMENTS_PROFILS`. **Zone éditoriale : Zone 2** (grand public). **Périmètre : 201 (Formation) dans le SCOPE ; 198 (Inscription) à valider au SCOPE avant de toucher.**

## Page PROGRAMME (id 201)
*Rôle : répondre à TOUTES les questions avant de demander quoi que ce soit.*

**Bloc « Informations pratiques », visible sans scroll :**
- Durée totale + volume horaire (décomposé présentiel / visio) : **480 h**.
- Format + lieu (Paris) + visio en direct.
- Prochaines dates de session (même approximatives : « automne 2026 »).
- Coût total + modalités de paiement.
- **Financement** : FIF-PL / FAF-PM **si éligibilité confirmée par IDENAT**. **NE PAS afficher « DPC »** tant qu'IDENAT n'est pas confirmé organisme de DPC (ODPC) — publier DPC sans ce statut = promesse trompeuse (L.121-2 / L.4021-1).
- Conditions d'admission (professions, prérequis).

**Puis le syllabus** : modules avec **intitulés** + objectifs en **compétences cliniques** (« à l'issue de ce module, le praticien sait… »). Jamais « les grandes thématiques de la naturothérapie ». Un module à titre clinique (ex. accompagnement de l'oncologie) reste en compétences, sans promesse de soin.

**CTA bas de page** : « Candidater » (principal) + « Recevoir le programme (PDF) » (secondaire).

## Page INSCRIPTION (id 198)
*Rôle : réduire la friction au strict nécessaire.* **À valider au SCOPE avant modification.**

- **CTA principal** : « Candidater / Déposer un dossier » (signale la sélectivité). **Jamais « Nous contacter »** comme accès principal.
- **Formulaire minimal** : nom · profession (liste des professions admises) · email pro · **RPPS** (optionnel, « pour vérifier votre éligibilité ») · message court. Pas de captcha lourd, **pas de pop-up**.
- **Vérifier d'abord quel plugin de formulaire est déjà actif** (Gravity Forms / CF7…). La confirmation auto + relance J+3 dépend de l'existant : **pas de nouveau plugin sans validation QG**.
- **Confirmation immédiate** : récapitulatif + PDF du programme + délai de réponse explicite + **interlocuteur nommé** (prénom + email).
- **Relance J+3** si pas de réponse, signée d'un prénom réel (si l'outil le permet).

## SEO / schema (E-130 lié)
La refonte du syllabus est le bon moment pour vérifier que le **schema Course** (Yoast) reflète le nouveau contenu. Un seul `<h1>` par page, expression clé définie. WebP + lazy-load.

## Conformité
« Tarif anticipé » (jamais « réduit ») · pas de promesse de résultat · sujet = école / soignant · « en appui du suivi médical » · pas de « DPC » sans statut ODPC.

## Dépend d'IDENAT
Volume horaire · dates de session · coût · **statut ODPC** + éligibilité FIF-PL/FAF-PM · voie d'inscription · interlocuteur identifié · plugin de formulaire existant.

## Méthode
Dupliquer **201** (et **198** une fois validée au SCOPE) en brouillons → restructurer → remettre au QG. Snapshot JetBackup avant. Ne pas publier.
