# Conditions Générales d'Utilisation — Supernova Bot

**Dernière mise à jour :** 14 novembre 2026
**Support officiel :** https://discord.gg/NUFRRmHKKZ

---

## Préambule

Les présentes Conditions Générales d'Utilisation (ci-après « CGU ») régissent l'accès et l'utilisation du bot Discord Supernova (ci-après « le Bot »), développé et maintenu par son propriétaire (ci-après « l'Owner »).

En invitant le Bot sur votre serveur Discord ou en utilisant l'une de ses commandes, vous acceptez sans réserve l'intégralité des présentes CGU. Si vous n'acceptez pas ces conditions, vous devez cesser immédiatement toute utilisation du Bot et le retirer de vos serveurs.

---

## Article 1 — Description du service

Supernova est un bot Discord offrant les fonctionnalités suivantes :

**1.1 Système de modération**
- Suivi des suspects et des comportements signalés
- Exécution de sanctions (ban, kick) en cas de nécessité

**1.2 Système anti-raid automatique**
- Détection et sanction automatique des comportements malveillants
- Détection du spam de messages et suppression des webhooks suspects
- Détection des actions massives et destructrices sur un serveur
- Journalisation de toutes les alertes dans un salon dédié
- Prise en charge et suivi des incidents par le staff

**1.3 Système de whitelist et de blacklist**
- Exemption de certains utilisateurs des protections anti-raid
- Blocage permanent d'utilisateurs blacklistés
- Blocage d'ajout du Bot à des serveurs

**1.4 Système d'alertes SOS et RAID**
- Signalement d'urgence à l'équipe staff du bot
- Suivi de la prise en charge et de la résolution par un membre du staff Bot

**1.5 Commandes générales**
- Informations sur le Bot (`s!botinfo`, `s!ping`)
- Aide (`s!help`, `/help`)

**1.6 Panneau propriétaire (Owner Panel)**
- Gestion avancée des serveurs hébergeant le Bot
- Commandes réservées exclusivement à l'Owner du Bot

**1.7 Fonctionnalités d'intelligence artificielle**
- Le Bot intègre une IA fournie par un prestataire tiers (Groq)
- Les réponses sont générées automatiquement et peuvent être inexactes, incomplètes ou inappropriées

---

## Article 2 — Conditions d'accès et hiérarchie des permissions

**2.1** Le Bot est accessible à tout serveur Discord disposant des permissions nécessaires pour l'inviter.

**2.2** L'utilisation des commandes est soumise à la hiérarchie suivante :

### Niveau 1 — Owner du Bot (commandes `o!`)

L'Owner du Bot bénéficie d'un accès total et inconditionnel. Il est exempté de toutes les protections anti-raid et de toutes les restrictions de modération, sans exception.

Capacités exclusives de l'Owner :
- Sanctionner (ban, kick) un utilisateur sur un serveur hébergeant le Bot, uniquement avec l'autorisation préalable du propriétaire du serveur (ou d'un administrateur désigné par lui), obtenue via le Bot. L'urgence justifie de demander cette autorisation, jamais de s'en passer.
- S'attribuer un rôle administrateur sur un serveur, uniquement après validation explicite du propriétaire ou d'un administrateur du serveur via les boutons Accepter/Refuser du Bot. Chaque action est journalisée et le rôle est retiré à la fin de l'intervention.
- Consulter la liste des serveurs hébergeant le Bot (nom et ID).
- Gérer la whitelist et la blacklist globales.

### Niveau 1B — Co-Owner du Bot

Le Co-Owner est désigné manuellement par l'Owner. Il assiste l'Owner dans la gestion de la sécurité du Bot.

Capacités du Co-Owner :
- Gérer la blacklist globale (ajout, retrait) selon les critères de l'article 5.1 bis de la Politique de Confidentialité.
- Il ne peut **pas** sanctionner ni s'attribuer de permissions sur un serveur sans l'autorisation de son propriétaire.

Chaque action du Co-Owner est journalisée et visible de l'Owner.

### Niveau 2A — Staff administrateur (sous-rang élevé)

Au sein de l'équipe staff, seuls certains membres disposent du rang Administrateur. Ce rang est attribué manuellement par l'Owner et n'est pas accordé à l'ensemble du staff.

Les staff administrateurs peuvent, dans le cadre d'une urgence avérée uniquement, s'attribuer les permissions administrateur via le Bot. Pour cela, ils doivent utiliser la commande dédiée en précisant une raison. La demande est publiée en mentionnant l'ensemble des rôles Administrateur du serveur ainsi que le propriétaire du serveur, et est soumise à validation via deux boutons (Accepter/Refuser) : seuls les administrateurs et le propriétaire du serveur/Bot concerné peuvent y répondre. Toute tentative d'un membre staff non-administrateur d'utiliser cette fonctionnalité est automatiquement refusée par le Bot. Les staffs ne peuvent pas utiliser les commandes de modération sans avoir de permission Discord préalable.

