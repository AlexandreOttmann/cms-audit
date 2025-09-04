# Recommandation CMS pour Odysway

## Résumé
Nous souhaitions recommander un CMS moderne, effectuer un comparatif pertinent entre les principaux CMS ressortant sur le marché actuellement.

## PainPoints Actuels 
- Publication lente (constructions de sites statiques, déploiements longs)
- Rédaction en Markdown, trop technique, trop compliqué à prendre en main
- Contenu riche limité (difficile d'intégrer des galeries, cartes ou blocs complexes), pas de champs de texte riche (avec de l'édition de texte)
- Aucun moyen facile de lier le contenu (ex : Voyage ↔ Destination ↔ Thématique)
- Pas de log d'erreur convenable (le site peut planter sans message, warning préalable)

Ce dont vous avez besoin à la place : aperçu/publication instantanés, texte riche avec médias/blocs intégrés, interface d'édition conviviale, et relations de première classe entre contenus.
CMS AUDITÉS ET TESTÉS : [Sanity](https://www.sanity.io/), [Storyblok](https://www.storyblok.com/), [Strapi](https://strapi.io/), [Prismic](https://prismic.io/), [Directus](https://directus.io/)

Vidéo de présentation de l'audit 🚀: [Lien 1](https://www.loom.com/share/d2bf360930624131a3bb8e7db5d8605b?sid=5ff60fd0-e492-4a6d-b28f-fda1799c3c9f)

---

## TL;DR 
- Vous souhaitez un CMS moderne avec publication rapide, contenu riche (images, blocs, relations), et une expérience d'édition que les non‑développeurs peuvent utiliser confortablement.
- Deux meilleures options globales : Storyblok (le plus visuel, le plus facile pour les éditeurs) et Sanity (le plus flexible et évolutif pour les développeurs et équipes d'Odysway, moins cher, moins complexe).
- Classement mis à jour (basé sur vos besoins et budget) :
  1) Sanity, 2) StoryBlok, 3) Strapi, 4) Prismic, 5) Directus

### Pourquoi ces trois ?
- Storyblok : édition vraiment visuelle (ce‑que‑vous‑voyez‑est‑ce‑que‑vous‑obtenez), excellent pour le marketing et les pages d'atterrissage.
- Sanity : modélisation de contenu puissante et relations, texte riche avec blocs intégrés, excellente intégration Nuxt et aperçus rapides.
- Strapi : option solide d'auto‑hébergement ou cloud avec relations fortes et rôles ; ressemble à un CMS traditionnel.


- Meilleur fonctionnalités générales pour vos besoins : Sanity ou Storyblok
  - Voulez l'éditeur le plus visuel et l'intégration non‑dev la plus rapide ? Choisissez Storyblok
  - Voulez une flexibilité maximale, une simplicité dans l'editeur malgré une présentation austère, des relations fortes entre les types de contenus/données, limiter les possibilités supperficielles et aller à l'essentiel ? Choisissez Sanity
- Préférez le contrôle auto‑hébergé avec un admin traditionnel et des rôles forts ? Choisissez Strapi 

---


## Aperçus des Plateformes (Business‑First)

### 1) SANITY
Ce que c'est : Plateforme de contenu moderne utilisée par des marques comme PUMA, Figma, Nike

