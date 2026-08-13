# TWINT CH Desktop
<img width="1117" height="1562" alt="Twint" src="https://github.com/user-attachments/assets/24ecd40e-2efa-4236-8516-9bea7835d344" />


**TWINT CH Desktop** ist eine Desktop-Anwendung für Windows-PCs, die entwickelt wurde, um die Nutzung von TWINT-Funktionen auf einem Computer zu ermöglichen.

Die Anwendung verbindet sich über eine eigene API-Schnittstelle mit der mobilen TWINT-Anwendung. Dadurch können bestimmte Funktionen und Daten zwischen der Desktop-Anwendung und der TWINT-Mobile-Umgebung ausgetauscht und auf dem PC dargestellt werden.

## 🖥️ Über das Projekt

Das Ziel des Projekts ist es, eine komfortable Desktop-Oberfläche für die Arbeit mit TWINT auf einem PC bereitzustellen.

Die Desktop-Anwendung übernimmt dabei die Benutzeroberfläche und die Kommunikation mit der TWINT-Mobile-Umgebung. Die Verbindung erfolgt über eine API-Schnittstelle, wodurch die Desktop-App mit den entsprechenden mobilen TWINT-Funktionen kommunizieren kann.

### 🔗 Architektur

```text
┌─────────────────────────┐
│     TWINT CH Desktop    │
│        Windows PC       │
└────────────┬────────────┘
             │
             │ API
             ▼
┌─────────────────────────┐
│     TWINT Mobile API    │
│      / Mobile App       │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│   TWINT Backend /       │
│   Payment Services      │
└─────────────────────────┘
```

## ⚙️ Funktionsprinzip

Die Anwendung wurde als Desktop-Client konzipiert. Anstatt eine vollständig unabhängige Zahlungsinfrastruktur auf dem PC zu implementieren, nutzt die Anwendung eine API-basierte Kommunikation mit der TWINT-Mobile-Umgebung.

Der grundlegende Ablauf:

1. Der Benutzer startet die Desktop-Anwendung auf dem PC.
2. Die Anwendung stellt eine Verbindung zur API-Schnittstelle her.
3. Anfragen werden an die TWINT-Mobile-Umgebung übermittelt.
4. Die erhaltenen Daten werden verarbeitet und in der Desktop-Oberfläche dargestellt.
5. Aktionen des Benutzers können über die API an die entsprechende TWINT-Umgebung weitergeleitet werden.

## 🚀 Ziel

Das Projekt dient als technische Demonstration dafür, wie eine Desktop-Anwendung mit einer mobilen Zahlungsanwendung über eine API-Schnittstelle verbunden werden kann.

Der Schwerpunkt liegt dabei auf:

* 🖥️ Desktop-Benutzeroberfläche
* 🔗 API-Kommunikation
* 📱 Integration mit TWINT Mobile
* 🔐 sicherer Datenübertragung
* ⚡ schneller Kommunikation zwischen Desktop und Mobile
* 🧩 modularer Softwarearchitektur

## ⚠️ Hinweis

Dieses Projekt ist **keine offizielle TWINT-Anwendung** und steht in keiner offiziellen Verbindung zur TWINT AG. Die verwendeten API-Schnittstellen und Integrationsmechanismen sind ausschließlich für Entwicklungs- und Demonstrationszwecke vorgesehen.

Für produktive Zahlungsanwendungen müssen die offiziellen TWINT-Schnittstellen, Sicherheitsanforderungen und Nutzungsbedingungen beachtet werden.

## 📄 Lizenz

Die Lizenz und Nutzungsbedingungen dieses Projekts werden vom jeweiligen Repository-Eigentümer festgelegt.
