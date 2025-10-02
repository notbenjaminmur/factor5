# factor5
Billing has never been easier

# Générateur de Factures Conforme (France) – V2

Ce projet est une application **web simple et autonome** permettant de générer des factures **conformes à la législation française**, directement depuis le navigateur, au format PDF.

## 🚀 Fonctionnalités principales

- **Saisie rapide des informations légales** de l’entreprise  
  (raison sociale, adresse, SIRET/SIREN, capital social, RCS/RM, TVA, etc.).  
- **Ajout d’un ou plusieurs articles/prestations**  
  (description, quantité, prix unitaire HT).  
- **Gestion de la TVA** :
  - TVA applicable (calcul automatique du HT, TVA et TTC).  
  - Option **TVA non applicable** (art. 293B du CGI – micro-entrepreneur).  
- **Calcul automatique des totaux** : HT, TVA, TTC ou Net à payer.  
- **Numérotation séquentielle automatique** des factures.  
- **Conditions de paiement personnalisables**  
  (échéance, pénalités de retard, indemnité forfaitaire de 40€).  
- **Lien de paiement intégré** :
  - Possibilité d’ajouter une **URL de paiement en ligne**  
    (ex : [BridgeAPI.io](https://bridgeapi.io), Stripe, PayPal…).  
  - Génération automatique d’un **QR Code** cliquable sur la facture.
- **Export PDF instantané** avec mise en page professionnelle et conforme.  
- **100% côté client** : aucune donnée n’est envoyée sur un serveur, tout est généré localement dans le navigateur avec [jsPDF](https://github.com/parallax/jsPDF).

## 🖼 Démo rapide

1. Remplissez vos informations (entreprise, client, dates, n° de facture).  
2. Ajoutez un ou plusieurs articles.  
3. Indiquez un lien de paiement (facultatif).  
4. Cliquez sur **Générer la Facture PDF**.  
5. Votre facture est prête, avec lien/QR code de paiement intégré.  

## 💡 Cas d’usage

- Freelance, micro-entrepreneur ou PME souhaitant générer des factures conformes **sans logiciel complexe**.  
- Facturation avec **paiement en ligne intégré** via BridgeAPI, Stripe, PayPal, etc.  
- Génération rapide et sécurisée de factures PDF **sans dépendre d’un service tiers**.  

---

✨ *Simple, conforme, et directement prêt à l’emploi.*