Important :
- Chaque demande est soumise à validation (boutons Accepter/Refuser) par un administrateur/le propriétaire du serveur, et chaque utilisation déclenche une alerte envoyée à l'Owner du Bot.
- Le staff administrateur doit lister l'ensemble des actions effectuées grâce à ces permissions dans le salon de logs.
- Le rôle Administrateur temporaire doit être supprimé par l'administrateur du Bot à la fin de l'intervention.
- Les staff administrateurs ne sont **pas** exemptés du système anti-raid. Les protections automatiques s'appliquent à eux comme à n'importe quel autre utilisateur.
- L'usage de cette fonctionnalité doit rester exceptionnel et strictement limité aux urgences.

### Niveau 2B — Staff standard (commandes `staff!`)

Les membres staff sans rang Administrateur ont accès aux commandes staff courantes (alertes, sos). Les staffs ne peuvent pas utiliser les commandes de modération sans avoir de permission Discord préalable. Ils ne peuvent **pas** s'attribuer de permissions administrateur : le Bot refuse explicitement cette action pour ce niveau. Ils ne sont **pas** exemptés du système anti-raid.

### Niveau 3 — Membres whitelistés

Les utilisateurs ajoutés à la whitelist par l'Owner sont exemptés des protections anti-raid automatiques, mais ne disposent d'aucun accès aux commandes staff ou owner.

### Niveau 4 — Membres généraux (commandes `s!`)

Accès aux commandes publiques uniquement : ping, botinfo, help, sos, raidalert, ia. Soumis à l'intégralité des protections anti-raid.

**2.3** L'accès à certaines fonctionnalités peut être suspendu ou révoqué à tout moment sans préavis, notamment en cas de violation des présentes CGU.

---

## Article 3 — Règles d'utilisation

**3.1 Utilisation loyale**
Vous vous engagez à utiliser le Bot conformément à son usage prévu et dans le respect des Conditions d'Utilisation de Discord (discord.com/terms).

**3.2 Comportements interdits**
Il est strictement interdit de :

- a) Tenter de contourner, désactiver ou manipuler le système anti-raid, la whitelist, la blacklist ou tout autre mécanisme de sécurité du Bot ;
- b) Utiliser le Bot pour mener, faciliter ou dissimuler un raid, une attaque ou toute action malveillante contre un serveur Discord ;
- c) Exploiter des failles ou bugs du Bot à des fins abusives ; tout bug découvert doit être signalé au support officiel ;
- d) Usurper l'identité de l'Owner ou du staff pour accéder à des commandes réservées ;
- e) Utiliser abusivement les commandes d'urgence (attribution de permissions administrateur) en dehors d'une situation d'urgence avérée ; cette fonctionnalité est réservée aux staff administrateurs et tout usage détourné est tracé et signalé à l'Owner ;
- f) Utiliser le Bot pour diffuser du contenu illégal, haineux, diffamatoire ou portant atteinte aux droits de tiers ;
- g) Automatiser l'envoi de commandes au Bot par des scripts ou bots tiers sans autorisation préalable de l'Owner ;
- h) Tester, simuler ou déclencher volontairement le système anti-raid ou les commandes d'urgence (SOS, RaidAlert) en dehors d'une situation réelle nécessitant leur usage, y compris à des fins de démonstration, de curiosité ou de vérification, sans autorisation explicite préalable de l'Owner ;
- i) Utiliser l'IA du Bot pour générer du contenu illégal, haineux ou malveillant, tenter de contourner ses restrictions (injection de prompt, jailbreak), ou en abuser par du spam de requêtes.

**3.3 Conséquences des violations**
Tout manquement aux présentes CGU peut entraîner, selon la gravité :
- Un avertissement (warn)
- Un bannissement temporaire ou permanent du serveur concerné
- L'ajout en blacklist globale du Bot
- Le retrait du Bot sur vos serveurs
- Le signalement aux équipes de Discord

---

## Article 4 — Système anti-raid et sanctions automatiques

**4.1** Le Bot intègre un système de protection automatique contre les raids et les comportements malveillants. Ce système agit de manière autonome, sans intervention humaine préalable, afin de protéger les serveurs en temps réel.

**4.2** En utilisant le Bot, vous acceptez que des sanctions automatiques (avertissements, bannissements...) puissent être appliquées à tout utilisateur dont le comportement est détecté comme malveillant ou potentiellement dangereux pour l'intégrité du serveur.

**4.3** Aucune catégorie d'utilisateurs — y compris les membres staff, qu'ils soient standards ou administrateurs — n'est exemptée de ces protections automatiques. Seuls l'Owner du Bot, le Co-Owner et les utilisateurs figurant explicitement sur la whitelist en sont exemptés.

**4.4** Chaque incident déclenché par le système anti-raid est consigné dans un journal d'alertes et notifié au staff du Bot, qui peut prendre en charge et résoudre l'alerte via les boutons interactifs du Bot.

**4.5** L'Owner du Bot décline toute responsabilité pour les sanctions automatiques effectuées de bonne foi par le système. Les administrateurs de serveur sont responsables de la configuration correcte de la whitelist afin d'éviter tout faux positif.

