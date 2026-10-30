# Enterprise Hybrid Infrastructure
## Persönlicher Projektplan

---

# Projektstatus

- [ ] Phase 1 – Basisinfrastruktur
- [ ] Phase 2 – Hochverfügbarkeit
- [ ] Phase 3 – Sicherheit
- [ ] Phase 4 – Automatisierung
- [ ] Phase 5 – Azure Hybrid
- [ ] Phase 6 – Notfallwiederherstellung
- [ ] Phase 7 – Dokumentation

---

# Phase 1 – Basisinfrastruktur

**Ziel**

Aufbau der grundlegenden Unternehmensinfrastruktur.

## VMware

- [ ] Server01 erstellen
- [ ] Server02 erstellen
- [ ] Windows 11 erstellen
- [ ] Netzwerk konfigurieren

## Windows Server

- [ ] Windows Server 2025 installieren
- [ ] Server umbenennen
- [ ] Statische IP konfigurieren
- [ ] Zeitzone einstellen

## Active Directory

- [ ] AD DS installieren
- [ ] Neue Gesamtstruktur erstellen
- [ ] Domäne erstellen

## DNS

- [ ] DNS prüfen
- [ ] DNS-Zone konfigurieren
- [ ] Namensauflösung testen

## DHCP

- [ ] DHCP installieren
- [ ] DHCP-Bereich erstellen
- [ ] IP-Vergabe testen

## Windows 11

- [ ] Windows 11 installieren
- [ ] Domäne beitreten
- [ ] Anmeldung testen

## Organisationseinheiten

Erstellen:

- [ ] Management
- [ ] HR
- [ ] Finance
- [ ] IT
- [ ] Sales
- [ ] Warehouse

## Benutzer und Gruppen

- [ ] Benutzer erstellen
- [ ] Sicherheitsgruppen erstellen
- [ ] Benutzer zuweisen

## Dateiserver

- [ ] Freigaben erstellen
- [ ] NTFS-Berechtigungen konfigurieren
- [ ] Freigabeberechtigungen konfigurieren

## Gruppenrichtlinien

- [ ] Kennwortrichtlinie
- [ ] Laufwerkszuordnung
- [ ] Desktop-Richtlinie
- [ ] Windows-Firewall

---

# Phase 2 – Hochverfügbarkeit

**Ziel**

Die Dienste sollen auch beim Ausfall eines Servers verfügbar bleiben.

## Zweiter Domain Controller

- [ ] Server02 installieren
- [ ] Der Domäne beitreten
- [ ] Zum Domain Controller hochstufen

## Replikation

- [ ] AD-Replikation prüfen
- [ ] Benutzerreplikation testen

## DNS

- [ ] DNS-Replikation prüfen

## DHCP

- [ ] DHCP-Failover konfigurieren
- [ ] Failover testen

---

# Phase 3 – Sicherheit

**Ziel**

Die Infrastruktur absichern.

## Windows LAPS

- [ ] LAPS konfigurieren
- [ ] Passwort testen

## Administrator-Konten

- [ ] Separate Admin-Konten erstellen
- [ ] Administratorrechte von Standardbenutzern entfernen

## Kennwortrichtlinien

- [ ] Mindestlänge
- [ ] Komplexität
- [ ] Ablaufdatum

## Kontosperrung

- [ ] Sperrrichtlinie konfigurieren

## Überwachung

- [ ] Anmeldungen
- [ ] Benutzeränderungen
- [ ] Gruppenänderungen

---

# Phase 4 – Automatisierung

**Ziel**

Administrative Aufgaben automatisieren.

## PowerShell

- [ ] Benutzer aus CSV importieren
- [ ] Benutzer deaktivieren
- [ ] Benutzer verschieben
- [ ] Berichte erstellen

---

# Phase 5 – Azure Hybrid

**Ziel**

Die lokale Umgebung mit Azure verbinden.

## Azure

- [ ] Ressourcengruppe
- [ ] Budget

## Microsoft Entra Cloud Sync

- [ ] Installieren
- [ ] Benutzer synchronisieren

## Azure File Sync

- [ ] Agent installieren
- [ ] Ordner synchronisieren

## Azure Backup

- [ ] Recovery Services Vault
- [ ] Backup konfigurieren
- [ ] Wiederherstellung testen

## Azure Arc

- [ ] Server01 verbinden
- [ ] Server02 verbinden

## Azure Monitor

- [ ] Log Analytics
- [ ] Monitoring

## Azure Policy

- [ ] Richtlinien konfigurieren
- [ ] Compliance prüfen

---

# Phase 6 – Notfallwiederherstellung

**Ziel**

Dienste und Daten nach einem Ausfall wiederherstellen.

## Backup

- [ ] Windows Server Backup
- [ ] Wiederherstellung testen

## Schattenkopien

- [ ] Aktivieren
- [ ] Wiederherstellung testen

## Active Directory Papierkorb

- [ ] Aktivieren
- [ ] Gelöschte Benutzer wiederherstellen

## Notfallsimulation

- [ ] Domain Controller ausschalten
- [ ] Anmeldung testen
- [ ] DNS testen
- [ ] DHCP testen
- [ ] Dateien wiederherstellen

---

# Phase 7 – Dokumentation

- [ ] Netzwerkdiagramm
- [ ] IP-Adressplan
- [ ] OU-Struktur
- [ ] Azure-Architektur
- [ ] Backup-Konzept

---

# Erweiterungen (Optional)

- [ ] DFS Namespace
- [ ] DFS-Replikation
- [ ] Site-to-Site VPN
- [ ] Azure Update Manager
- [ ] Microsoft Defender for Cloud
- [ ] Azure Key Vault
- [ ] BitLocker
- [ ] IIS
- [ ] File Server Resource Manager
- [ ] Windows Admin Center
- [ ] Multi-Faktor-Authentifizierung
- [ ] Protected Users

---

# Abschluss

- [ ] Alle Dienste testen
- [ ] Screenshots erstellen
- [ ] Wiederherstellungszeiten dokumentieren
- [ ] Dokumentation abschließen
- [ ] Präsentation vorbereiten
