# SOC Home Lab

Projet de fin d'études — Master Cybersécurité, Sup de Vinci (2024)

## Contexte

Mise en place d'un SOC (Security Operations Center) externalisé pour 
une entreprise fictive du secteur médical.
Objectif : détecter, analyser et répondre aux incidents de sécurité 
via une stack open-source.

## Stack technique

| Outil | Rôle |
|-------|------|
| **Wazuh** | SIEM / EDR — collecte et corrélation des alertes |
| **TheHive** | Gestion des incidents de sécurité |
| **Suricata** | IDS/IPS — détection d'intrusions réseau |

## Architecture

- VMs locales (environnement virtualisé)
- Intégration Wazuh → TheHive pour remontée automatique des alertes
- Agents Wazuh déployés sur les postes supervisés
- Règles de détection personnalisées (Linux, scan de vulnérabilités)

## Ce qui a été fait

- Analyse des besoins de sécurité et identification des actifs critiques
- Conception de l'architecture SOC
- Installation et configuration de Wazuh (serveur + agents)
- Installation et configuration de TheHive
- Intégration Wazuh ↔ TheHive
- Installation de Suricata (IDS réseau)
- Création de règles de détection de vulnérabilités
- Documentation complète du processus

## Compétences mobilisées

`Cybersécurité` `SIEM` `SOC` `Wazuh` `TheHive` `Suricata` 
`Linux` `Virtualisation` `Détection d'incidents` `RGPD` `ISO 27001`
