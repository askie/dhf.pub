# DHF Agent - Agent Web automatisé piloté par l'IA

[English](README.md) | [简体中文](README_CN.md) | [日本語](README_JA.md) | [Deutsch](README_DE.md) | [Français](README_FR.md) | [Español](README_ES.md) | [Português](README_PT.md) | [Русский](README_RU.md) | [한국어](README_KO.md)

![Logo DHF Agent](icon.png)

**La plateforme d'automatisation intelligente des processus de nouvelle génération pilotée par l'IA, qui comprend et exécute intelligemment vos processus métier.**

[Télécharger DHF Agent](https://dhf.pub/) | [Fonctionnalités clés](#-fonctionnalités-clés--key-features) | [Pour qui ?](#-pourquoi-choisir-dhf-agent--who-is-this-for) | [Écosystème MCP](#-connexion-à-lécosystème-mcp)

---

## 🚀 Introduction

**DHF Agent** est un outil révolutionnaire de RPA (Robotic Process Automation) pour navigateur. Il utilise une technologie d'IA avancée pour comprendre les pages Web et aider les utilisateurs à créer des flux de travail automatisés.

Contrairement à d'autres agents d'IA, DHF Agent adopte un modèle **"Généré par l'IA, Exécuté localement"**. Une fois qu'un flux de travail est construit, il se transforme en une exécution de code fixe efficace, **ne consommant plus de jetons (Tokens)**, garantissant à la fois la précision de l'exécution et un fonctionnement sans coût. Que vous soyez un employé de bureau cherchant à échapper aux tâches répétitives ou un développeur à la recherche d'interfaces Web efficaces, DHF Agent est votre meilleur partenaire.

---

## 🎯 Pourquoi choisir DHF Agent ? | Who is this for?

Nous avons des solutions sur mesure pour différents groupes :

### 1. 👩‍💼 Employés de bureau et personnel administratif (Office Workers)
**Dites adieu aux clics répétitifs et gardez du temps pour la créativité.**
*   **Problème :** Remplir des formulaires, extraire des données et cliquer sur des boutons de manière répétitive sur le navigateur chaque jour.
*   **Solution DHF :** Dites à l'IA ce que vous voulez faire, et elle générera automatiquement le processus d'opération. Avec le **Planificateur de tâches** intégré, vous pouvez laisser l'ordinateur vous aider automatiquement à télécharger des rapports ou à saisir des données tard dans la nuit, et voir les résultats directement en arrivant au travail le matin.

### 2. 👨‍💻 Geeks de l'IA et développeurs (Developers & Geeks)
**Solution d'opération Web de haute précision et sans coût.**
*   **Problème :** Les opérations Web pilotées uniquement par LLM consomment beaucoup de jetons et sont sujettes aux hallucinations et à l'instabilité.
*   **Solution DHF :** Utilisez l'IA pour aider à écrire des scripts Playwright. Une fois le débogage réussi, les exécutions ultérieures consomment **0 jeton**. Transformez le raisonnement incertain de l'IA en exécution de code déterminée, précise, fiable et gratuite.

### 3. 🦄 Solopreneurs et développeurs indépendants (Solopreneurs)
**Une seule personne est une équipe.**
*   **Problème :** Manque de ressources, coût élevé de l'embauche d'employés.
*   **Solution DHF :** Créez différents rôles d'agent DHF (par exemple, assistant de service client, opérateur de médias sociaux, spécialiste financier). Ils sont comme vos employés numériques, accomplissant leurs tâches Web respectives indépendamment en arrière-plan, assurant le fonctionnement de votre entreprise 24h/24 et 7j/7.

### 4. 🔗 Utilisateurs MCP et OpenClaw (Ecosystem Users)
**Le super tentacule qui connecte tout.**
*   **Problème :** Les grands modèles ne peuvent pas utiliser précisément les pages Web, ou le coût d'opération est trop élevé.
*   **Solution DHF :** Prend parfaitement en charge le **MCP (Model Context Protocol)**. DHF Agent peut être monté comme la "main" d'OpenClaw ou d'autres outils d'IA, convertissant les instructions en langage naturel en actions Playwright précises, économisant considérablement les jetons et améliorant les taux de réussite des opérations.

---

## ✨ Fonctionnalités clés | Key Features

### ⚡ Amélioration de l'efficacité de 10x
Confiez les opérations Web fastidieuses et répétitives à DHF Agent pour réaliser un bond de 10x en efficacité. Laissez les machines faire les tâches de machines et les humains faire les tâches humaines.

### 🧠 Piloté par l'IA et débogage assisté
Dites adieu au code fastidieux. L'IA aide intelligemment à générer et à déboguer les flux de travail, permettant au langage naturel de piloter la construction des processus. Le développement automatisé n'a jamais été aussi simple ; même si vous ne connaissez pas le code, vous pouvez commencer.

### 💸 Coût d'exécution nul (Zero Runtime Cost)
C'est notre plus grand avantage. Après le débogage, le flux de travail peut s'exécuter indépendamment sans intervention de l'IA. **Pas de coûts continus de jetons API**, réalisant une véritable économie.

### 🔒 Confidentialité avant tout
S'exécute entièrement localement, avec un stockage de données crypté. Les données du navigateur, les mots de passe de compte sont tous sur votre propre appareil. Vous avez un contrôle total pour assurer une sécurité absolue.

### 🌐 Connexion à l'écosystème MCP
Prend en charge les protocoles MCP standard, se connectant de manière transparente aux écosystèmes externes comme **n8n**, **Dify** et **OpenClaw**. Brisez les silos d'applications et créez des flux de travail super automatisés.

### 🤝 Partage de flux de travail
Prend en charge l'exportation et le partage en un clic des flux de tâches. Transformez votre "expérience d'automatisation" en fichiers à partager avec des collègues ou la communauté, permettant une réutilisation rapide des capacités.

### ⏱️ Planification intelligente des tâches
Moteur de planification Cron de niveau professionnel intégré, prenant en charge la configuration du temps à la seconde près. Automatisez entièrement votre travail périodique (par exemple, pointage automatique à 9h00 tous les jours, envoi automatique de rapports hebdomadaires tous les vendredis).

---

## 🛠️ Intégration technique (For Developers)

DHF Agent est plus qu'un simple outil ; c'est une infrastructure.

*   **En tant que serveur MCP :** Vous pouvez monter DHF Agent en tant que serveur MCP pour Cursor, Claude Desktop ou d'autres outils de code IA. Cela donne à votre assistant de programmation IA la possibilité d'utiliser directement de vrais navigateurs.
*   **Convertisseur Playwright :** Il peut précipiter les intentions instables en langage naturel en scripts Playwright stables.
*   **Déclencheur API :** Prend en charge les appels API locaux, s'intégrant facilement à vos projets Python/Node.js existants.

---

## 📥 Téléchargement et installation | Download

Prend en charge Windows, macOS et Linux.

[**Cliquez ici pour télécharger la dernière version**](https://dhf.pub/)

---

## 🚀 Démarrage rapide | Quick Start

1.  **Télécharger et installer** DHF Agent.
2.  **Créer une tâche** : Cliquez sur "Nouvelle tâche" et entrez l'URL cible.
3.  **Enregistrement IA** : Dites à l'IA dans la boîte de dialogue "Aide-moi à me connecter et télécharge le dernier Excel de commande", et l'IA générera automatiquement les étapes.
4.  **Enregistrer et exécuter** : Confirmez que les étapes sont correctes et enregistrez la tâche. Réglez une minuterie, et il travaillera automatiquement pour vous à l'avenir.

---

## Communauté et support

*   Soumettre des problèmes : [GitHub Issues](https://github.com/askie/dhf.pub/issues)

---

**DHF Agent** - Redefining Browser Automation with AI.

---
