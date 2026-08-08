## 🌐 Choisissez votre langue

**[🇫🇷 Français](README.fr.md)** · **[🇬🇧 Read the English version](README.md)**

---

# Observatoire des IA NeoMundi

## Mesurer le comportement des IA dans le temps

L’Observatoire des IA NeoMundi est une initiative de recherche ouverte consacrée à l’observation, à la mesure et à la documentation du comportement des systèmes d’IA dans des conditions répétées et comparables.

Il produit des mesures longitudinales, des méthodologies publiques, des jeux de données, des publications analytiques et des éléments de preuve reproductibles portant notamment sur :

- la stabilité ;
- la variation sémantique ;
- la dérive comportementale ;
- les signaux de risque factuel ;
- la cohérence ;
- les coûts et la consommation de tokens ;
- la latence ;
- la couverture de mesure ;
- les conditions et limites d’observation.

NeoMundi ne publie ni classement, ni verdict universel, ni certification des modèles.

Son objectif est de produire des mesures, des traces, des méthodes et des éléments de preuve publics pouvant être examinés, contestés, améliorés et réutilisés.

> **Un signal n’est pas un verdict. L’observation doit rester distincte de l’interprétation.**

---

## Explorer l’Observatoire

L’Observatoire opère actuellement deux programmes publics de mesure récurrents.

### [Voir le Baromètre hebdomadaire des IA →](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)

Suivi longitudinal de la stabilité, de la variation sémantique, des signaux de risque factuel, de la couverture de mesure et de la dérive comportementale au fil de périodes d’observation répétées.

### [Explorer la Cartographie mensuelle du comportement des IA →](https://github.com/neomundi-io/ai-behavior-cartography)

Campagnes de mesure comparatives réalisées dans des conditions d’observation communes ou documentées, sans réduire les systèmes d’IA à un score unique ou à un classement.

### [Explorer le cadre des stations distribuées →](https://github.com/neomundi-io/neomundi-distributed-stations)

Cadre expérimental de gouvernance, de gestion des données et de contribution pour les stations internationales distribuées de mesure et de recherche appliquée de NeoMundi.

---

## Validation métrologique

