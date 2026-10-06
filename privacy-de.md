---
layout: default
title: Datenschutzerklärung
permalink: /privacy-de/
---

# MedTime (İlaçVakti) — Datenschutzerklärung

**Zuletzt aktualisiert:** 6. Oktober 2026

MedTime (İlaçVakti) ist eine mobile Anwendung, die von dem Apotheker **Mehmet Tuğberk Özsoy** entwickelt wurde und Nutzerinnen und Nutzer dabei unterstützt, ihre Medikamente im Blick zu behalten. Der Schutz Ihrer Privatsphäre hat für uns höchste Priorität; diese Erklärung legt transparent dar, welche Daten verarbeitet werden und auf welche Weise.

Andere Sprachen: [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Nicht erhobene Daten

MedTime erhebt **keine** personenbezogenen Identifikationsmerkmale (Name, E-Mail-Adresse, Telefonnummer, Ausweisnummer, Geburtsdatum usw.) von Nutzerinnen und Nutzern, übermittelt diese nicht an unsere Server und gibt sie nicht an Dritte weiter. Es ist keine Kontoerstellung erforderlich; die App funktioniert vollständig **anonym**.

Detaillierte Liste der nicht erhobenen Daten:
- ❌ Werbenetzwerke, Profilbildung oder App-übergreifendes Tracking (zur Werbemessung im App Store siehe Abschnitt 5)
- ❌ Analysedienste von Drittanbietern (Google Analytics, Facebook Pixel usw.)
- ❌ Standortdaten
- ❌ Kontakte, Kalender
- ❌ Speicherung von Audioaufnahmen (das Mikrofon wird nur für die optionale Spracheingabe aktiviert, siehe 3.6)
- ❌ Kontoerstellung, E-Mail, Telefon
- ❌ Apple-Health-Daten **verlassen Ihr Gerät nicht** (die optionale Lese-/Schreib-Synchronisierung läuft auf dem Gerät, siehe 3.5)
- ❌ Ihre iCloud-Sicherung und Ihre Familienfreigabe-Daten **erreichen den Entwickler nicht** (sie bleiben in Ihren eigenen iCloud-Konten, siehe 2.1 und 2.2)

---

## 2. Lokale Speicherung (auf Ihrem Gerät gespeicherte Daten)

Die von Ihnen eingegebenen Informationen werden **im internen Speicher Ihres Geräts** gespeichert; der Entwickler betreibt keinen Server, der diese Daten speichert:

- Medikamentennamen, Dosierungen, Erinnerungszeiten
- Profilnamen (von Ihnen angegebene Namen) und optionales Profilfoto
- Informationen zum Medikamentenbestand und Fotos
- Behandlungsverlauf, Protokolle über eingenommene/ausgelassene Dosen
- Streak- und Abzeichendaten
- Manuell hinzugefügte Gesundheitsberichte und Notizen
- Einstellungen für Design, Sprache, Benachrichtigungston und sonstige Präferenzen

Wenn Sie die App löschen, werden diese Daten von Ihrem Gerät entfernt. Ist die iCloud-Sicherung aktiv, bleibt Ihre Sicherung in Ihrem eigenen iCloud-Konto (siehe 2.1).

### 2.1 iCloud-Sicherung (standardmäßig aktiv, abschaltbar)

Wenn Sie auf Ihrem iPhone bei iCloud angemeldet sind, speichert die App einmal täglich eine Sicherung Ihrer Daten im **privaten Bereich Ihres eigenen iCloud-Kontos** (private Apple-CloudKit-Datenbank). So kehren Ihre Medikamente und Ihr Verlauf nach einem Telefonwechsel oder einer Neuinstallation zurück.

- Die Sicherung umfasst Medikamente, Profile, Berichte, Messwerte, Einnahmeverlauf, Abzeichen/Serien und App-Einstellungen. **Fotos sind nicht enthalten.** Auch aus Apple Health übernommene Messwerte sind nicht enthalten; Apple Health speichert sie selbst, und die App liest sie auf einem neuen Telefon erneut ein.
- Die Sicherung liegt in Apples Ende-zu-Ende-verschlüsselten Feldern (CloudKit-verschlüsselte Werte); der Schlüssel befindet sich in Ihrem iCloud-Schlüsselbund. Sehr große Sicherungen (jahrelanger Verlauf) werden als verschlüsselte Datei in iCloud abgelegt; mit aktiviertem Erweitertem Datenschutz ist auch diese Datei Ende-zu-Ende-verschlüsselt.
- Die Sicherung gelangt nie auf Server des Entwicklers; **der Entwickler hat keinen Zugriff darauf.** Sie nutzt Ihren iCloud-Speicher.
- Die Liste Ihrer Familienverbindungen (wem Sie folgen, wer Ihre Dosen sieht) wird ebenso gesichert, damit Verbindungen ein neues Telefon überstehen.
- Abschalten: in der App unter Tab „Profil“ › Datenverwaltung › iCloud-Sicherung. Löschen: iPhone-Einstellungen › [Ihr Name] › iCloud › Accountspeicher verwalten › MedTime.

### 2.2 Familienfreigabe (optional)

Sie können die Medikamente eines Angehörigen von Ihrem eigenen Telefon aus im Blick behalten. Die Freigabe beginnt nur durch **eine ausdrückliche Handlung beider Seiten**: Die folgende Person sendet einen Einladungslink; die Person, der gefolgt wird, sieht auf ihrem eigenen Telefon, was geteilt wird, und **tippt auf „Annehmen“.**

- **Geteilt werden:** die Angaben der Medikamentenkarten des geteilten Profils (etwa Name, Wirkstoff, Dosis, Uhrzeiten, Einnahmehinweise und Medikamentennotiz), genommene oder zurückgenommene Dosen samt Markierungszeit, Profilname und -farbe sowie die Zeitzone des Geräts.
- **Nicht geteilt werden:** das Medikamenten-Tagebuch (Befinden/Nebenwirkungen), Blutdruck- und Blutzuckerwerte, Fotos, Beipackzettel und andere Profile.
- Die Daten werden über Apple iCloud (CloudKit-Freigabe) übertragen und **im iCloud-Konto der folgenden Person** gespeichert; Medikamentennamen und -angaben liegen in Ende-zu-Ende-verschlüsselten Feldern. Wird eine Dosis nicht innerhalb der gewählten Zeit markiert, erhält die folgende Person einen Hinweis; dies wird auf ihrem Gerät berechnet.
- **Der Entwickler hat keinen Zugriff auf diese Daten**; sie laufen nicht über Server des Entwicklers.
- **Beenden:** Die Person, der gefolgt wird, jederzeit über die Karte „Deine Familie“ im Tab „Profil“ („… sieht deine Dosen“), die folgende Person über „Nicht mehr folgen“ auf dem Personenbildschirm. Danach werden die geteilten Daten aus dem iCloud-Konto der folgenden Person gelöscht.
- Eine Einladung anzunehmen ist kostenlos; das Folgen ist eine Premium-Funktion (mit der Apple-Familienfreigabe genügt das Abo eines Familienmitglieds).

---

## 3. Berechtigungen

### 3.1 Benachrichtigungen
Die Berechtigung für Benachrichtigungen wird für Medikamentenerinnerungen angefragt. Benachrichtigungen werden **lokal auf Ihrem Gerät** geplant; es ist keine Serververbindung beteiligt.

### 3.2 Kamera
Der Kamerazugriff wird ausschließlich auf dem Bildschirm *„Medikament hinzufügen"* angefragt, um Barcodes/QR-Codes auf Medikamentenschachteln zu scannen oder Fotos von Medikamenten aufzunehmen. Kameraaufnahmen werden nicht an einen Server übermittelt.

### 3.3 Fotos
Ein optionaler Zugriff auf die Fotomediathek wird angefragt, wenn Sie Medikamenten- oder Profilfotos hinzufügen möchten. Ausgewählte Fotos werden ausschließlich in den internen Ordner der App auf Ihrem Gerät kopiert.

### 3.4 Medikamentendatenbank-Abfrage
Wenn Sie einen Barcode/QR-Code auf einer Medikamentenschachtel scannen oder ein Medikament nach Namen suchen, wird ausschließlich dieser **Barcode bzw. Produktcode oder der Medikamentenname** an einen offiziellen Medikamentendatenbankdienst gesendet, um den Medikamentennamen und weitere Details (Beipackzettel, Verpackung, Verfallsdatum usw.) abzurufen. Welcher Dienst verwendet wird, hängt von der Region Ihres Geräts ab: **NosyAPI** (Türkei), die **U.S. FDA openFDA**-Datenbank (Vereinigte Staaten) oder **AEMPS CIMA** (Spanien). In dieser Abfrage sind keinerlei personenbezogene Daten (Ihr Name, Profildaten, Gesundheitsdaten, Fotos oder Kameraaufnahmen) enthalten – übertragen wird ausschließlich der gescannte Code oder der Suchbegriff. Diese Funktion ist optional; wenn Sie sie nicht nutzen, werden keine Daten gesendet.

Sie können erteilte Berechtigungen jederzeit über die iOS-*Einstellungen &gt; MedTime* widerrufen.

### 3.5 Apple Health (HealthKit) — Optionale Synchronisierung
Premium-Nutzer können optional die Synchronisierung *Einstellungen → Apple Health* aktivieren. Wenn aktiv: (1) die in der App erfassten **Blutdruck-, Blutzucker- und Pulswerte** sowie die markierten **Insulindosen** werden in Apple Health **geschrieben**; (2) **Blutdruck-, Blutzucker- und Pulswerte**, die Ihr Messgerät, Blutzuckermessgerät oder andere Apps in Apple Health schreiben, werden in Ihr Messwert-Tagebuch in der App **gelesen**. Diese Funktion ist **völlig optional** und standardmäßig **deaktiviert**.

- Lese- und Schreibberechtigungen werden über den iOS-Berechtigungsdialog **getrennt** und ausdrücklich erteilt; es wird nur auf die oben genannten Datentypen zugegriffen (Medikamentenlisten, Schritte, Schlaf usw. werden **nicht gelesen**).
- Es werden nur Messwerte **Ihres eigenen Profils** geschrieben; Profile von Familienmitgliedern werden nie synchronisiert.
- Die Daten gehen direkt in den Health-Speicher Ihres Geräts; **nichts wird an einen Server gesendet**. Ihre Health-Daten werden von Apple verschlüsselt.
- Wenn Sie eine Messung in der App löschen oder bearbeiten, wird die in Health geschriebene Kopie entsprechend aktualisiert/entfernt.
- Sie können den Zugriff jederzeit unter iOS *Einstellungen → Health → Datenzugriff & Geräte → İlaçVakti* widerrufen.
- Gesundheitsdaten werden niemals für Werbung, Marketing oder Analysen verwendet (konform mit App-Store-Richtlinie 5.1.3).

### 3.6 Mikrofon und Spracherkennung — Optional
Wenn Sie im Messungs-Bildschirm auf das Mikrofonsymbol tippen, können Sie Ihren Blutdruck oder Blutzucker **per Sprache** eingeben. Diese Funktion ist **vollständig optional**; das Mikrofon wird nur aktiviert, wenn Sie dieses Symbol antippen.

- Ihre Sprache wird **auf Ihrem Gerät** in Text umgewandelt; die App **erzwingt** die geräteinterne Spracherkennung von iOS. **Es werden keine Audiodaten an einen Server gesendet** — die Funktion arbeitet auch im Flugmodus.
- **Es wird keine Audioaufnahme gespeichert.** Nach der Umwandlung in Text werden die Audiodaten nicht aufbewahrt; nur die erkannten Zahlen werden in die Felder auf dem Bildschirm eingetragen.
- Der erkannte Wert wird **nicht direkt gespeichert**: Er wird in das Feld eingetragen und erst erfasst, wenn Sie ihn prüfen und auf **Speichern** tippen.
- Das Mikrofon ist nur auf diesem Bildschirm und nur nach Ihrem Start aktiv; es findet kein Mithören im Hintergrund statt.
- Sie können die Berechtigung jederzeit über iOS *Einstellungen &gt; MedTime* widerrufen.

---

## 4. Absturzberichte (Sentry)

Zur Verbesserung der Stabilität der App werden über den Dienst **Sentry** anonyme Absturzberichte erhoben.

**Erhoben werden:**
- Zeitpunkt des Absturzes, Gerätemodell, iOS-Version, App-Version
- Fehlermeldung und technischer Stack-Trace
- Technischer Kontext vor dem Absturz (z. B. geöffnete Bildschirme)

**Nicht erhoben werden:**
- Benutzername, E-Mail-Adresse, IP-Adresse (`sendDefaultPii` deaktiviert)
- Screenshots, persönliche Medikamentendaten, Gesundheitsdaten
- Fotos oder Inhalte von Berichten

Die Sentry-Daten werden ausschließlich zur Verbesserung der App verwendet; **niemals** für Marketing- oder Werbezwecke. Die Sentry-Daten werden bis zu **90 Tage** lang aufbewahrt.

Datenschutzerklärung von Sentry: <https://sentry.io/privacy/>

---

## 5. Premium-Abonnement und RevenueCat

MedTime bietet ein optionales **Premium-Abonnement** an:

| Plan | Preis | Funktionen |
|---|---|---|
| Monatlich | 3,99 € | Verlängert sich automatisch |
| Jährlich | 29,99 € | Beinhaltet **7-tägige kostenlose Testphase**, verlängert sich automatisch |
| Lebenslang | 49,99 € | **Einmalige Zahlung** – kein Abonnement, keine Verlängerung |

> Die genannten Beträge gelten für den App Store im Euro-Raum (in der Schweiz in CHF). **Die Preise variieren je nach Land**; der App Store zeigt Ihnen vor dem Kauf den genauen Betrag in Ihrer Landeswährung an.

### Verwaltung des Abonnements
- Abonnements verlängern sich automatisch; die Zahlung wird Ihrem iTunes-Konto belastet, sofern nicht mindestens **24 Stunden** vor Ablauf des laufenden Zeitraums gekündigt wird.
- Kündigung: iOS-*Einstellungen → Apple ID → Abonnements*.
- **Familienfreigabe** ist aktiviert – ein Abonnement kann mit bis zu 5 Familienmitgliedern geteilt werden.
- Zahlungen werden von Apple abgewickelt; MedTime hat keinen Zugriff auf Kartendaten.

### Lebenslanger kostenloser Zugang für frühere Nutzer
Nutzerinnen und Nutzer, die die Version **2.0.1 (Build 5) oder eine frühere** installiert haben, erhalten automatisch **lebenslangen kostenlosen Premium-Zugang**. Dies wird anonym auf dem Gerät anhand des Felds `originalApplicationVersion` im Apple-Beleg überprüft.

### RevenueCat (Abonnement-Validierung)
Der Dienst **RevenueCat** wird zur Überprüfung des Abonnementstatus eingesetzt. Eine anonyme Kennung (App User ID), die aus Ihrer Apple ID abgeleitet wird, sowie Daten des Apple-Belegs werden an RevenueCat gesendet. Ihr Name, Ihre E-Mail-Adresse oder Ihre Kontaktdaten werden **nicht weitergegeben**.

Datenschutzerklärung von RevenueCat: <https://www.revenuecat.com/privacy/>

### Werbemessung (Apple Search Ads)
MedTime schaltet gelegentlich Anzeigen im App Store. Um zu messen, welche Anzeige Sie zur App geführt hat, wird ein von Apple **bei der Installation** erzeugtes *Attributions-Token* an RevenueCat übermittelt; RevenueCat fragt damit bei Apple ab, ob die Installation aus einer Anzeige stammt.

- Das Token ist **nicht Ihre Werbe-ID (IDFA)** und identifiziert weder Sie noch Ihr Gerät. Daher wird die iOS-Abfrage *App-Tracking-Transparenz* nicht angezeigt — es findet kein App-übergreifendes Tracking statt.
- Apple liefert ausschließlich Informationen **auf Kampagnenebene** zurück. Diese werden **nicht** mit Ihrem Namen, Ihrem Profil, Ihren Medikamenten oder Ihren Gesundheitsdaten verknüpft.
- Der Vorgang läuft **einmalig bei der Installation**; danach wird Ihre Nutzung der App nicht zu Werbezwecken verfolgt.
- Der einzige Zweck ist die Kontrolle, ob das Werbebudget sinnvoll eingesetzt wird; er dient **nicht** dazu, Ihnen Werbung auszuspielen oder Daten zu verkaufen.

### Nutzungsbedingungen
Es gilt der Apple-Standard-EULA: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Datenweitergabe

MedTime **gibt Nutzerdaten an keinen Dritten weiter, verkauft sie nicht und verwendet sie nicht zu Marketingzwecken**. Die einzigen Ausnahmen sind:

- Die in Abschnitt 3.4 beschriebenen Medikamentendatenbank-Abfragen (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) – übertragen wird ausschließlich der gescannte Code oder der gesuchte Medikamentenname; sie enthalten keine personenbezogenen Daten.
- Die in Abschnitt 4 beschriebenen anonymen Absturzberichte (Sentry).
- Die in Abschnitt 5 beschriebenen anonymen Daten zur Abonnement-Validierung sowie das nicht identifizierende Werbe-Attributions-Token (RevenueCat + Apple).
- Die in Abschnitt 2.2 beschriebene, **von Ihnen gestartete und bestätigte** Familienfreigabe — nur mit der Person, die Sie eingeladen haben oder deren Einladung Sie angenommen haben, über Apple iCloud.

---

## 7. Ihre Rechte nach der DSGVO (Nutzer in der EU)

Wenn Sie in der EU ansässig sind, stehen Ihnen nach der Datenschutz-Grundverordnung (DSGVO) die Rechte auf **Auskunft, Berichtigung, Löschung, Widerspruch gegen die Verarbeitung sowie Datenübertragbarkeit** zu. Unsere Rechtsgrundlagen sind: die Erforderlichkeit zur Erbringung des Dienstes (Article 6(1)(b)) sowie das berechtigte Interesse an der Fehlerberichterstattung (Article 6(1)(f)).

---

## 8. Ihre Rechte nach dem türkischen KVKK

Nach Artikel 11 des türkischen Datenschutzgesetzes (KVKK) stehen Ihnen unter anderem folgende Rechte zu: zu erfahren, ob Ihre Daten verarbeitet werden, Informationen anzufordern, eine Berichtigung oder Löschung zu verlangen, die Dritten zu erfahren, an die Daten übermittelt wurden, gegen Ergebnisse einer automatisierten Verarbeitung Widerspruch einzulegen sowie Schadensersatz zu verlangen. Um diese Rechte auszuüben, wenden Sie sich an <ilacvaktidestek@gmail.com>. Anfragen werden innerhalb von **30 Tagen** beantwortet.

---

## 9. Datenschutz für Kinder

Die App ist mit **4+** eingestuft. Es werden wissentlich keine Daten von Kindern unter 13 Jahren erhoben. Wenn ein Elternteil die App nutzt, um ein Kinderprofil (Familienmitglied) anzulegen, verbleiben die Profildaten ausschließlich lokal auf dem Gerät gespeichert.

---

## 10. Datensicherheit

Da Ihre Daten überwiegend auf Ihrem Gerät gespeichert werden, sind sie durch die Hardwareverschlüsselung von iOS (Secure Enclave) geschützt. Die Kommunikation mit Drittanbieterdiensten erfolgt verschlüsselt über HTTPS. Medikamentendaten in der iCloud-Sicherung und der Familienfreigabe liegen in Ende-zu-Ende-verschlüsselten Feldern von Apple CloudKit; niemand, auch nicht der Entwickler, kann sie lesen.

---

## 11. Änderungen dieser Erklärung

Wir können diese Erklärung von Zeit zu Zeit aktualisieren. Wesentliche Änderungen werden über eine In-App-Benachrichtigung oder die Versionshinweise bekannt gegeben. Bitte überprüfen Sie regelmäßig das Datum unter *Zuletzt aktualisiert*.

---

## 12. Kontakt

E-Mail: <ilacvaktidestek@gmail.com>