**4.6** Tout bannissement automatique peut faire l'objet d'un recours via le serveur de support : https://discord.gg/NUFRRmHKKZ

---

## Article 5 — Collecte et traitement des données

La collecte et le traitement des données (données collectées, blacklist globale, finalités, bases légales, durées de conservation, droits des utilisateurs) sont détaillés dans la **Politique de Confidentialité** du Bot, qui fait partie intégrante des présentes CGU.

---

## Article 6 — Responsabilités

**6.1 Responsabilité de l'Owner du Bot**
L'Owner s'engage à maintenir le Bot en état de fonctionnement dans la mesure du possible et à corriger les bugs signalés dans un délai raisonnable. L'Owner s'engage également à n'utiliser ses capacités étendues (sanctions, attribution de rôle administrateur) sur un serveur qu'avec l'autorisation préalable de son propriétaire ou d'un administrateur, et uniquement dans l'intérêt de la sécurité des serveurs. Aucune garantie de disponibilité continue n'est accordée.

**6.2 Responsabilité des administrateurs de serveur**
Les administrateurs qui invitent le Bot sur leur serveur sont responsables :
- De la configuration correcte des permissions accordées au Bot ;
- De la gestion de la whitelist pour éviter des sanctions involontaires ;
- Du respect des présentes CGU par les membres de leur serveur ;
- De l'attribution rigoureuse du rang Administrateur au sein du staff, ce rang conférant des capacités d'urgence étendues via le Bot.

**6.3 Responsabilité des staff administrateurs**
Les membres du staff disposant du rang Administrateur s'engagent à n'utiliser la fonctionnalité d'attribution de permissions que dans les cas d'urgence strictement nécessaires, sachant que chaque utilisation est tracée et signalée à l'Owner du Bot. Les staff standards ne disposant pas de ce rang ne peuvent pas accéder à cette fonctionnalité, le Bot refusant automatiquement toute tentative non autorisée.

**6.4 Limitation de responsabilité**
Le Bot est fourni « en l'état ». L'Owner ne saurait être tenu responsable :
- Des dommages indirects causés par une mauvaise configuration du Bot ;
- Des pertes de données liées à une interruption du service ;
- Des actions automatiques du système anti-raid effectuées de bonne foi ;
- Des interruptions de service liées à Discord ou à l'hébergeur ;
- Du contenu généré par l'IA et de son exactitude ;
- Des interruptions liées au prestataire d'IA (Groq).

**6.5 Hébergement**
Le Bot est hébergé par KaMi4zEi, en France.
Contact : Discord — discord.gg/Uu9M7AAWvQ / E-mail — contact@pixelhorizons.fr
L'Owner ne saurait être tenu responsable des interruptions ou incidents liés à l'infrastructure d'hébergement.

---

## Article 7 — Propriété intellectuelle

**7.1** Le Bot Supernova, son code source, ses fonctionnalités et son nom sont la propriété exclusive de l'Owner.

**7.2** Il est interdit de copier, reproduire, modifier, distribuer ou exploiter commercialement tout ou partie du Bot sans l'accord écrit préalable de l'Owner.

**7.3** L'utilisation du Bot ne vous confère aucun droit de propriété sur celui-ci.

---

## Article 8 — Suspension et résiliation

**8.1** L'Owner se réserve le droit de suspendre ou de résilier l'accès au Bot à tout utilisateur ou serveur, à tout moment et sans préavis, notamment en cas de :
- Violation des présentes CGU ;
- Utilisation abusive ou malveillante du Bot ;
- Violation des Conditions d'Utilisation de Discord.

**8.2** Un serveur ou un utilisateur peut être ajouté en blacklist globale, empêchant tout accès futur au Bot.

**8.3** Les administrateurs de serveur peuvent retirer le Bot à tout moment en le kickant depuis les paramètres de leur serveur Discord.

---

## Article 9 — Modifications des CGU

**9.1** L'Owner se réserve le droit de modifier les présentes CGU à tout moment. Les modifications entrent en vigueur dès leur publication.

**9.2** Il est de la responsabilité des utilisateurs et administrateurs de consulter régulièrement les CGU en vigueur.

**9.3** La poursuite de l'utilisation du Bot après modification des CGU vaut acceptation des nouvelles conditions.

---

## Article 10 — Contact et support

Pour toute question, signalement de bug, demande de suppression de données ou recours suite à une sanction automatique, contactez le support officiel :

- **Nom du projet :** Supernova Bot
- **Responsable du traitement :** Mr.Hugo, développeur et propriétaire du Bot (« l'Owner »)
- **Pays :** France
- **Contact :** supernovabotofficiel@gmail.com
- **Serveur Discord :** https://discord.gg/NUFRRmHKKZ
- **Préfixes du Bot :** `s!` (général) | `staff!` (staff bot) | `o!` (owner bot uniquement)

---

## Article 11 — Droit applicable

Les présentes CGU sont régies par le droit français. Tout litige relatif à leur interprétation ou exécution sera soumis aux tribunaux compétents.
