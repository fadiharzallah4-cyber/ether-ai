# ETHER – Votre partenaire intellectuel impitoyable

ETHER est une application de chat IA basée sur Electron qui route intelligemment les requêtes vers plusieurs fournisseurs (Groq, Gemini, Mistral, Cerebras) tout en conservant une personnalité distincte : franche, directe et sans complaisance.

## Ce qui rend ETHER différent

La plupart des assistants IA sont conçus pour valider vos idées. ETHER fait le contraire.

### Le principe du Mentor Impitoyable

ETHER fonctionne comme un partenaire intellectuel honnête, pas comme un assistant passif :

• **Voix active et directivité** : Pas d'emojis, pas de fioritures. Droit au but.
• **Analyse critique** : Chaque idée est passée au crible. Si elle est bancale, ETHER vous dira pourquoi et comment la corriger.
• **Pas de fausse politesse** : Le désaccord est attendu. La contradiction est bienvenue.
• **Adaptation automatique** : Synthétique pour un résumé, détaillé avec exemples pour un travail complexe.
• **Refus du vide** : Les explications longues et inutiles sont rejetées par conception.

## Fonctionnalités principales

• **Routage intelligent** : Bascule entre Groq, Gemini, Mistral et Cerebras selon la tâche.
• **Modes multiples** : Mode Teacher (pédagogie socratique), Mode Créatif, Mode Écriture.
• **Mixture of Agents (MoA)** : Collaboration entre modèles pour des réponses de haute qualité.
• **Architecture locale** : Données persistantes stockées localement pour la confidentialité.

## État actuel (v1.2.0)

• ✅ Intégration complète de **Mistral Large** (prioritaire pour le raisonnement complexe).
• ✅ Système de collaboration Gemini + Mistral + Groq opérationnel.
• ✅ Support multi-onglets et recherche dans l'historique.
• ✅ Interface de gestion des clés API sécurisée.

## Installation et Lancement

### Prérequis
• Node.js 18+
• Clés API (Groq, Gemini, ou Mistral)

### Commandes Terminal
1. **Mise à jour et Installation** :
```bash
git pull
npm install
```

2. **Configuration** (Optionnel) :
Créez un fichier `.env` à la racine :
```env
MISTRAL_KEY=votre_cle_ici
GROQ_KEY=votre_cle_ici
```

3. **Lancement** :
```bash
npm start
```

## Philosophie
ETHER rejette l'idée que l'IA doit être universellement amicale. La croissance intellectuelle nécessite de l'honnêteté. Attendez-vous à être mis au défi.

---
*Construit avec une honnêteté radicale.*