- 2 vidéos de présentation : 
  - Lien 1: [Vidéo présentation](https://www.loom.com/share/aaa76c2baeae48a28b96bc1f0998ec95?sid=e94cd11b-3a75-4823-b7a8-7848da34dc6e)
  - Lien 2: [Vidéo complémentaire](https://www.loom.com/share/d73c2ae76ec14ee19072f56598fe4e61?sid=147ecda8-9d35-4441-9bb5-43956b6c8613)

Avantages
- Aperçu en temps réel ; les changements s'affichent instantanément
- Excellente gestion d'images et CDN
- Relations puissantes et Portable Text (intégrer blocs/références) : Editeur de texte riche (très utile pour les blogs/articles)
- Évolue bien, excellente intégration Nuxt (@nuxtjs/sanity)

Inconvénients
- Interface d'édition basée sur des formulaires (moins visuelle que Storyblok)
- Langage de requête GROQ ajoute une petite courbe d'apprentissage

Prix indicatifs (10 personnes)
- Plan gratuit pour commencer ; Croissance autour de 150€/mois
- Total typique avec actifs : ~170–180€/mois

Meilleur pour vous si
- Vous voulez une modélisation flexible (circuits, destinations, guides) et un aperçu rapide, et votre équipe est OK avec un éditeur basé sur des formulaires simples au lieu de la construction de pages par Drag&Drop par exemple.

--- 

### 2) STORYBLOK
Ce que c'est : Plateforme de contenu visuelle utilisée par Adidas, Tesla, Marc O'Polo


- 1 vidéo de présentation : 
  - Lien: [Vidéo présentation](https://www.loom.com/share/1f5f2c0f90724f19b6bc53fc94c65a6b?sid=637b7e78-4210-4c88-9d55-2214d8302c9c)

Avantages
- Éditeur visuel : preview les pages pendant l'édition
- Blocs de contenu par drag&drop ; excellent pour les landing pages, et campagnes, etc...
- Localisation forte et réutilisation de composants (Facilité de traduction par IA, création de composants customs qu'on pourra intégrer dans l'outil)

Inconvénients
- Plus orienté autour des composants/blocs ; nécessite une planification préalable (A la manière du markdown Nuxt Content/Studio)
- Moins de requêtes ad‑hoc vs GROQ

Prix indicatifs (10 personnes)
- Plan Équipe ≈ 299€/mois (~330$) avec 10 utilisateurs et 100GB d'actifs

Meilleur pour vous si
- Les équipes marketing ont besoin d'autonomie maximale et de vitesse pour construire des pages visuellement (Nous ne sommes par certains que ce soit votre besoin même si vous aimez que le site soit déployé rapidement).

---

### 3) STRAPI 
Ce que c'est : CMS open‑source que vous pouvez auto‑héberger ou utiliser Strapi Cloud

- 2 vidéos de présentation : 
  - Lien 1: [Vidéo présentation](https://www.loom.com/share/0ceef9bd79004e9a849075daefb46797?sid=a6233219-8a8e-47ae-a780-23b88f5974a5)
  - Lien 2: [Vidéo complémentaire](https://www.loom.com/share/373e7c2bc7484c9a8fccb3ddb4167b01?sid=8ab5287-3d6f-48cf-b1ea-599722d730eb)


Avantages
- Panneau d'administration traditionnel ; relations fortes des données, composants, zones dynamiques
- RBAC (Role-Based Access Control) : Gestion fine des rôles et permissions pour contrôler qui peut faire quoi dans le CMS
- Workflows personnalisables : Création de processus de validation et de publication (ex: brouillon → révision → publication)
- Large écosystème de plugins : Extensions disponibles pour ajouter des fonctionnalités (SEO, import/export, etc.)
- Fonctionnalités entreprise : Audit logs, authentification SSO, API tokens, webhooks pour l'intégration avec d'autres systèmes
- Fonctionne avec SQL/SQLite/Postgres ; APIs REST/GraphQL

Inconvénients
- Si auto‑hébergé, vous gérez les opérations, l'évolutivité, sauvegardes, mises à jour de sécurité
- Aperçu en temps réel et intégration de blocs riches nécessitent une configuration

Prix indicatifs (10 personnes)
- Auto‑hébergé : coûts d'infrastructure (~50–200€/mois) + maintenance
- Strapi Cloud Pro ≈ 99$/mois (10 sièges) ; Équipe/Entreprise plus élevé

Meilleur pour vous si
- Vous voulez la propriété/contrôle et une sensation CMS familière, et vous êtes OK avec soit gérer l'infrastructure soit payer pour le cloud.

---

### 4) PRISMIC
Ce que c'est : CMS axé marketing avec édition basée sur des slices

Avantages
- Slices pour sections de page réutilisables ; bonne UX d'éditeur
- Aperçus solides, CDN hébergé, fast, Nuxt integration, etc...

Inconvénients
- Modélisation de contenu plus contraignante pour les relations complexes de données 
- Limites d'utilisateurs et de dépôts peuvent vous pousser vers des palliers de tarifs plus élevés 

Prix indicatifs (10 personnes)
- Souvent nécessite un niveau plus élevé (~450€/mois) pour les sièges/fonctionnalités dont vous auriez besoin

Meilleur pour vous si
- Votre priorité est les pages de campagne/marketing avec des bibliothèques de slices prévisibles et vous êtes à l'aise avec le prix.

---

### 5) DIRECTUS
Ce que c'est : CMS headless axé données, piloté par base de données

Avantages
- Fonctionne sur votre base de données ; modélisation relationnelle forte et permissions
- Bon pour les outils internes et tableaux de bord riches en données

Inconvénients
- Texte riche et blocs intégrés nécessitent des patterns et une configuration
- Pas axé sur la construction de pages visuelles pour les marketeurs

Prix indicatifs
- Auto‑hébergé (coût d'infrastructure) ou Directus Cloud Équipe ≈ 349$/mois pour 15 utilisateurs

Meilleur pour vous si
- Vous voulez un CMS axé données sur une DB existante et êtes moins axés sur les workflows marketing.

---

## Comparaison des Fonctionnalités (Langage Simple)

| Fonctionnalité | Sanity | Storyblok | Strapi | Prismic | Directus |
|---------|--------|-----------|--------|---------|----------|
| Facilité d'utilisation pour non‑devs | ⭐⭐⭐ Bon | ⭐⭐⭐⭐⭐ Excellent | ⭐⭐⭐ Bon | ⭐⭐⭐⭐ Très Bon | ⭐⭐ Modéré |
| Construction de pages visuelles | ❌ Non | ✅ Oui | ❌ Non | 🔶 Limité | ❌ Non |
| Vitesse de publication | ⚡ Instantané | ⚡ Instantané | 🔶 Dépend | ⚡ Instantané | 🔶 Dépend |
| Gestion d'images (7GB) | ✅ Excellent | ✅ Excellent | 🔶 Basique | ✅ Bon | 🔶 Basique |
| Multi‑langue | ✅ Excellent | ✅ Excellent | ✅ Bon | ✅ Très Bon | ✅ Bon |
| Relations de contenu | ✅ Excellent | ✅ Excellent | ✅ Excellent | 🔶 Limité | ✅ Excellent |
| Collaboration d'équipe | ✅ Bon | ✅ Excellent | ✅ Bon | ✅ Bon | 🔶 Basique |
| Édition mobile | ✅ Oui | ✅ Oui | ✅ Oui | ✅ Oui | 🔶 Limité |
| Planification | ✅ Oui | ✅ Oui | ✅ Oui | ✅ Oui | ❌ Non |

Notes
- "Construction de pages visuelles" = éditer comme PowerPoint avec changements immédiats à l'écran. Sanity est basé sur des formulaires, mais avec l'aperçu en direct, cela reste rapide.
- "Vitesse de publication" dépend de votre architecture d'hébergement ; toutes les options hébergées recommandées sont rapides avec aperçu.

---

## Coût Total (Approximatif, Mensuel)

| Plateforme | Coût Logiciel | Stockage Supplémentaire | Total Mensuel |
|----------|----------------|--------------------|--------------------|
| Storyblok | ~330€ | Inclus | ~330€ |
| Sanity | ~150€ | ~20–30€ | ~170–180€ |
| Strapi (Cloud) | 99–499$ | Varie | 99–499$ |
| Prismic | ~450€ | Inclus | ~450€ |
| Directus (Cloud) | ~349$ | Inclus | ~349$ |

---

## Migration & Calendrier (Depuis Nuxt Content/Studio)

| Cible | Difficulté | Calendrier | Perturbation Business |
|--------|------------|----------|---------------------|
| Sanity | Modérée | 4–6 semaines | Minimale |
| Storyblok | Facile–Modérée | 3–4 semaines | Minimale |
| Strapi | Difficile (si auto‑hébergé) | 6–8 semaines | Modérée |
| Prismic | Modérée | 4–5 semaines | Minimale |
| Directus | Difficile | 6–8 semaines | Modérée |

Tâches de migration clés
- Créer les modèles de données (collections/types)
- Migrer le contenu actuel(voyages, destinations, guides, avis) vers le nouveau modèle
- Définir texte riche + blocs intégrés  ( composants custom, images, encadrés, code, galeries, etc...)
- Configurer les workflows d'aperçu et rôles éditoriaux tôt
- Remplir le contenu et valider les URLs avant la mise en ligne

---

## Recommandation Finale (Classement Mis à Jour)

1) Sanity — Meilleur équilibre de flexibilité, performance et coût. Si vous avez besoin de relations riches et de contenu évolutif avec une excellente stack Nuxt, choisissez ceci.
2) Storyblok — Meilleur pour les éditeurs non‑techniques et la construction rapide de pages. Si votre équipe valorise le plus l'édition visuelle et l'autonomie, cela délivre une productivité immédiate.
3) Strapi — CMS traditionnel fort avec rôles/permissions ; bon choix si vous préférez plus de contrôle ou l'auto‑hébergement (ou un Strapi Cloud géré) et acceptez plus de configuration.
4) Prismic — Workflows marketing polis et slices ; prix continu plus élevé au niveau dont vous auriez probablement besoin.
5) Directus — Meilleur si vous êtes vraiment pilotés par base de données et moins axés sur la construction de pages marketing/éditoriales.

---



