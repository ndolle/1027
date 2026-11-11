Je comprends. La colonne « Enablement Required » donne effectivement l'impression qu'une équipe externe sollicite des ressources auprès de BNP Paribas.

Or, Octopus est une initiative interne, portée par des collaborateurs qui connaissent déjà les capacités, les contraintes et l'organisation de la banque.

Il faut donc adopter une posture différente : nous ne demandons pas à la banque de nous fournir des moyens ; nous expliquons comment nous allons mobiliser intelligemment les capacités de notre environnement.

Je proposerais de repositionner la slide comme suit.

## Project Octopus — Enterprise Capability Alignment

Building Octopus within the existing enterprise technology and governance ecosystem.

| Capability Area          | Existing Enterprise Capabilities                                               | Octopus Implementation Approach                                                                                             |
| ------------------------ | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Intelligence Sources     | Silobreaker, existing intelligence subscriptions and approved external sources | Prioritise existing intelligence services and APIs; complement coverage only where gaps are identified.                     |
| Enterprise AI            | Internal LLM and approved AI services                                          | Route analysis and summarisation through internal AI; optimise processing and minimise unnecessary external AI consumption. |
| Infrastructure           | Approved enterprise application and container hosting                          | Deploy Octopus using established hosting and operational standards.                                                         |
| Data & Integration       | Enterprise connectors, internal reference data and available data services     | Establish reusable intelligence datasets and integrate relevant business reference information.                             |
| Security & Governance    | Existing security, data protection and AI governance frameworks                | Embed enterprise controls into intelligence workflows from design through production.                                       |
| Engineering & Operations | Internal development expertise, platform services and operational practices    | Adopt existing engineering standards and operational processes, with targeted development of Octopus-specific capabilities. |

## Une autre amélioration que je recommande

Je remplacerais également le titre « Enterprise Capability Alignment » par quelque chose de plus naturel dans une présentation interne :

Project Octopus — Technology & Capability Strategy

Ce titre répond directement à la question initiale du management : What tools are we going to use?

Mais plutôt que de présenter une liste de produits techniques, nous exposons les principes de choix et d'utilisation des technologies.

Je structurerais la slide autour de trois principes :

REUSE FIRST

Prioritise approved enterprise platforms, tools and existing investments.

INTEGRATE BY DESIGN

Connect existing capabilities through approved APIs and common intelligence workflows.

BUILD SELECTIVELY

Develop only the orchestration, knowledge-sharing and correlation capabilities not already available.

### Message de conclusion

> Octopus will be developed as part of the existing enterprise ecosystem, following established technology standards and extending capabilities only where required.

### Une réflexion supplémentaire

Nous devons aussi faire attention à ne pas transformer Octopus en un projet qui semble dépendre de nombreuses validations et équipes avant de pouvoir commencer.

Pour un projet interne, je distinguerais :

- Ce que nous maîtrisons déjà : les cas d'usage, les besoins métier, les prototypes et les méthodes d'analyse.
- Ce que nous pouvons réutiliser : Silobreaker, le LLM interne, l'hébergement et les mécanismes d'intégration approuvés.
- Ce qui reste à concevoir : l'orchestration commune, le modèle de données partagé, la corrélation interservices et les interfaces métier.

Ma préférence serait donc de remplacer le tableau initial par ces trois catégories, avec quelques exemples concrets sous chacune.

Cela donnerait une slide moins administrative, plus stratégique et surtout plus représentative d'une initiative développée au sein de la banque, par ses propres équipes et à partir de ses capacités existantes.
