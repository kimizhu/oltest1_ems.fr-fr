---
description: na
keywords: na
title: FastTrack Center Benefit Process for Azure Active Directory Premium 
search: na
ms.date: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: f1e8d94d-ce42-4d4c-a25b-0f28b93a9e10
---
# Processus de l’offre du Centre FastTrack pour Azure Active Directory Premium 
Si votre organisation est éligible à l’intégration de l’offre du centre FastTrack pour Microsoft Azure AD Premium, vous pouvez travailler à distance avec des spécialistes Microsoft pour préparer votre environnement Microsoft Azure AD Premium. Pour savoir si votre organisation est éligible, consultez [Offre du Centre FastTrack pour Azure Active Directory Premium](../Topic/FastTrack_Center_Benefit_for_Azure_Active_Directory_Premium.md).

Cet article fournit les informations suivantes :

-   [Overview of the onboarding process](#overview)

-   [Expectations for your source environment](#expectations_src_environ)

-   [Phases of the onboarding process](#phases_onboarding_process)

-   [Microsoft responsibilities](#microsoft_responsibilities) pour chaque phase

-   [Your responsibilities](#your_responsibilities) pour chaque phase

Voici ce à quoi vous pouvez vous attendre quand l'intégration est terminée :

-   Votre client Microsoft Azure AD Premium est créé.

-   Les titulaires d’une licence d’utilisation peuvent accéder aux services Microsoft Azure AD Premium à l’aide de l’une des options d’identité suivantes :

    -   Identités de cloud (comptes Microsoft Azure AD Premium uniques).

    -   Identités synchronisées : comptes Microsoft Azure AD Premium synchronisés à partir de votre annuaire Active Directory local avec l’outil Azure Active Directory Connect (Azure AD Connect) pour les clients avec une seule forêt ou plusieurs forêts Active Directory.

    -   Identités fédérées avec des comptes Microsoft Azure AD Premium qui sont :

        -   synchronisés à partir d'Active Directory avec l'outil Microsoft Azure AD Connect pour les clients avec une configuration de forêt Active Directory unique ;

        -   fédérés avec Active Directory Federation Services (ADFS) 2.0 ou version ultérieure à partir de votre annuaire Active Directory local.

## <a name="overview"></a>Vue d'ensemble du processus d'intégration
L'intégration présente deux composants majeurs :

-   **Fonctionnalités principales** : tâches requises pour la configuration du client et l'intégration à Azure AD, si nécessaire. Les fonctionnalités principales fournissent également la base de référence pour l’intégration d’autres services éligibles de Microsoft Online.

-   **Intégration de service** : tâches nécessaires pour configurer Microsoft Azure AD Premium en mode autonome ou avec la synchronisation d'annuaires Azure AD Connect ou AD FS.

Le diagramme suivant décrit la chronologie de l’utilisation de l’offre du centre FastTrack.

![](../Image/1-rms_onboarding_process.png)

Le processus de base se présente comme suit :

-   Microsoft essaie de vous contacter dans les 30 jours suivant votre achat d’un plan éligible. Vous pouvez également demander de l’aide à partir du [Centre FastTrack](http://fasttrack.microsoft.com/) si vous êtes prêt à déployer ces services pour votre organisation. Pour demander de l’aide, connectez-vous au Centre FastTrack (http://fasttrack.microsoft.com), accédez au tableau de bord, sélectionnez le nom de votre entreprise, cliquez sur l’onglet Offres et sur le bouton de demande d’assistance pour le service éligible. Une fois que l'assistance en matière d'intégration débute, nous organisons un programme de réunions en ligne.

-   L’équipe Microsoft vous apporte son aide pour les fonctionnalités principales, puis pour l’intégration de chaque service éligible.

L'assistance en matière d'intégration est assurée à distance par le personnel désigné de Microsoft :

-   Microsoft vous aide à distance pour de nombreuses activités d'intégration, en utilisant une combinaison d'outils, de documentation et de conseils. Si vous souhaitez que Microsoft effectue certaines tâches de configuration pour vous, vous pouvez choisir de fournir un accès et des autorisations appropriés à Microsoft.

-   L'assistance en matière d'intégration est fournie par le centre FastTrack, et est disponible pendant les heures normales de bureau d'une région donnée.

-   Elle est disponible dans les langues suivantes : chinois traditionnel, anglais, français, allemand, italien, japonais, portugais (Brésil) ou espagnol.

-   L’équipe Microsoft peut travailler directement avec vous ou votre représentant.

## <a name="expectations_src_environ"></a>Attentes concernant votre environnement source
Si vous avez Microsoft Active Directory en local dans votre environnement source, vous pouvez l’intégrer à Microsoft Azure AD Premium pour optimiser la gestion des identités à partir d’une seule console. L’offre du centre FastTrack comprend une assistance à l’intégration de Microsoft Azure AD Premium à votre implémentation locale existante. Si l'intégration est nécessaire, votre environnement source doit être à un niveau minimal pour cette application.

Le tableau suivant indique les conditions attendues dans votre environnement source existant pour l'intégration.

|Activité|Attente concernant l'environnement source|
|------------|---------------------------------------------|
|Fonctionnalités principales|Forêts Active Directory avec le niveau de forêts fonctionnel défini sur Windows Server 2008 ou version ultérieure, avec la configuration de forêts suivante :<br /><br />-   Forêt Active Directory unique<br />-   Plusieurs forêts Active Directory **Note:** Pour toutes les configurations à plusieurs forêts, le déploiement AD FS n’entre pas dans le cadre de l’offre du centre FastTrack.|
|Intégration de service<br /><br />-   Microsoft Azure AD Premium|L'annuaire Active Directory et l'environnement locaux ont été préparés pour Azure AD Premium, ce qui inclut la correction des problèmes identifiés susceptibles d'empêcher l'intégration aux fonctionnalités Azure AD et Azure AD Premium.|

## <a name="phases_onboarding_process"></a>Phases du processus d'intégration
L'intégration de Microsoft Azure AD Premium comporte cinq phases principales, comme illustré dans la figure suivante :

-   Initier

-   Évaluer

-   Corriger

-   Activer

-   Fermer

![](../Image/2-aadp_onboarding_phases-v3.png)

Pour connaître les tâches détaillées pour chaque phase, consultez les sections [Microsoft responsibilities](#microsoft_responsibilities) et [Your responsibilities](#your_responsibilities).

### Phase de lancement
Après avoir acheté le nombre approprié de licences, suivez la procédure figurant dans l’e-mail de confirmation d’achat pour associer ces licences à votre client existant ou à un nouveau client. Microsoft vérifie votre éligibilité à l’offre du centre FastTrack. Microsoft essaie de vous contacter dans les 30 jours suivant votre achat d’un plan éligible. Vous pouvez également demander de l’aide à partir du [Centre FastTrack](http://fasttrack.microsoft.com/) si vous êtes prêt à déployer ces services pour votre organisation. Pour demander de l’aide, connectez-vous au Centre FastTrack (http://fasttrack.microsoft.com), accédez au tableau de bord, sélectionnez le nom de votre entreprise, cliquez sur l’onglet Offres et sur le bouton de demande d’assistance pour le service éligible. Une fois que l'assistance en matière d'intégration débute, nous organisons un programme de réunions en ligne.

Pendant cette phase, nous aborderons le processus d'intégration, vérifierons les données et organiserons une réunion de lancement.

![](../Image/Microsoft_Azure_AD_Premium_initiate_phase_1.png)

### Phase d'évaluation
Une fois le processus d'intégration démarré, Microsoft travaillera avec vous pour évaluer votre environnement source et les conditions requises. Des outils seront exécutés afin d'évaluer votre environnement et Microsoft vous guidera tout au long de l'évaluation de votre annuaire Active Directory local, de vos navigateurs Internet, des systèmes d'exploitation des appareils clients, de votre service DNS, de votre réseau, de votre infrastructure et de votre système d'identité, afin de déterminer si des changements sont nécessaires pour l'intégration. En fonction de votre configuration actuelle, nous vous fournirons un plan de correction qui adaptera votre environnement source aux conditions minimales requises pour la réussite de l'intégration à Microsoft Azure AD Premium. Nous mettrons également en place des appels de point de contrôle appropriés pour la phase de correction.

![](../Image/Microsoft_Azure_AD_Premium_assess_phase_v6.png)

### Phase de correction
Si nécessaire, vous effectuerez les tâches figurant dans le plan de correction dans votre environnement source de façon à pouvoir remplir les conditions requises pour l'intégration de chaque service.

![](../Image/Microsoft_Azure_AD_Premium_remediate_phase_1.png)

Avant de commencer la phase d'activation, nous vérifierons ensemble les résultats des activités de correction pour nous assurer que vous pouvez continuer.

### Phase d'activation
Une fois toutes les activités de correction terminées, le projet passe à la configuration de l'infrastructure de base pour la consommation de services et à l'approvisionnement de Microsoft Azure AD Premium.

**Phase d'activation - Fonctionnalités principales**

L'activation des fonctionnalités principales implique l'approvisionnement de services et l'intégration du client et de l'identité. Elle comprend également des étapes de création d'une base pour l'intégration de Microsoft Azure AD Premium.

L'intégration de Microsoft Azure AD Premium peut commencer quand l'intégration de base est terminée.

**Phase d’activation de Microsoft Azure AD Premium**

L’environnement Microsoft Azure AD Premium peut être configuré, si nécessaire, avec la synchronisation d’annuaires Azure AD Connect et les services AD FS (Active Directory Federation Services).

Pour les scénarios Microsoft Azure AD Premium qui incluent la synchronisation des identités locales vers le cloud, nous vous aiderons en ajoutant des utilisateurs et des administrateurs informatiques à votre abonnement, en validant vos principaux cas d'usage pour le service, ainsi qu’en configurant l'environnement de gestion minimal, Microsoft Azure AD Premium, la synchronisation d'annuaires à l'aide d'Azure AD Connect, les services AD FS (Active Directory Federation Services) à l'aide d'Azure AD Connect et des utilisateurs de test.

Le programme d'installation de Microsoft Azure AD Premium inclut l'activation des fonctions suivantes :

-   Réinitialisation du mot de passe libre-service

-   Azure Multi-Factor Authentication (MFA)

-   Application SaaS (Software as a Service) : configurer une application SaaS

-   Gestion de groupes en libre-service

-   Rapports d'administration

![](../Image/Microsoft_Azure_AD_Premium_enable_phase_2.png)

## <a name="microsoft_responsibilities"></a>Responsabilités de Microsoft

### Général

-   Nous vous offrirons une assistance technique à distance pour les activités de configuration obligatoires, comme décrit dans les descriptions détaillées des phases.

-   Nous fournirons la documentation disponible et les outils logiciels, les consoles d'administration ainsi que des scripts pour vous aider à réduire ou éliminer les tâches de configuration.

Vous n’avez pas besoin de fournir un accès et des autorisations à Microsoft pour utiliser l’offre du centre FastTrack. Dans certains cas, vous pouvez choisir d'octroyer à Microsoft l'accès et les autorisations appropriés pour qu'il effectue des actions spécifiques à votre place.

### Phase de lancement

-   Vous contacter dans les 30 jours suivant l'achat de licences éligibles pour un nouveau client.

-   Collaborer avec vous pour commencer l'intégration dans les 90 jours suivant l'achat de licences éligibles.

-   Définir les services éligibles que vous souhaitez intégrer.

### Phase d'évaluation

-   Fournir un aperçu administratif.

-   Fournir des conseils à propos des éléments suivants :

    -   DNS, réseau et besoins en infrastructure.

    -   Besoins du client (navigateur Internet, système d'exploitation client et besoins des services).

    -   Identité utilisateur et approvisionnement.

    -   Identification des besoins en termes de synchronisation d'annuaires.

    -   Évaluation de la synchronisation de hachage de mot de passe par rapport aux objectifs du client ou de la nécessité d'utiliser AD FS.

    -   Activation des services éligibles qui ont été achetés et définis comme faisant partie de l'intégration.

    -   Identification des spécifications requises en termes d’environnement de pilotage et de test, par exemple, comptes de test, instances de test des applications SaaS (par exemple, SalesForce).

-   Établir la chronologie des activités de correction.

-   Fournir une liste de contrôle de correction.

### Phase de correction

-   Tenir des téléconférences avec vous en fonction du calendrier convenu, afin d'examiner la progression des activités de correction.

-   Vous aider à exécuter des outils permettant d'identifier et de résoudre les problèmes, et vous aider à interpréter les résultats.

### Phase d'activation
Fournir des conseils à propos des éléments suivants :

-   Activation de votre client Microsoft Azure AD Premium.

-   Configuration des ports de pare-feu.

-   Configuration du service DNS pour les services éligibles.

-   Validation de la connectivité aux services Microsoft Azure AD Premium.

-   Pour un environnement à forêt unique :

    -   Installation d'une synchronisation d'annuaires entre vos services de domaine Active Directory et Azure AD Connect, si nécessaire.

    -   Configuration de la synchronisation de mot de passe avec l'outil Azure AD Connect.

-   Pour un environnement à plusieurs forêts :

    -   Installation de la synchronisation d'Azure AD Connect, pour des scénarios à plusieurs forêts. Notez que l'écriture différée de mot de passe et la synchronisation de hachage de mot de passe prennent en charge les scénarios à plusieurs forêts.  Toutefois, les autres scénarios d'écriture différée ne sont pas pris en charge.

    -   Configuration de la synchronisation entre les forêts Active Directory locales et l'annuaire Microsoft Azure AD Premium (Azure Active Directory).

        > [!NOTE]
        > Le développement et l'implémentation des extensions de règles personnalisées sont hors de portée.

-   Pour une forêt unique quand des identités fédérées sont ciblées : installation et configuration des services AD FS (Active Directory Federation Services) pour l’authentification de domaine local avec Microsoft Azure AD Premium dans une configuration avec un seul site et à tolérance de panne, si nécessaire.

    > [!NOTE]
    > Pour toutes les configurations à plusieurs forêts, les déploiements AD FS sont hors de portée.

-   Test de la fonctionnalité d'authentification unique, si elle est déployée.

#### Phase d'activation - Azure AD Premium avec Azure AD Connect et AD FS
Fournir des conseils pour la configuration des éléments suivants :

-   Approvisionnement utilisateur, y compris la gestion des licences

-   Synchronisation d'annuaires Azure AD Connect (avec écriture différée de mot de passe et synchronisation de hachage de mot de passe).

-   Services de fédération Active Directory (AD FS)

-   Réinitialisation du mot de passe libre-service

-   Azure Multi-Factor Authentication (MFA)

-   Une application intégrée, qui peut comprendre l’authentification unique pour les applications SaaS.

-   Rapports d'utilisation et de sécurité pour les administrateurs

-   Gestion de groupes en libre-service

-   Proxy d'application

-   Notifications à l'administrateur

-   Écran de connexion personnalisé, y compris le logo, le texte et les images

## <a name="your_responsibilities"></a>Vos responsabilités
Cette section décrit certaines de vos responsabilités au cours du processus d'intégration.

### Général

-   Toutes les améliorations et intégrations de votre client Microsoft Azure AD Premium en plus des options configurables répertoriées dans cet article.

-   Gestion globale des projets et des programmes concernant vos ressources.

-   Communications avec l'utilisateur final, documentation, formation et gestion des modifications.

-   Documentation et formation destinées au support technique.

-   Production de rapports, présentations ou comptes rendus de réunion spécifiques à votre organisation.

-   Création de documentation architecturale et technique spécifique à votre organisation.

-   Conception, approvisionnement, installation et configuration du matériel et de la mise en réseau.

-   Approvisionnement, installation et configuration de logiciels.

-   Gestion, configuration et application de stratégies de sécurité en plus de celles créées pour tester vos fonctionnalités et configuration de ligne de base des services Microsoft Azure AD Premium.

-   Inscription de comptes d'utilisateur en plus de ceux utilisés pour tester les fonctionnalités et la configuration de ligne de base des services Microsoft Azure AD Premium.

-   Configuration, analyse, validation de la bande passante, test et surveillance du réseau.

-   Gestion d'un processus d'approbation de gestion des modifications techniques et création de la documentation associée.

-   Modification de votre modèle opérationnel et des guides d'utilisation.

-   Configuration de l'authentification multifacteur en local.

-   Désaffectation et suppression des services et des environnements sources précédemment utilisés par le client.

-   Construction et maintenance de votre environnement de test.

-   Installation de Service Packs et d'autres mises à jour obligatoires sur les serveurs d'infrastructure.

-   Fourniture et configuration de tous les certificats SSL publics.

-   Rédaction des conditions d'utilisation de l'organisation à configurer et à afficher sur les appareils des utilisateurs finaux.

### Phase de lancement

-   Travailler avec l’équipe Microsoft pour commencer l’intégration des services éligibles.

-   Participer à la réunion de lancement, gérer et diriger les participants de votre organisation, et confirmer la chronologie des corrections.

### Phase d'évaluation

-   Identifier les parties prenantes appropriées (dont un chef de projet) pour effectuer les activités d'évaluation nécessaires.

-   Si vous le souhaitez, partager votre écran avec Microsoft si vous avez besoin de conseils lors de l’exécution des outils d’évaluation dans votre environnement ou votre abonnement Microsoft Azure AD Premium.

-   Participer aux réunions pour la création de la liste de contrôle de correction et contribuer au plan global, y compris sur des sujets tels que l'infrastructure, le réseau, l'administration, la préparation de la synchronisation d'annuaires, la sécurité du réseau et les identités fédérées.

-   Participer aux réunions pour définir l'approche d'approvisionnement utilisateur.

-   Participer aux réunions pour planifier la configuration du service en ligne.

-   Créer un plan de prise en charge pour la préparation à la migration.

### Phase de correction

-   Exécuter les étapes obligatoires pour effectuer les activités de correction identifiées durant la phase d'évaluation.

-   Participer aux réunions de point de contrôle.

### Phase d'activation

-   Si vous le souhaitez, partagez votre écran avec Microsoft si vous avez besoin de conseils pour modifier votre environnement ou votre abonnement à Microsoft Azure AD Premium.

-   Gérer les ressources de manière appropriée.

-   Configurer les éléments liés au réseau selon les recommandations de Microsoft.

-   Effectuer la préparation des annuaires et configurer la synchronisation d'annuaires selon les recommandations de Microsoft.

-   Configurer les éléments d'infrastructure liés à la sécurité (tels que les ports de pare-feu) selon les recommandations de Microsoft.

-   Implémenter l'infrastructure cliente appropriée.

-   Implémenter une approche d'approvisionnement utilisateur selon les recommandations de Microsoft.

-   Activer divers services selon les recommandations de Microsoft.

## Vous souhaitez en savoir plus ?
Consultez [Microsoft Azure Active Directory](http://azure.microsoft.com/en-us/documentation/services/active-directory/) et [Enterprise Mobility Suite](http://www.microsoft.com/en-us/server-cloud/products/enterprise-mobility-suite/default.aspx).