La méthodologie, la calibration, la reproductibilité et les éléments de preuve soutenant les signaux de mesure NeoMundi sont documentés dans le repository [**NeoMundi Metrology Validation**](https://github.com/neomundi-io/neomundi-metrology-validation).

Ce repository documente la qualification expérimentale progressive de la couche de mesure : ce que les signaux observent, comment ils sont testés, où ils échouent, comment ils se comparent à des références indépendantes et quelles affirmations les preuves disponibles permettent de soutenir.

> **L’Observatoire produit des observations. Metrology Validation qualifie la mesure.**

---

---

### Soutien infrastructure

L’Observatoire IA NeoMundi est soutenu par des partenaires d’infrastructure souveraine, notamment Infomaniak.

<img src="logos/ecosystem/logo_infomaniak.png"
     alt="Infomaniak"
     width="135">

---

## Mission

Les systèmes d’IA sont de plus en plus utilisés dans des environnements à conséquences importantes, alors que leur comportement peut évoluer silencieusement selon le temps, les fournisseurs, les prompts, les politiques, les configurations, les infrastructures ou les conditions de déploiement.

L’Observatoire IA NeoMundi existe pour aider à répondre à des questions opérationnelles :

- Qu’a-t-on observé ?
- Dans quelles conditions l’a-t-on observé ?
- Dans quelle mesure le comportement était-il stable ou variable ?
- Le système a-t-il changé au fil du temps ?
- Quels signaux peuvent être mesurés ?
- Quelles conclusions exigent une interprétation contextuelle ?
- Quels éléments de preuve peuvent soutenir la gouvernance, l’audit et la décision opérationnelle ?

L’Observatoire traite le comportement des IA comme un objet de mesure continue, plutôt que comme une propriété fixe déduite d’un benchmark unique.

---

## Principes de mesure

L’Observatoire suit plusieurs principes fondamentaux :

- **Observation répétée** plutôt qu’évaluation ponctuelle ;
- **Mesure longitudinale** plutôt que photographie statique ;
- **Conditions comparables** lorsque cela est techniquement possible ;
- **Méthodologies et limites transparentes** ;
- **Séparation entre mesure et interprétation** ;
- **Désidentification des systèmes observés dans les publications publiques** ;
- **Absence de classement public par défaut** ;
- **Publication d’éléments de preuve sans exposition des données opérationnelles protégées** ;
- **Reproductibilité dans des limites explicitement documentées**.

Les signaux observés peuvent indiquer une variation, une instabilité, un risque factuel ou un changement de régime. Ils n’établissent pas à eux seuls la qualité globale, la sécurité, la conformité ou l’adéquation d’un modèle à un cas d’usage donné.

---

## Programmes de recherche

L’Observatoire organise actuellement ses travaux publics autour de deux programmes récurrents.

### Baromètre hebdomadaire des IA

Le Baromètre hebdomadaire réalise des mesures répétées conçues pour détecter les variations comportementales et les dérives dans le temps.

Il observe notamment si les systèmes d’IA :

- restent stables au fil d’exécutions répétées ;
- changent de régime de réponse ;
- présentent une variation sémantique ;
- produisent des signaux de risque factuel ;
- montrent des variations de couverture de mesure ;
- se comportent différemment d’une période d’observation à l’autre.

**Dépôt :**  
[NeoMundi Weekly AI Barometer](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)

Le dépôt comprend notamment :

- la méthodologie publique ;
- la baseline de référence ;
- les publications hebdomadaires ;
- les jeux de données agrégés ;
- les définitions des métriques ;
- les frontières d’interprétation ;
- les manifests de publication et les informations de provenance.

---

### Cartographie mensuelle du comportement des IA

La Cartographie mensuelle réalise des campagnes comparatives dans des conditions d’observation partagées ou documentées.

Elle vise à cartographier les différences entre systèmes d’IA sans réduire les résultats à un score unique ni à un classement.

Le programme peut inclure des mesures relatives à :

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
- les limites de mesure.

**Dépôt :**  
[NeoMundi AI Behaviour Cartography](https://github.com/neomundi-io/ai-behavior-cartography)

La Cartographie fournit une vue comparative, tandis que le Baromètre apporte un suivi temporel. Ensemble, ils soutiennent à la fois l’observation inter-systèmes et l’analyse longitudinale.

---

## Architecture d’observation

L’Observatoire structure progressivement ses travaux publics autour de cinq fonctions complémentaires :

1. **Observation runtime**  
   Capturer le comportement des IA dans des conditions d’exécution documentées.

2. **Production de signaux comportementaux**  
   Mesurer la stabilité, la variation, la cohérence, les signaux de risque factuel, la latence, le coût et les régimes comportementaux.

3. **Analyse longitudinale**  
   Comparer les mesures entre exécutions répétées et périodes d’observation.

4. **Production d’éléments de preuve publics**  
   Publier des données agrégées, des méthodologies, des manifests, des rapports analytiques et des informations de reproductibilité.

5. **Interopérabilité avec les systèmes de gouvernance**  
   Rendre les mesures runtime utilisables par des systèmes d’audit, de conformité, d’observabilité, de gouvernance ou de contrôle d’exécution.

L’Observatoire produit des mesures et des éléments de preuve. Les décisions de gouvernance ou d’exécution restent sous la responsabilité des systèmes et des organisations qui les consomment.

---

## Axes de recherche progressifs

Des axes complémentaires peuvent être introduits à mesure que l’Observatoire, les datasets et les méthodologies gagnent en maturité.

### Questions thématiques hebdomadaires

Questions publiques récurrentes liées à l’actualité, conçues pour observer la manière dont les systèmes d’IA répondent à des sujets récents, socialement pertinents ou sensibles au temps.

### Mesures intra-fournisseur

Mesures répétées au sein d’un même fournisseur ou d’une même famille de modèles, afin d’observer la variabilité interne, la cohérence, la dérive et les changements de régime.

### Mesures sectorielles

Programmes d’observation spécifiques à des domaines tels que :

- le droit ;
- la santé ;
- la finance ;
- l’assurance ;
- l’éducation ;
- l’administration publique ;
- la cybersécurité ;
- les systèmes industriels.

### Revues externes et analyses indépendantes

Revues méthodologiques, analyses portées par des contributeurs, audits externes et commentaires publics sur les résultats publiés.

### Protocoles expérimentaux

Nouveaux formats d’observation, datasets et méthodes analytiques introduits dans des conditions expérimentales clairement documentées.

Ces axes ne doivent pas être interprétés comme des certifications, des classements ou des conclusions définitives, sauf si une méthodologie explicite l’établit.

---

## Éléments de preuve publics et reproductibilité

L’Observatoire publie ses éléments de preuve dans des dépôts dédiés et au sein de publications officielles.

Selon le programme, les artefacts publics peuvent inclure :

- des jeux de données agrégés ;
- des synthèses de publication ;
- des contrats de mesure ;
- des documents méthodologiques ;
- des campagnes de baseline ;
- des manifests de fichiers ;
- des hashes d’intégrité ;
- des rapports analytiques ;
- des cartographies visuelles ;
- des comparaisons longitudinales ;
- des limites documentées.

Les publications publiques sont conçues pour permettre :

- des contrôles de cohérence interne ;
- une revue méthodologique ;
- des analyses indépendantes ;
- des comparaisons entre publications ;
- une discussion publique des signaux observés.

Une reproduction complète à partir des sources peut nécessiter l’accès à des exports de campagne protégés, à des configurations d’infrastructure ou à des données opérationnelles restreintes.

Chaque dépôt documente sa propre frontière de reproductibilité.

---

## Protection des données et désidentification

Les publications publiques de l’Observatoire utilisent par défaut des informations agrégées et désidentifiées.

Les systèmes observés peuvent être représentés au moyen d’identifiants opaques et stables. Ces identifiants publics ne sont pas attribués en fonction des performances, du nom du fournisseur, du nom du modèle, de l’ordre alphabétique, d’un score ou d’un rang.

Certaines informations peuvent rester restreintes, notamment :

- les correspondances fournisseur–modèle ;
- les prompts ou identifiants de prompts ;
- les réponses complètes des modèles ;
- les identifiants de requête et de trace ;
- les payloads bruts ;
- les horodatages par réponse ;
- les clés API et identifiants ;
- les coûts privés détaillés ;
- les résultats non publiés ;
- les informations de débogage ;
- les éléments stratégiques ou commercialement sensibles.

L’existence d’un registre privé de correspondance implique que les publications doivent être décrites comme **désidentifiées**, et non comme irréversiblement anonymes.

L’accès aux éléments non publics n’est pas automatique et peut nécessiter un cadre spécifique de gouvernance, de recherche ou de confidentialité.

---

## Stations internationales expérimentales

NeoMundi prépare un réseau distribué de stations expérimentales de mesure et de recherche appliquée.

Ces stations ont vocation à :

- conduire des campagnes de mesure locales ou régionales ;
- reproduire des protocoles communs ;
- tester des articulations indépendantes ;
- documenter des cas d’usage liés à leur contexte ;
- contribuer au corpus commun par des observations et des analyses ;
- relier des infrastructures, chercheurs et institutions locales ;
- renforcer la diversité géographique et institutionnelle de l’Observatoire.

Pendant la phase expérimentale, une station est :

- un nœud de contribution et de mesure ;
- ni une filiale ;
- ni une franchise ;
- ni une entité juridique autonome ;
- ni un représentant commercial exclusif ;
- ni une structure autorisée à engager juridiquement NeoMundi.

L’autonomie des stations a vocation à se construire progressivement par la qualité des mesures, la rigueur méthodologique, la continuité des contributions, les usages réels et la confiance accumulée.

Les fiches individuelles des stations seront publiées après validation des contributeurs et acceptation formelle du cadre expérimental.

**Dépôt du cadre :**  
[NeoMundi Distributed Stations](https://github.com/neomundi-io/neomundi-distributed-stations)

---

## Infrastructure institutionnelle et normalisation

NeoMundi développe progressivement les fondations institutionnelles, de gouvernance et de normalisation nécessaires au soutien durable d’une métrologie indépendante des IA.

Ce travail vise notamment à documenter et renforcer :

- l’architecture institutionnelle de l’Observatoire ;
- l’indépendance scientifique et méthodologique ;
- la gestion des éléments de preuve publics ;
- les règles de contribution et d’attribution ;
- la gestion des conflits d’intérêts ;
- les processus de révision méthodologique ;
- la doctrine de publication et d’archivage ;
- les principes de propriété intellectuelle et de licence ;
- les exigences d’interopérabilité ;
- les relations avec les systèmes externes de gouvernance ;
- la trajectoire vers une normalisation internationale de la métrologie runtime des IA.

**Dépôt public :**  
[NeoMundi Distributed Stations — Cadre de gouvernance, de données et de contribution](https://github.com/neomundi-io/neomundi-distributed-stations)

Le dépôt documente le cadre expérimental de gouvernance, de gestion des données, de contribution, d’attribution et d’autonomie progressive des stations internationales distribuées NeoMundi.

Il définit également les principes par défaut concernant :

- la conservation des données brutes ;
- les espaces collaboratifs partagés ;
- les manifests de campagne ;
- la provenance des composants ;
- l’historique des corrections ;
- la validation des publications ;
- la réversibilité des stations ;
- les opportunités commerciales ;
- la relation entre les stations locales et le hub NeoMundi.

Le programme institutionnel évolue parallèlement aux programmes publics de mesure, mais à un rythme différent. Les mesures publiques construisent la légitimité empirique ; l’infrastructure institutionnelle soutient la continuité, la responsabilité et la future normalisation.

---

## Cadre de contribution

L’Observatoire fonctionne selon un cadre de contribution léger pour le cycle exploratoire allant de juin à décembre 2026.

### Version de référence

- [Version française de référence — Esprit NeoMundi & cadre de contribution v1.0](./governance/esprit-neomundi-cadre-contribution-v1.0-fr.md)

### Traductions de courtoisie

- [Version anglaise — NeoMundi Spirit & Contribution Framework v1.0](./governance/neomundi-spirit-contribution-framework-v1.0-en.md)
- [Version espagnole — Marco de contribución y espíritu NeoMundi v1.0](./governance/marco-contribucion-espiritu-neomundi-v1.0-es.md)
- [Version arabe — Esprit NeoMundi & cadre de contribution v1.0](./governance/esprit-neomundi-cadre-contribution-v1_0-ar.md)
- [Version ewe — NeoMundi Contribution Charter EWE v1.0](./governance/NeoMundi_Contribution_Charter_EWE_v1.0.md)

La version française est la version de référence. Les traductions présentées ici sont des contributions linguistiques produites ou relues par des locuteurs natifs engagés auprès de l’Observatoire.

Elles sont publiées comme le symbole d’une infrastructure scientifique ouverte, multilingue et internationale, dans laquelle la diversité linguistique contribue à la construction d’un cadre commun.

> **La technologie ne suffit pas. La langue, la culture et le sens partagé font partie de l’infrastructure.**

### Annexe A — Cadre de contribution indépendante

- [Version française — Engagement de contribution indépendante v0.1](./governance/annexe-a-engagement-contribution-independante-v0.1-fr.md)
- [Version anglaise — Independent Contribution Framework v0.1](./governance/annex-a-independent-contribution-framework-v0.1-en.md)

Cette annexe complète « Esprit NeoMundi & cadre de contribution » et définit les conditions applicables aux contributeurs, relecteurs, pairs méthodologiques, experts et contributeurs infrastructure participant à l’Observatoire IA NeoMundi.

---

## Contribuer

NeoMundi Recherche accueille des contributions portant notamment sur :

- la méthodologie et la conception de protocoles ;
- l’analyse de données ;
- la métrologie ;
- la gouvernance des IA ;
- la revue juridique, éthique et réglementaire ;
- la revue scientifique ;
- la documentation technique ;
- les infrastructures et l’interopérabilité ;
- la rédaction, la traduction et la pédagogie ;
- la recherche d’intérêt général ;
- les partenariats et le développement institutionnel.

Le cycle actuel de contribution est exploratoire, bénévole et limité dans son périmètre.

Avant de proposer une contribution, merci de consulter le cadre de contribution.

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

Le cadre de contribution NeoMundi s’est en partie inspiré de la Governance Participation Discipline v0.1 et du Collaborative Participation Framework v0.1 publiés par James Aull / MagicianzCardstock LLC.

[Governance Participation Discipline](https://github.com/magicianzcardstockllc/governance-participation-discipline)

Cette référence externe constitue un garde-fou utile en matière de contribution, d’attribution, de non-extraction et de limites d’autorité.

Elle ne place pas NeoMundi sous l’autorité de ce cadre et ne crée aucune dépendance institutionnelle.

Des informations complémentaires sur les références externes de gouvernance et les contributeurs peuvent être documentées dans le répertoire [`governance`](./governance/).

---

## Rôle du dépôt

Ce dépôt constitue le point d’entrée public de l’Observatoire IA NeoMundi.

Il contient :

- la mission et les principes de mesure de l’Observatoire ;
- des accès directs aux programmes publics récurrents ;
- le cadre de contribution ;
- les documents de gouvernance et d’orientation ;
- les supports d’intégration des contributeurs ;
- les liens vers les éléments de preuve publics et les dépôts dédiés ;
- les informations relatives au programme de stations distribuées ;
- les informations relatives au programme institutionnel et de normalisation.

Les datasets détaillés, scripts, méthodologies, publications et artefacts techniques sont publiés dans les dépôts propres à chaque programme.

---

## Liens NeoMundi

- **Site officiel — français :** [neomundi.org](https://neomundi.org)
- **Site officiel — anglais :** [neomundi.org/en/home](https://neomundi.org/en/home)
- **Baromètre hebdomadaire des IA :** [github.com/neomundi-io/NeoMundi-Weekly-Barometer](https://github.com/neomundi-io/NeoMundi-Weekly-Barometer)
- **Cartographie mensuelle du comportement des IA :** [github.com/neomundi-io/ai-behavior-cartography](https://github.com/neomundi-io/ai-behavior-cartography)
- **Cadre des stations distribuées :** [github.com/neomundi-io/neomundi-distributed-stations](https://github.com/neomundi-io/neomundi-distributed-stations)
- **Démonstration ControlTower :** [controltower.neomundi.io/welcome](https://controltower.neomundi.io/welcome)
- **Organisation GitHub :** [github.com/neomundi-io](https://github.com/neomundi-io)
- **Cadre théorique — Law E :** [DOI 10.5281/zenodo.19385052](https://doi.org/10.5281/zenodo.19385052)
- **From AI Observability to Governance Metrology :** [DOI 10.5281/zenodo.21250268](https://doi.org/10.5281/zenodo.21250268)
- **Contact :** [contact@neomundi.org](mailto:contact@neomundi.org)

Pour les cas d’usage industriels, la mesure runtime, les programmes pilotes, l’interopérabilité ou les échanges relatifs à ControlTower, merci de contacter directement NeoMundi.

---

## Écosystème et soutien infrastructure

L’Observatoire IA NeoMundi développe ses travaux au sein d’un écosystème ouvert de contributeurs techniques, scientifiques, institutionnels et infrastructure.

### Soutien infrastructure

L’Observatoire est soutenu par des partenaires d’infrastructure souveraine, notamment Infomaniak.

<img src="logos/ecosystem/logo_infomaniak.png"
     alt="Infomaniak"
     width="150">

### NVIDIA Inception

NeoMundi est membre du programme NVIDIA Inception.

<img src="https://raw.githubusercontent.com/neomundi-io/neomundi-sandbox/main/nvidia-inception-program-badge-rgb-for-screen.png"
     alt="NeoMundi is a member of the NVIDIA Inception program"
     width="180">

Ces relations soutiennent le développement et l’exploitation de capacités indépendantes de mesure des IA, d’auditabilité et de gouvernance runtime.

Elles n’impliquent aucune approbation des résultats de recherche, des mesures, des méthodologies ou des interprétations de l’Observatoire par les organisations mentionnées.

© 2025 NVIDIA, le logo NVIDIA et NVIDIA Inception sont des marques commerciales ou déposées de NVIDIA Corporation aux États-Unis et dans d’autres pays.

---

## Licence

Ce dépôt utilise actuellement la [licence Apache 2.0](LICENSE).

Certains jeux de données, rapports, traductions, composants logiciels ou contributions externes peuvent être soumis à des licences ou mentions complémentaires lorsque cela est nécessaire.
