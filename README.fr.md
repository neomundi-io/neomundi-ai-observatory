## 🌐 Choisir votre langue

**[🇬🇧 English](README.md)** · **[🇫🇷 Français](README.fr.md)**

---

# Observatoire IA NeoMundi

**Mesurer le comportement des IA dans le temps.**

L’Observatoire IA NeoMundi est une initiative de recherche ouverte consacrée à l’observation, à la mesure et à la documentation du comportement des systèmes d’intelligence artificielle dans des conditions répétées et comparables.

Il produit des mesures longitudinales, des méthodologies publiques, des jeux de données, des publications analytiques et des éléments de preuve reproductibles portant notamment sur :

- la stabilité ;
- la variation sémantique ;
- la dérive comportementale ;
- les signaux de risque factuel ;
- la cohérence ;
- les coûts et la consommation de tokens ;
- la latence ;
- la couverture de mesure ;
- les conditions et les limites d’observation.

NeoMundi ne publie ni classements, ni verdicts universels, ni certifications de modèles.

Son objectif est de produire des mesures, des traces, des méthodes et des preuves publiques pouvant être examinées, discutées, améliorées et réutilisées.

**Un signal n’est pas un verdict. L’observation doit rester distincte de l’interprétation.**

---

## Mission

Les systèmes d’IA sont de plus en plus utilisés dans des environnements à conséquences, alors même que leur comportement peut évoluer silencieusement selon le temps, les fournisseurs, les prompts, les politiques, les configurations, les infrastructures ou les conditions de déploiement.

L’Observatoire IA NeoMundi vise à répondre à des questions opérationnelles :

- Qu’avons-nous observé ?
- Dans quelles conditions cette observation a-t-elle été réalisée ?
- Quel était le niveau de stabilité ou de variabilité du comportement ?
- Le système a-t-il évolué dans le temps ?
- Quels signaux peuvent être mesurés ?
- Quelles conclusions exigent une interprétation contextuelle ?
- Quelles preuves peuvent soutenir la gouvernance, l’audit et la décision opérationnelle ?

L’Observatoire considère le comportement des IA comme un objet de mesure continue, et non comme une propriété fixe déduite d’un benchmark unique.

---

## Principes de mesure

L’Observatoire s’appuie sur plusieurs principes fondamentaux :

- **Observation répétée** plutôt qu’évaluation ponctuelle ;
- **Mesure longitudinale** plutôt qu’instantané statique ;
- **Conditions comparables** lorsque cela est techniquement possible ;
- **Transparence des méthodologies et des limites** ;
- **Séparation entre mesure et interprétation** ;
- **Désidentification des systèmes observés dans les publications publiques** ;
- **Absence de classement public par défaut** ;
- **Production de preuves publiques sans divulgation de données opérationnelles protégées** ;
- **Reproductibilité dans des limites explicitement documentées**.

Les signaux observés peuvent indiquer une variation, une instabilité, un risque factuel ou un changement de régime. Ils n’établissent pas, à eux seuls, la qualité globale, la sécurité, la conformité ou l’adéquation d’un système à un cas d’usage particulier.

---

## Programmes de recherche

L’Observatoire organise actuellement ses travaux autour de deux programmes publics de mesure récurrents.

### Baromètre IA hebdomadaire

Le Baromètre IA hebdomadaire réalise des mesures répétées destinées à détecter les variations comportementales et les dérives dans le temps.

Il observe notamment si les systèmes d’IA :

- restent stables lors d’exécutions répétées ;
- changent de régime de réponse ;
- présentent des variations sémantiques ;
- produisent des signaux de risque factuel ;
- connaissent des variations de couverture de mesure ;
- se comportent différemment d’une période d’observation à l’autre.

**Dépôt :**  
[NeoMundi Weekly Barometer](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)

Le dépôt comprend notamment :

- la méthodologie publique ;
- la baseline de référence ;
- les releases hebdomadaires ;
- les jeux de données agrégés ;
- les définitions des métriques ;
- les limites d’interprétation ;
- les manifestes de publication et les informations de provenance.

---

### Cartographie mensuelle du comportement des IA

