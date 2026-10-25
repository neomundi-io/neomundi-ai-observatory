> **Explorer les preuves :** [pilotes, Observatoire, méthodes et travaux historiques](https://github.com/neomundi-io/neomundi-station-public/blob/main/EVIDENCE.fr.md). Ce dépôt conserve ses pièces et son périmètre d'origine. Les futurs résultats Station seront distingués de ces travaux.

[🇬🇧 English](./README.md) · [🇫🇷 Français](./README.fr.md)

---

# Observatoire des IA NeoMundi

## Mesurer le comportement des IA dans le temps

L’Observatoire des IA NeoMundi est une initiative de recherche ouverte consacrée à l’observation, à la mesure et à la documentation du comportement des systèmes d’IA dans des conditions répétées et comparables.

Il produit des mesures longitudinales, des méthodologies publiques, des jeux de données, des publications analytiques et des preuves reproductibles portant notamment sur :

- la stabilité ;
- la variation sémantique ;
- la dérive comportementale ;
- les signaux de risque factuel ;
- la cohérence ;
- les coûts et la consommation de tokens ;
- la latence ;
- la couverture de mesure ;
- les conditions et limites de l’observation.

NeoMundi ne publie ni classement, ni verdict universel, ni certification de modèles.

L’objectif est de produire des mesures, des traces, des méthodes et des preuves publiques pouvant être examinées, discutées, améliorées et réutilisées.

> **Un signal n’est pas un verdict. L’observation doit rester distincte de l’interprétation.**

---

## Explorer l’Observatoire

L’Observatoire mène actuellement des programmes publics de mesure récurrents et documente des articulations expérimentales autour des signaux de mesure runtime NeoMundi.

### [Explorer la Météo des IA NeoMundi →](https://github.com/neomundi-io/neomundi-ai-weather)

Observation quotidienne du comportement d’un panel fixe de systèmes d’IA soumis aux mêmes questions, avec un signal synthétique de niveau d’attention et une question du jour traduite en plusieurs langues.

### [Voir le Baromètre hebdomadaire des IA →](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)

Suivi longitudinal de la stabilité, de la variation sémantique, des signaux de risque factuel, de la couverture de mesure et de la dérive comportementale au fil de périodes d’observation répétées.

### [Explorer la Cartographie mensuelle du comportement des IA →](https://github.com/neomundi-io/ai-behavior-cartography)

Campagnes de mesure comparative menées dans des conditions d’observation partagées ou documentées, sans réduire les systèmes d’IA à un score unique ou à un classement.

### [Explorer le cadre des stations distribuées →](https://github.com/neomundi-io/neomundi-distributed-stations)

Cadre expérimental de gouvernance, de gestion des données et de contribution pour les stations internationales distribuées de mesure et de recherche appliquée de NeoMundi.

### [Explorer les cas d’usage documentés →](https://github.com/neomundi-io/neomundi-use-cases)

Pilotes, expérimentations d’interopérabilité et articulations opérationnelles documentés montrant comment des systèmes indépendants peuvent consommer les signaux de mesure runtime NeoMundi tout en conservant leur architecture et leur autorité.

---

## Validation métrologique

La méthodologie, l’étalonnage, la reproductibilité et les preuves soutenant les signaux de mesure NeoMundi sont documentés dans le dépôt [**NeoMundi Metrology Validation**](https://github.com/neomundi-io/neomundi-metrology-validation).

Ce dépôt documente la qualification expérimentale progressive de la couche de mesure : ce que les signaux observent, comment ils sont testés, où ils échouent, comment ils se comparent à des références indépendantes et quelles affirmations les preuves disponibles permettent de soutenir.

> **L’observation produit des preuves. La validation métrologique qualifie la mesure.**

---

## Mission

Les systèmes d’IA sont de plus en plus utilisés dans des environnements à enjeux, alors que leur comportement peut évoluer silencieusement selon le temps, les fournisseurs, les prompts, les politiques, les configurations, l’infrastructure ou les conditions de déploiement.

L’Observatoire des IA NeoMundi cherche à répondre à des questions opérationnelles :

- Qu’a-t-on observé ?
- Dans quelles conditions ?
- Dans quelle mesure le comportement était-il stable ou variable ?
- Le système a-t-il changé dans le temps ?
- Quels signaux peuvent être mesurés ?
- Quelles conclusions exigent une interprétation contextuelle ?
- Quelles preuves peuvent soutenir la gouvernance, l’audit et la décision opérationnelle ?

L’Observatoire traite le comportement des IA comme un objet de mesure continue, et non comme une propriété fixe déduite d’un benchmark unique.

---

## Principes de mesure

L’Observatoire suit plusieurs principes fondamentaux :

- **observation répétée** plutôt qu’évaluation ponctuelle ;
- **mesure longitudinale** plutôt qu’instantanés statiques ;
- **conditions comparables** lorsque cela est techniquement possible ;
- **transparence des méthodologies et des limites** ;
- **séparation entre mesure et interprétation** ;
- **désidentification des systèmes observés dans les publications publiques** ;
- **absence de classement public par défaut** ;
- **preuves publiques sans divulgation de données opérationnelles protégées** ;
- **reproductibilité dans des limites explicitement documentées**.

Les signaux observés peuvent indiquer une variation, une instabilité, un risque factuel ou un changement de régime. Ils n’établissent pas, à eux seuls, la qualité globale, la sécurité, la conformité ou l’adéquation d’un modèle à un cas d’usage précis.

---

## Programmes de recherche

L’Observatoire organise actuellement une partie de ses travaux publics de mesure autour de programmes récurrents.

### Baromètre hebdomadaire des IA

Le Baromètre hebdomadaire effectue des mesures répétées visant à détecter la variation comportementale et la dérive dans le temps.

Il observe si les systèmes d’IA :

- restent stables au fil d’exécutions répétées ;
- changent de régime de réponse ;
- présentent une variation sémantique ;
- produisent des signaux de risque factuel ;
- montrent des changements de couverture de mesure ;
- se comportent différemment d’une période d’observation à l’autre.

**Dépôt :**  
[NeoMundi Weekly AI Barometer](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)

Le dépôt comprend la méthodologie publique, la baseline de référence, les publications hebdomadaires, les données agrégées, les définitions des métriques, les limites d’interprétation, les manifestes de publication et les informations de provenance.

### Cartographie mensuelle du comportement des IA

La Cartographie mensuelle mène des campagnes de mesure comparative dans des conditions d’observation partagées ou documentées.

Elle vise à cartographier les différences entre les systèmes d’IA sans réduire les résultats à un score unique ou à un classement.

Le programme peut comprendre des mesures portant sur :

- la stabilité ;
- la variation sémantique ;
- la validité factuelle ;
- l’accord entre méthodes d’évaluation ;
- la cohérence ;
- le coût ;
- la consommation de tokens ;
- la latence ;
- les régimes comportementaux ;
- la structure des réponses ;
- les limites de la mesure.

**Dépôt :**  
[NeoMundi AI Behaviour Cartography](https://github.com/neomundi-io/ai-behavior-cartography)

La Cartographie fournit une vue comparative, tandis que le Baromètre fournit un suivi temporel. Ensemble, ils soutiennent l’observation intersystèmes et longitudinale.

---

## Architecture d’observation

L’Observatoire structure progressivement ses travaux publics autour de cinq fonctions complémentaires :

1. **Observation runtime**  
   Capturer le comportement des IA dans des conditions d’exécution documentées.

2. **Production de signaux comportementaux**  
   Mesurer la stabilité, la variation, la cohérence, les signaux de risque factuel, la latence, les coûts et les régimes comportementaux.

3. **Analyse longitudinale**  
   Comparer les mesures entre des exécutions répétées et des périodes d’observation.

4. **Production de preuves publiques**  
   Publier des données agrégées, des méthodologies, des manifestes, des rapports analytiques et des informations de reproductibilité.

5. **Interopérabilité de gouvernance**  
   Rendre les mesures runtime utilisables par des systèmes d’audit, de conformité, d’observabilité, de gouvernance et de contrôle d’exécution.

L’Observatoire produit des preuves et des signaux. Les décisions de gouvernance ou d’exécution restent sous la responsabilité des systèmes et organisations qui les consomment.

---

## Axes de recherche progressifs

Des axes supplémentaires pourront être introduits à mesure que l’Observatoire, les jeux de données et les méthodologies gagneront en maturité.

### Questions thématiques hebdomadaires

Questions publiques récurrentes liées à l’actualité, destinées à observer la façon dont les systèmes d’IA répondent à des sujets récents, socialement pertinents ou sensibles au temps.

### Mesures intra-fournisseur

Mesures répétées au sein d’un même fournisseur ou d’une même famille de modèles, destinées à observer la variabilité interne, la cohérence, la dérive et les changements de régime.

### Mesures sectorielles verticales

Programmes d’observation propres à des secteurs tels que le droit, la santé, la finance, l’assurance, l’éducation, l’administration publique, la cybersécurité et les systèmes industriels.

### Revues externes et analyses indépendantes

Revues méthodologiques, analyses menées par des contributeurs, audits externes et commentaires publics portant sur les résultats publiés.

### Protocoles expérimentaux

Nouveaux formats d’observation, jeux de données et méthodes analytiques introduits dans des conditions expérimentales clairement documentées.

Ces axes ne doivent pas être interprétés comme des certifications, des classements ou des conclusions définitives, sauf si une méthodologie explicite l’établit.

---

## Preuves publiques et reproductibilité

L’Observatoire publie des preuves publiques au moyen de dépôts dédiés et de publications officielles.

Selon le programme, les artefacts publics peuvent comprendre :

- des jeux de données agrégés ;
- des synthèses de publication ;
- des contrats de mesure ;
- des documents méthodologiques ;
- des campagnes baseline ;
- des manifestes de fichiers ;
- des empreintes d’intégrité ;
- des rapports analytiques ;
- des cartographies visuelles ;
- des comparaisons longitudinales ;
- des limites documentées.

Les publications publiques visent à permettre les contrôles de cohérence interne, la revue méthodologique, l’analyse indépendante, la comparaison entre publications et la discussion publique des signaux observés.

Une reproduction complète à partir des sources peut exiger l’accès à des exports de campagne protégés, à la configuration de l’infrastructure ou à des données opérationnelles restreintes. Chaque dépôt documente sa propre frontière de reproductibilité.

---

## Protection des données et désidentification

Les publications publiques de l’Observatoire utilisent par défaut des informations agrégées et désidentifiées.

Les systèmes observés peuvent être représentés par des identifiants de profil opaques et stables. Les identifiants publics ne sont pas attribués selon la performance, le fournisseur, le modèle, l’ordre alphabétique, le score ou le rang.

Certaines informations peuvent rester restreintes, notamment :

- les correspondances entre fournisseurs et modèles ;
- les prompts ou leurs identifiants ;
- les réponses complètes des modèles ;
- les identifiants de requête et de trace ;
- les payloads bruts ;
- les horodatages par réponse ;
- les clés API et identifiants d’accès ;
- les coûts privés détaillés ;
- les résultats non publiés ;
- les informations de débogage ;
- les éléments stratégiques ou commercialement sensibles.

L’existence d’un registre privé de correspondance signifie que les publications doivent être décrites comme **désidentifiées**, et non comme irréversiblement anonymes.

L’accès aux éléments non publics n’est pas automatique et peut nécessiter un cadre spécifique de gouvernance, de recherche ou de confidentialité.

---

## Stations internationales expérimentales

NeoMundi prépare un réseau distribué de stations expérimentales de mesure et de recherche appliquée.

Ces stations ont vocation à mener des campagnes locales ou régionales, reproduire des protocoles communs, tester des articulations indépendantes, documenter des cas d’usage contextuels, contribuer au corpus commun et renforcer la diversité géographique et institutionnelle de l’Observatoire.

Durant la phase expérimentale, une station est :

- un nœud de contribution et de mesure ;
- ni une filiale, ni une franchise ;
- ni une entité juridique autonome ;
- ni un représentant commercial exclusif ;
- non autorisée à engager juridiquement NeoMundi.

L’autonomie des stations doit progresser avec la qualité des mesures, la rigueur méthodologique, la continuité des contributions, les usages réels et la confiance accumulée.

Les profils individuels des stations seront publiés après validation des contributeurs et acceptation formelle du cadre expérimental.

**Dépôt du cadre :**  
[NeoMundi Distributed Stations](https://github.com/neomundi-io/neomundi-distributed-stations)

---

## Infrastructure institutionnelle et normative

NeoMundi développe progressivement les fondations institutionnelles, de gouvernance et de normalisation nécessaires au soutien à long terme d’une métrologie indépendante des IA.

Ces travaux visent notamment l’architecture institutionnelle de l’Observatoire, l’indépendance scientifique, la gestion des preuves publiques, les règles de contribution et d’attribution, les conflits d’intérêts, les révisions méthodologiques, la doctrine de publication et d’archivage, les principes de propriété intellectuelle et de licence, l’interopérabilité et la trajectoire vers une normalisation internationale de la métrologie runtime des IA.

**Dépôt public :**  
[NeoMundi Distributed Stations — Governance, Data and Contribution Framework](https://github.com/neomundi-io/neomundi-distributed-stations)

Le dépôt documente le cadre expérimental de gouvernance, de gestion des données, de contribution, d’attribution et d’autonomie progressive des stations internationales distribuées de NeoMundi.

Il définit également les principes par défaut relatifs à la conservation des données brutes, aux espaces collaboratifs partagés, aux manifestes de campagne, à la provenance des composants, à l’historique des corrections, à l’approbation des publications, à la réversibilité des stations, aux opportunités commerciales et à la relation entre les stations locales et le Hub NeoMundi.

Le programme institutionnel se développe parallèlement aux programmes publics de mesure, mais à un rythme différent. Les mesures publiques établissent la légitimité empirique ; l’infrastructure institutionnelle soutient la continuité, la responsabilité et la future normalisation.

---

## Cadre de contribution

L’Observatoire fonctionne selon un cadre de contribution léger pour le cycle exploratoire de juin à décembre 2026.

### Version de référence

- [Version française — Esprit NeoMundi & cadre de contribution v1.0](./governance/esprit-neomundi-cadre-contribution-v1.0-fr.md)

### Traductions de courtoisie

- [Version anglaise — NeoMundi Spirit & Contribution Framework v1.0](./governance/neomundi-spirit-contribution-framework-v1.0-en.md)
- [Version espagnole — Marco de contribución y espíritu NeoMundi v1.0](./governance/marco-contribucion-espiritu-neomundi-v1.0-es.md)
- [Version arabe — Esprit NeoMundi & cadre de contribution v1.0](./governance/esprit-neomundi-cadre-contribution-v1_0-ar.md)
- [Version éwé — NeoMundi Contribution Charter EWE v1.0](./governance/NeoMundi_Contribution_Charter_EWE_v1.0.md)

La version française est la version de référence. Les traductions sont des contributions linguistiques produites ou relues par des locuteurs natifs engagés auprès de l’Observatoire.

Elles symbolisent une infrastructure scientifique ouverte, multilingue et internationale, dans laquelle la diversité linguistique participe à la construction d’un cadre commun.

> **La technologie ne suffit pas. La langue, la culture et le sens partagé font partie de l’infrastructure.**

### Annexe A — Cadre de contribution indépendante

- [Version française — Engagement de contribution indépendante v0.1](./governance/annexe-a-engagement-contribution-independante-v0.1-fr.md)
- [Version anglaise — Independent Contribution Framework v0.1](./governance/annex-a-independent-contribution-framework-v0.1-en.md)

Cette annexe complète « Esprit NeoMundi & cadre de contribution » et définit les conditions applicables aux contributeurs, relecteurs, pairs méthodologiques, experts et contributeurs d’infrastructure participant à l’Observatoire.

---

## Contribuer

NeoMundi Recherche accueille les contributions relatives à la méthodologie et aux protocoles, à l’analyse de données, à la métrologie, à la gouvernance de l’IA, aux revues juridiques, éthiques et de conformité, à la revue scientifique, à la documentation technique, aux infrastructures et à l’interopérabilité, à la rédaction, la traduction et la pédagogie, à la recherche d’intérêt public ainsi qu’aux partenariats et au développement institutionnel.

Le cycle actuel de contribution est exploratoire, bénévole et limité dans son périmètre.

Avant de proposer une contribution, veuillez consulter le cadre de contribution. Un formulaire public sera mis à disposition sur le site officiel de NeoMundi.

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

Cette référence externe constitue un garde-fou utile en matière de contribution, d’attribution, de non-extraction et de limites d’autorité.

Elle ne place pas NeoMundi sous l’autorité de ce cadre et ne crée aucune dépendance institutionnelle.

Des informations complémentaires sur les références externes et les contributeurs peuvent être documentées dans le répertoire [`governance`](./governance/).

---

## Rôle de ce dépôt

Ce dépôt est la porte d’entrée publique de l’Observatoire des IA NeoMundi.

Il contient :

- la mission et les principes de mesure de l’Observatoire ;
- un accès direct aux programmes publics récurrents ;
- le cadre de contribution ;
- les documents de gouvernance et d’orientation ;
- les ressources d’accueil des contributeurs ;
- les liens vers les preuves publiques et les dépôts dédiés ;
- les informations sur le programme de stations distribuées ;
- les informations sur le programme institutionnel et normatif.

Les données, scripts, méthodologies, publications et artefacts techniques détaillés sont publiés dans les dépôts des programmes concernés.

---

## Liens NeoMundi

- **Site officiel — anglais :** [neomundi.org/en/home](https://neomundi.org/en/home)
- **Site officiel — français :** [neomundi.org](https://neomundi.org)
- **Baromètre hebdomadaire des IA :** [github.com/neomundi-io/NeoMundi-Weekly-Barometer](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)
- **Cartographie mensuelle du comportement des IA :** [github.com/neomundi-io/ai-behavior-cartography](https://github.com/neomundi-io/ai-behavior-cartography)
- **Cadre des stations distribuées :** [github.com/neomundi-io/neomundi-distributed-stations](https://github.com/neomundi-io/neomundi-distributed-stations)
- **Démonstration ControlTower :** [controltower.neomundi.io/welcome](https://controltower.neomundi.io/welcome)
- **Organisation GitHub :** [github.com/neomundi-io](https://github.com/neomundi-io)
- **Cadre théorique — Loi E :** [DOI 10.5281/zenodo.19385052](https://doi.org/10.5281/zenodo.19385052)
- **From AI Observability to Governance Metrology :** [DOI 10.5281/zenodo.21250268](https://doi.org/10.5281/zenodo.21250268)
- **Contact :** [contact@neomundi.org](mailto:contact@neomundi.org)

Pour les cas d’usage industriels, la mesure runtime, les programmes pilotes, l’interopérabilité ou ControlTower, contactez directement NeoMundi.

---

## Écosystème et soutien d’infrastructure

L’Observatoire développe ses travaux au sein d’un écosystème ouvert de contributeurs techniques, scientifiques, institutionnels et d’infrastructure.

### Soutien d’infrastructure

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

Elles n’impliquent aucune approbation des résultats de recherche, mesures, méthodologies ou interprétations de l’Observatoire par les organisations citées.

© 2025 NVIDIA, le logo NVIDIA et NVIDIA Inception sont des marques commerciales et/ou déposées de NVIDIA Corporation aux États-Unis et dans d’autres pays.

---

## Licence

Ce dépôt utilise actuellement la [licence Apache 2.0](LICENSE).

Certains jeux de données, rapports, traductions, composants logiciels ou contributions externes peuvent comporter des licences ou mentions complémentaires lorsque cela est nécessaire.
