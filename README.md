# Scalable Capital Personal Live

**Scalable Capital Personal Live** ist eine lokale Windows‑Desktop‑Anwendung zur privaten Portfolio‑Übersicht.  
Die App zeigt Depotwerte, Guthaben, Tagesgeld, Aktien, ETFs, Live‑Kurse, Gewinne/Verluste, Prognosen und optional KI‑gestützte Auswertungen in einer modernen Dark‑Business‑Oberfläche.

> Diese Anwendung ist **keine offizielle Scalable‑Capital‑App** und steht in keiner Verbindung zu Scalable Capital.  
> Alle Daten dienen ausschließlich der privaten Übersicht.

---

## 📌 Inhaltsverzeichnis

- [Überblick](#überblick)
- [Download](#download)
- [Start](#start)
- [Systemanforderungen](#systemanforderungen)
- [Hauptfunktionen](#hauptfunktionen)
- [Datenschutz](#datenschutz)
- [Sicherheit](#sicherheit)
- [Hinweise zur Genauigkeit](#hinweise-zur-genauigkeit)
- [Keine Anlageberatung](#keine-anlageberatung)
- [Bekannte Einschränkungen](#bekannte-einschränkungen)
- [Empfohlener Ablauf](#empfohlener-ablauf)
- [Dateiname](#dateiname)
- [Lizenz](#lizenz)
- [Haftungsausschluss](#haftungsausschluss)

---

## Überblick

Die Anwendung kombiniert importierte Scalable‑Capital‑Daten, manuelle Abgleichswerte und Live‑Kurse, um ein möglichst realistisches Bild des eigenen Portfolios darzustellen.

Unterstützt werden unter anderem:

- Gesamtvermögen  
- Broker-/Depotwert  
- Guthaben  
- Tagesgeld  
- Aktienpositionen  
- ETF‑Positionen  
- Einstandswerte  
- Stückzahlen  
- Gewinn/Verlust  
- Markttag‑Veränderungen  
- Live‑Kursquellen  
- ETF‑Prognosen  
- KI‑Unterstützung über OpenRouter  

---

## Download

Die Anwendung wird als fertige Windows‑EXE bereitgestellt.

Lade die aktuelle Datei aus den **Releases** herunter:


Keine Installation notwendig.

---

## Start

1. `ScalableCapitalPersonalLive.exe` starten  
2. Scalable‑Capital‑CSV importieren oder manuelle Werte eintragen  
3. Optional Live‑Aktualisierung aktivieren  
4. Optional OpenRouter‑API‑Key für den KI‑Broker hinterlegen  

---

## Systemanforderungen

### Betriebssystem

- Windows 10 oder neuer  
- Windows 11 empfohlen  

### Netzwerk

Für Live‑Kurse und KI‑Funktionen wird eine Internetverbindung benötigt.

### Optional

Für den KI‑Broker wird ein OpenRouter‑API‑Key benötigt:


---

## Hauptfunktionen

### Portfolio‑Übersicht

Die App zeigt eine kompakte Übersicht über:

- Gesamtwert  
- Depotwert  
- Guthaben  
- Tagesgeld  
- Gesamtgewinn  
- Performance  
- investierten Betrag  
- Updatequelle  

---

### Scalable‑Abgleich

Manuelle Abgleichswerte für:

- Gesamtvermögen  
- Depotwert  
- Guthaben  
- Tagesgeld  
- Stückzahlen  
- Einstandswerte  
- Positionstyp (Aktie/ETF)  

---

### Live‑Kurse

Mögliche Quellen:

- Yahoo/yfinance  
- Scalable‑CSV  
- manuelle Abgleichswerte  

---

### Aktien und ETFs

Für jede Position:

- Name  
- Symbol  
- ISIN  
- Stückzahl  
- aktueller Kurs  
- aktueller Wert  
- Einstand  
- Gewinn/Verlust  
- Datenquelle  

---

### Markttag‑Berechnung

Die App zeigt Veränderungen seit dem letzten gespeicherten Markttag:

- Veränderung Gesamtwert  
- Veränderung Gesamtgewinn  
- Prozentuale Veränderung  
- farbliche Hervorhebung  

---

### Tagesgeld

Unterstützt:

- Tagesgeldbetrag  
- Zinssatz p.a.  
- Zinsen pro Tag  
- Zinsen pro Monat  
- Zinsen pro Jahr  
- 30‑Tage‑Prognose  
- 12‑Monats‑Prognose  

---

### ETF‑Prognose

Berechnet langfristige Szenarien basierend auf:

- aktuellem ETF‑Wert  
- monatlicher Sparrate  
- erwarteter Rendite  
- Inflation  
- Laufzeit  

Ausgabe:

- ETF‑Wert  
- Aktien‑Wert  
- Gesamtwert  
- heutige Kaufkraft  
- erwarteter Gewinn  

---

### Dashboard

Enthält:

- KPI‑Karten  
- Live‑Status  
- Portfolioübersicht  
- Positionskarten  
- Charts  
- Markttag‑Werte  
- Updatequelle  

---

### Desktop‑Widget

Zeigt kompakt:

- Gesamtwert  
- Depotwert  
- Guthaben  
- Tagesgeld  
- Gewinn/Verlust  
- Live‑Status  

---

### KI‑Broker (OpenRouter)

Beantwortet ausschließlich deutschsprachige Finanz‑ und Portfoliofragen:

- Broker  
- Aktien  
- ETFs  
- Portfolioanalyse  
- Rendite  
- Kursentwicklung  
- Szenarien  

API‑Key wird lokal verschlüsselt gespeichert.

---

## Datenschutz

Lokal gespeichert werden:

- CSV‑Daten  
- manuelle Abgleichswerte  
- verschlüsselte Datenbank  
- Einstellungen  
- verschlüsselter API‑Key  
- lokale Logdateien  

Keine Daten werden an Server dieses Projekts übertragen.

---

## Sicherheit

- Lokale Speicherung  
- Verschlüsselte Datenbank  
- Keine Cloud‑Synchronisierung  
- Keine Verbindung zu Scalable Capital  

---

## Hinweise zur Genauigkeit

Werte können abweichen durch:

- andere Kursquelle  
- verzögerte Kurse  
- Rundungen  
- Währungsumrechnung  
- Gebühren  
- Steuern  
- Tagesgeld‑Zinsen  
- CSV‑Zeitpunkt  
- manuelle Abgleichswerte  

---

## Keine Anlageberatung

Diese Anwendung stellt **keine Anlageberatung** dar.  
Alle Auswertungen, Prognosen und KI‑Antworten dienen nur der privaten Orientierung.

---

## Bekannte Einschränkungen

- Keine offizielle Scalable‑API  
- Live‑Kurse können verzögert sein  
- CSV‑Daten können älter sein  
- manuelle Werte müssen gepflegt werden  
- KI‑Ausgaben können Fehler enthalten  

---

## Empfohlener Ablauf

1. EXE starten  
2. CSV importieren  
3. Guthaben, Tagesgeld und Gesamtvermögen abgleichen  
4. Positionen prüfen  
5. Stückzahlen/Einstände korrigieren  
6. Live‑Aktualisierung starten  
7. Dashboard prüfen  
8. Optional KI‑Broker aktivieren  

---