La Cartographie mensuelle du comportement des IA réalise des campagnes de mesure comparatives dans des conditions d’observation communes ou documentées.

Elle vise à cartographier les différences entre systèmes d’IA sans réduire les résultats à un score unique ou à un classement.

Le programme peut inclure des mesures relatives à :

- la stabilité ;
- la variation sémantique ;
- la validité factuelle ;
- l’accord entre méthodes d’évaluation ;
- la cohérence ;
- les coûts ;
- la consommation de tokens ;
- la latence ;
- les régimes comportementaux ;
- la structure des réponses ;
- les limites de mesure.

**Dépôt :**  
[NeoMundi AI Behaviour Cartography](https://github.com/neomundi-io/ai-behavior-cartography)

La Cartographie fournit une vision comparative, tandis que le Baromètre hebdomadaire assure le suivi temporel. Ensemble, ils permettent une observation à la fois transversale et longitudinale.

---

## Architecture d’observation

L’Observatoire structure progressivement ses travaux publics autour de cinq fonctions complémentaires :

1. **Observation runtime**  
   Capturer le comportement des IA dans des conditions d’exécution documentées.

2. **Production de signaux comportementaux**  
   Mesurer la stabilité, la variation, la cohérence, les signaux de risque factuel, la latence, les coûts et les régimes comportementaux.

3. **Analyse longitudinale**  
   Comparer les mesures entre exécutions répétées et périodes d’observation.

4. **Production de preuves publiques**  
   Publier des données agrégées, des méthodologies, des manifestes, des analyses et des informations de reproductibilité.

5. **Interopérabilité avec la gouvernance**  
   Rendre les mesures runtime exploitables par les systèmes d’audit, de conformité, d’observabilité, de gouvernance et de contrôle d’exécution.

L’Observatoire produit des preuves et des signaux. Les décisions de gouvernance ou d’exécution restent sous la responsabilité des systèmes et des organisations qui les utilisent.

---

## Axes de recherche progressifs

Des axes de recherche complémentaires pourront être introduits à mesure que l’Observatoire, les jeux de données et les méthodologies mûrissent.

Ils peuvent notamment inclure :

### Questions thématiques hebdomadaires

Des questions publiques récurrentes liées à l’actualité, destinées à observer la manière dont les systèmes d’IA répondent à des sujets récents, socialement pertinents ou sensibles au temps.

### Mesures intra-fournisseur

Des mesures répétées au sein d’un même fournisseur ou d’une même famille de modèles, destinées à observer la variabilité interne, la cohérence, la dérive et les changements de régime.

### Mesures sectorielles verticales

Des programmes d’observation spécifiques à des secteurs tels que :

- le droit ;
- la santé ;
- la finance ;
- l’assurance ;
- l’éducation ;
- l’administration publique ;
- la cybersécurité ;
- les systèmes industriels.

### Revues externes et analyses indépendantes

Des revues méthodologiques, analyses menées par des contributeurs, audits externes et commentaires publics sur les résultats publiés.

### Protocoles expérimentaux

De nouveaux formats d’observation, jeux de données et méthodes analytiques introduits dans des conditions expérimentales clairement documentées.

Ces axes ne doivent pas être interprétés comme des certifications, des classements ou des conclusions définitives, sauf indication explicite d’une méthodologie dédiée.

---

## Preuves publiques et reproductibilité

L’Observatoire publie des éléments de preuve publics dans ses dépôts dédiés et ses publications officielles.

Selon les programmes, les artefacts publics peuvent inclure :

- des jeux de données agrégés ;
- des synthèses de release ;
- des contrats de mesure ;
- des documents méthodologiques ;
- des campagnes baseline ;
- des manifestes de fichiers ;
- des empreintes d’intégrité ;
- des rapports analytiques ;
- des cartographies visuelles ;
- des comparaisons longitudinales ;
- des limites documentées.

Les publications publiques sont conçues pour permettre :

- des contrôles de cohérence interne ;
- une revue méthodologique ;
- des analyses indépendantes ;
- des comparaisons entre releases ;
- une discussion publique des signaux observés.

La reproduction complète depuis les sources peut nécessiter l’accès à des exports protégés, à la configuration de l’infrastructure ou à des données opérationnelles restreintes.

Chaque dépôt documente ses propres limites de reproductibilité.

---

## Protection des données et désidentification

Les publications publiques de l’Observatoire utilisent par défaut des informations agrégées et désidentifiées.

Les systèmes observés peuvent être représentés par des identifiants opaques stables. Ces identifiants publics ne sont pas attribués selon la performance, le nom du fournisseur, le nom du modèle, l’ordre alphabétique, le score ou le classement.

Certaines informations peuvent rester restreintes, notamment :

- les correspondances entre fournisseurs et modèles ;
- les prompts ou identifiants de prompts ;
- les réponses complètes des modèles ;
- les identifiants de requête et de trace ;
- les payloads bruts ;
- les horodatages par réponse ;
- les clés API et identifiants d’accès ;
- les coûts privés détaillés ;
- les résultats non publiés ;
- les informations de débogage ;
- les informations stratégiques ou commercialement sensibles.

L’existence d’un registre privé de correspondance implique que les publications publiques doivent être décrites comme **désidentifiées**, et non comme irréversiblement anonymes.

L’accès aux éléments non publics n’est pas automatique et peut nécessiter un cadre spécifique de gouvernance, de recherche ou de confidentialité.

---

## Infrastructure institutionnelle et de standardisation

NeoMundi développe progressivement les fondations institutionnelles, de gouvernance et de standardisation nécessaires au développement durable d’une métrologie indépendante des IA.

Ce travail vise notamment à documenter et renforcer :

- l’architecture institutionnelle de l’Observatoire ;
- l’indépendance scientifique et méthodologique ;
- la gestion et la conservation des preuves publiques ;
- les règles de contribution et d’attribution ;
- la gestion des conflits d’intérêts ;
- les processus de révision méthodologique ;
- la doctrine de publication et d’archivage ;
- les principes de propriété intellectuelle et de licences ;
- les exigences d’interopérabilité ;
- les relations avec les systèmes externes de gouvernance ;
- la trajectoire vers une standardisation internationale de la métrologie runtime des IA.

Un dépôt public dédié documentera progressivement ce travail.

**Dépôt :** prévu

Le programme institutionnel se développe parallèlement aux programmes publics de mesure, mais selon un rythme différent. Les mesures publiques établissent la légitimité empirique ; l’infrastructure institutionnelle soutient la continuité, la redevabilité et la future standardisation.

---

## Cadre de contribution

L’Observatoire fonctionne avec un cadre de contribution léger pour le cycle exploratoire de juin à décembre 2026.

### Version de référence

- [Version française de référence — Esprit NeoMundi & cadre de contribution v1.0](./governance/esprit-neomundi-cadre-contribution-v1.0-fr.md)

### Traductions de courtoisie

- [Version anglaise — NeoMundi Spirit & Contribution Framework v1.0](./governance/neomundi-spirit-contribution-framework-v1.0-en.md)
- [Version espagnole — Marco de contribución y espíritu NeoMundi v1.0](./governance/marco-contribucion-espiritu-neomundi-v1.0-es.md)

La version française constitue la version de référence. Les traductions sont fournies afin de faciliter la compréhension et la participation internationales.

---

## Contribuer

NeoMundi Recherche accueille les contributions liées à :

- la conception méthodologique et protocolaire ;
- l’analyse de données ;
- la métrologie ;
- la gouvernance des IA ;
- la revue juridique, éthique et de conformité ;
- la revue scientifique ;
- la documentation technique ;
- l’infrastructure et l’interopérabilité ;
- la rédaction, la traduction et la pédagogie ;
- la recherche d’intérêt public ;
- les partenariats et le développement institutionnel.

Le cycle actuel de contribution est exploratoire, bénévole et limité dans son périmètre.

Avant de proposer une contribution, veuillez consulter le cadre de contribution.

Un formulaire public de contribution sera mis à disposition sur le site officiel de NeoMundi.

---

## Principes de contribution

Les idées circulent.  
Les contributions formalisées sont attribuées.  
Les textes signés sont respectés.  
Les informations sensibles sont protégées.  
Les archives publiées deviennent stables.

L’Observatoire est conçu pour encourager :

- la coopération sans extraction ;
- l’attribution sans captation de propriété ;
- la revue indépendante sans dépendance institutionnelle ;
- la mesure sans proclamation ;
- la transparence sans divulgation incontrôlée.

---

## Référence externe de gouvernance

Le cadre de contribution NeoMundi s’inspire en partie de la Governance Participation Discipline v0.1 et du Collaborative Participation Framework v0.1 publiés par James Aull / MagicianzCardstock LLC.

[Governance Participation Discipline](https://github.com/magicianzcardstockllc/governance-participation-discipline)

Cette référence externe fournit un garde-fou utile concernant la contribution, l’attribution, la non-extraction et les limites d’autorité.

Elle ne place pas NeoMundi sous l’autorité de ce cadre et ne crée aucune dépendance institutionnelle.

Des informations complémentaires concernant les références externes de gouvernance et les contributeurs peuvent être documentées dans le répertoire [`governance`](./governance/).

---

## Rôle de ce dépôt

Ce dépôt constitue le point d’entrée public de l’Observatoire IA NeoMundi.

Il contient :

- la mission et les principes de mesure de l’Observatoire ;
- les liens vers les programmes de recherche récurrents ;
- le cadre de contribution ;
- les documents de gouvernance et d’orientation ;
- les ressources d’intégration des contributeurs ;
- les liens vers les preuves publiques et les dépôts dédiés ;
- les informations relatives au programme institutionnel et de standardisation.

Les jeux de données détaillés, scripts, méthodologies, releases et artefacts techniques sont publiés dans les dépôts correspondant à chaque programme.

---

## Liens NeoMundi

- **Site officiel — Français :** [neomundi.org](https://neomundi.org)
- **Site officiel — English :** [neomundi.org/en/home](https://neomundi.org/en/home)
- **Démonstration ControlTower :** [controltower.neomundi.io/welcome](https://controltower.neomundi.io/welcome)
- **Organisation GitHub :** [github.com/neomundi-io](https://github.com/neomundi-io)
- **Cadre théorique — Loi E :** [DOI 10.5281/zenodo.19385052](https://doi.org/10.5281/zenodo.19385052)
- **Contact :** [contact@neomundi.org](mailto:contact@neomundi.org)

Pour les cas d’usage industriels, les mesures runtime, les programmes pilotes, l’interopérabilité ou les échanges liés à ControlTower, veuillez contacter directement NeoMundi.

---

## Écosystème et soutien à l’infrastructure

L’Observatoire IA NeoMundi développe ses travaux au sein d’un écosystème ouvert de contributeurs techniques, scientifiques, institutionnels et spécialisés en gouvernance.

### Soutien à l’infrastructure

L’Observatoire bénéficie du soutien de partenaires d’infrastructure souveraine, dont Infomaniak.

<img src="logos/ecosystem/logo_infomaniak.png"
     alt="Infomaniak"
     width="150">

### NVIDIA Inception

NeoMundi est membre du programme NVIDIA Inception.

<img src="https://raw.githubusercontent.com/neomundi-io/neomundi-sandbox/main/nvidia-inception-program-badge-rgb-for-screen.png"
     alt="NeoMundi est membre du programme NVIDIA Inception"
     width="180">

Ces relations soutiennent le développement et l’exploitation de capacités indépendantes de mesure des IA, d’auditabilité et de gouvernance runtime.

Elles n’impliquent aucune approbation des résultats de recherche, des mesures, des méthodologies ou des interprétations de l’Observatoire par les organisations mentionnées.

© 2025 NVIDIA, le logo NVIDIA et NVIDIA Inception sont des marques commerciales et/ou des marques déposées de NVIDIA Corporation aux États-Unis et dans d’autres pays.

---

## Licence

Ce dépôt utilise actuellement la [licence Apache 2.0](LICENSE).

Certains jeux de données, rapports, traductions, composants logiciels ou contributions externes peuvent comporter des licences ou mentions complémentaires lorsque cela est nécessaire.
