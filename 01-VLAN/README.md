# Lab 01 - VLAN

## 🎯 Objectif

Créer et configurer deux VLAN sur un switch Cisco afin de
séparer deux réseaux.

## 🖥️ Topologie

PC1 -------- SW1 -------- PC2

PC1 → VLAN 10 (INFORMATIQUE)
PC2 → VLAN 20 (RH)

## 🌐 Plan d'adressage

| Équipement | Adresse IP | VLAN |
|------------|------------|------|
| PC1 | 192.168.10.10/24 | VLAN 10 |
| PC2 | 192.168.20.10/24 | VLAN 20 |

## ⚙️ Configuration

### Création des VLAN

```cisco
vlan 10
name INFORMATIQUE

vlan 20
name RH
