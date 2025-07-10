# ml-in-the-clouds

## Veille 
### L’AutoML et ses avantages
L’AutoML (Automated Machine Learning) révolutionne le développement de modèles en automatisant les tâches clés du pipeline de machine learning, comme la sélection de modèles, l’optimisation des hyperparamètres et le prétraitement des données. Cette automatisation permet de gagner un temps précieux tout en améliorant la performance des modèles, notamment dans les phases de prototypage rapide ou dans les contextes où les ressources en data science sont limitées. Les outils AutoML, comme ceux proposés par Google, H2O.ai ou DataRobot, rendent aussi la science des données accessible à un public non technique via des interfaces no-code ou low-code. En résumé, AutoML favorise une meilleure productivité, réduit la complexité technique et permet une plus grande démocratisation du machine learning.

### Le MLaaS et ses avantages
Le MLaaS repose sur une logique similaire au SaaS, en fournissant des outils d’intelligence artificielle via le cloud. Ces services proposent une infrastructure clé en main pour le stockage, l’entraînement, le déploiement et la gestion de modèles. Des plateformes comme Amazon SageMaker, Azure ML ou Google Vertex AI offrent ainsi une grande scalabilité, de la flexibilité tarifaire (facturation à l’usage), et une intégration simplifiée avec les autres services cloud. Les entreprises peuvent ainsi éviter les coûts liés à la mise en place d’une infrastructure locale, tout en profitant de services puissants comme l'inférence temps réel, le déploiement automatisé ou la surveillance des performances. C’est une solution particulièrement adaptée aux start-ups et aux PME qui veulent accélérer le développement IA sans recruter une équipe dédiée.

### Google Cloud Platform et Vertex AI
Vertex AI est une plateforme de machine learning unifiée proposée par Google Cloud. Elle permet aux entreprises de construire, entraîner et déployer des modèles d’IA et de ML de manière plus efficace.
#### Fonctionnalités Clés
- AutoML : Permet de créer des modèles sans coder.
- Custom Training : Pour les experts souhaitant personnaliser leurs modèles.
- Pipeline d’IA : Automatisation des workflows ML.
- Modèles pré-entraînés : Accès à des modèles optimisés pour la vision, le NLP, etc.
- Intégration avec Google Cloud : Utilisation de BigQuery, Dataflow et autres services.

### AWS et Sagemaker
SageMaker est la plateforme ML d’AWS la plus mature sur le marché. Elle permet de gérer tout le cycle de vie machine learning avec une approche modulaire : création de notebooks, gestion des pipelines (via SageMaker Pipelines), labelling automatisé (GroundTruth), ou encore Feature Store intégré. Son principal avantage réside dans son intégration parfaite avec l’écosystème AWS (S3, Glue, IAM…), ce qui en fait un choix logique pour les entreprises déjà implantées sur ce cloud. En plus, des outils récents permettent le tuning automatique des modèles et des solutions basées sur les fondations de l’IA générative. Des grandes banques comme JPMorgan ou Bridgewater utilisent SageMaker dans leurs pipelines IA. Toutefois, son interface peut sembler technique pour les débutants, et la facturation à l’usage peut rapidement grimper en fonction des besoins.

### Azure et Azure Machine Learning
Azure Machine Learning offre un bon équilibre entre puissance et accessibilité. La plateforme propose une interface graphique intuitive via Azure ML Studio, couplée à un environnement complet pour les développeurs Python ou R. Elle met l'accent sur le MLOps, avec un fort support des pipelines, de la gestion des versions de modèles, de la surveillance, et de l’intégration CI/CD avec GitHub Actions ou Azure DevOps. De nombreuses entreprises l’utilisent pour accélérer la mise en production des modèles, comme Marks & Spencer qui a amélioré son ciblage marketing grâce à cette plateforme. Azure ML s’intègre aussi parfaitement à l’environnement Microsoft (Power BI, Azure Synapse…), ce qui en fait une solution très attractive pour les entreprises déjà familières avec l’écosystème.

### DataRobot
DataRobot propose une approche différenciante centrée sur l’accessibilité et l’accompagnement. Très axée AutoML, la plateforme permet aux entreprises de construire, entraîner et déployer des modèles prédictifs en quelques clics. Ce qui distingue DataRobot, c’est son support expert intégré, ses workshops d’accompagnement, et une communauté active avec des bibliothèques d’accélérateurs prêts à l’emploi. En 2025, DataRobot mise aussi fortement sur l’IA générative avec une plateforme unifiée permettant la création d’agents intelligents, d’applications conversationnelles et de workflows automatisés. Elle s’adresse particulièrement aux entreprises qui veulent adopter l’IA rapidement avec un partenaire technologique solide, sans recruter d’équipe spécialisée en interne.