# WordPress et WooCommerce MCP : Abilities API et assistants IA

Présentation des interventions Allaux pour connecter WordPress et WooCommerce à un assistant compatible MCP, avec des fonctions adaptées au site et à ses extensions.

Développement et intégration par **[Emre Ucak — Allaux](https://allaux.fr/a-propos)**.

## Architecture et périmètre

L’Abilities API décrit les actions du site et leurs droits. Le MCP Adapter les expose à un client compatible. L’intervention vérifie les fonctions disponibles dans les versions installées et complète les abilities lorsque les extensions métier ne couvrent pas le besoin.

- Consultation du catalogue et des commandes selon les droits accordés.
- Développement d’abilities avec entrées, sorties et contrôles d’accès.
- Exposition des seules fonctions nécessaires à l’assistant.
- Recette des outils et documentation de la révocation des accès.

Cette page présente une intégration sur mesure, pas une extension à télécharger depuis ce dépôt. Les possibilités exactes dépendent des versions de WordPress, WooCommerce et de l’adapter.

## Ressources

- [WordPress et WooCommerce MCP](https://allaux.fr/wordpress-woocommerce/mcp)
- [Développement WordPress et WooCommerce](https://allaux.fr/wordpress-woocommerce)
- [Serveur MCP pour boutique](https://allaux.fr/expertises/serveur-mcp-boutique-pilotable)
- [MCP PrestaShop](https://allaux.fr/prestashop/mcp)

## Contrôles d’intégration

| Élément | Vérification |
|---|---|
| Ability | Description, schémas d’entrée et sortie, contrôle des droits |
| Adapter | Exposition des abilities nécessaires au client MCP |
| WooCommerce | Correspondance entre les outils et les objets produit/commande |
| Extension métier | Fonctions absentes à développer explicitement |
| Client IA | Authentification et réponses vérifiables |

Une demande de lecture de commande ne doit pas donner implicitement le droit de la modifier. La découverte des fonctions, leur exécution et les autorisations du compte sont vérifiées séparément.

## Présentation publique

Ce dépôt contient une présentation technique. Les sources, les accès et les données clients restent privés. Pour étudier une adaptation à votre contexte, indiquez vos outils existants, les échanges de données attendus et les contraintes d’exploitation.

## Contact

**Emre Ucak — Allaux**, développeur indépendant depuis 2019.

- [contact@allaux.fr](mailto:contact@allaux.fr)
- [WhatsApp : +33 6 21 86 33 28](https://wa.me/33621863328)
- [Décrire votre projet](https://allaux.fr/contact)
- [allaux.fr](https://allaux.fr/)
