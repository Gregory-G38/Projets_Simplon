# Projets_Simplon
Présentation des exercices demandé par Simplon pour évaluer mon niveau pour intégrer la formation Technicien Supérieur Système et Réseau

Quatre exercices techniques réalisés à partir d'un brief fourni par Simplon, centré sur le déploiement d'une infrastructure réseau pour une PME fictive.

## Topologie réseau — IP statiques (Packet Tracer)

Deux LAN (192.168.1.0/24 et 192.168.2.0/24) reliés par un routeur ISR4331.
Adressage statique sur tous les équipements, validation par ping inter-LAN.

![Topologie partie 1](packet-tracer/topologie-partie1.png)

## Topologie réseau — DHCP centralisé (Packet Tracer)

Ajout d'un serveur DHCP dans le LAN Site A, avec deux pools d'adresses
et un IP Helper sur le routeur pour couvrir le Site B.

![Topologie partie 2](packet-tracer/topologie-partie2.png)

## Windows Server 2019 (VirtualBox)

Installation et configuration sous VirtualBox : rôles DHCP et ADDS,
domaine rue25.com, UOs, groupes de sécurité, comptes utilisateurs
et dossiers partagés avec droits par groupe.

[Documentation](windows-server-2019/Rue25_DHCP_Document_Technique.pdf)

## Debian 11.6 + GLPI (VirtualBox)

Déploiement en CLI pur : SSH, stack LAMP, installation et configuration
initiale de GLPI accessible depuis l'interface web.

[Documentation](debian-glpi/Rue25_GLPI_Document_Technique.pdf)
