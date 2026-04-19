[english version](https://github.com/linksbuendig/unload-privacy/blob/main/README.md)
# Datenschutzerklärung — UnLoad

_Zuletzt aktualisiert: 19.04.2026_

Diese Datenschutzerklärung beschreibt, wie die mobile App UnLoad („UnLoad", „die App", „wir", „uns") personenbezogene Daten erhebt, verwendet und speichert. Mit der Erstellung eines Kontos und der Nutzung von UnLoad stimmen Sie den nachfolgend beschriebenen Praktiken zu.

## 1. Wer wir sind

UnLoad ist eine App für gemeinsame Haushalte, mit der Sie zusammen mit den Mitgliedern Ihres Haushalts Einkaufslisten, Rezepte und Essenspläne verwalten können.

- Entwickler: linksbuendig

## 2. Welche Daten wir erheben

Wir erheben und speichern nur die Daten, die für den Betrieb der App erforderlich sind.

### 2.1 Kontodaten
- E-Mail-Adresse
- Passwort (in gehashter Form durch Firebase Authentication gespeichert — das Klartextpasswort wird nie von uns gesehen oder gespeichert)
- Anzeigename

### 2.2 Haushalts- und Inhaltsdaten
- Haushalte, die Sie erstellen oder denen Sie angehören, einschließlich Name des Haushalts und Mitgliederliste
- Einträge auf der Einkaufsliste (Name, Menge, Einheit, Erledigungsstatus)
- Rezepte, die Sie erstellen oder importieren (Titel, Zutaten, Anweisungen, Bilder)
- Essensplan-Einträge (Datum, Mahlzeitentyp, Rezept oder Freitext)
- Einladungen, die Sie senden oder erhalten

### 2.3 Rezeptimport
Wenn Sie ein Rezept aus einer URL, einem Zwischenablage-Text oder einem Foto importieren, wird der Inhalt an unseren Importdienst gesendet und dort zu einem strukturierten Rezept verarbeitet. Der Inhalt wird verarbeitet, um das Rezept zu extrahieren, und zusammen mit dem importierten Rezept in Ihrem Konto gespeichert.

### 2.4 Technische Daten
- Von Firebase erzeugte Absturz- und Fehlerprotokolle zur Fehleranalyse
- Grundlegende Geräteinformationen, die zum Betrieb der App erforderlich sind
- Ein Offline-Cache auf Ihrem Gerät, damit die App auch ohne Internetverbindung funktioniert

Wir verwenden keine Werbe-IDs, zeigen keine Werbung und verkaufen Ihre Daten nicht.

## 3. Wie wir Ihre Daten verwenden

Wir verwenden die oben genannten Daten, um:

- Sie zu authentifizieren und Ihre Sitzung aufrechtzuerhalten
- Ihre Haushalte, Einkaufslisten, Rezepte und Essenspläne zwischen Ihren Geräten und anderen Haushaltsmitgliedern zu synchronisieren
- Einladungen an die von Ihnen angegebenen E-Mail-Adressen zu senden
- Rezepte zu importieren, die Sie aus URLs, Texten oder Bildern einreichen
- Abstürze zu analysieren und Fehler zu beheben

Wir verwenden Ihre Inhalte nicht für Profiling oder Werbung.

## 4. Wer Ihre Daten sehen kann

- **Sie selbst**: alle Daten in Ihrem Konto
- **Mitglieder Ihrer Haushalte**: die Inhalte der mit ihnen geteilten Haushalte (Einkaufsliste, Rezepte in diesem Haushalt, Essensplan, Mitgliederliste)
- **Personen, die Sie einladen**: ihre E-Mail-Adresse wird ausschließlich zur Zustellung der Einladung verwendet
- **Von uns eingesetzte Dienstleister** (siehe Abschnitt 6), ausschließlich zum Betrieb der App
- **Sonst niemand.** Wir verkaufen oder teilen Ihre Daten nicht mit Dritten zu Werbe- oder Analysezwecken.

## 5. Wo Ihre Daten gespeichert werden

Ihre Daten werden von Google Firebase (Authentication, Cloud Firestore und Cloud Storage) in der Google-Infrastruktur gespeichert. Je nach regionaler Firebase-Konfiguration können Daten in Rechenzentren innerhalb und außerhalb der Europäischen Union verarbeitet werden. Google stellt für internationale Datenübermittlungen geeignete Garantien bereit (z. B. Standardvertragsklauseln).

## 6. Dienstleister

Wir setzen die folgenden externen Auftragsverarbeiter ein:

- **Google Firebase** (Authentication, Firestore, Cloud Storage, gegebenenfalls Crashlytics) — Backend, Speicherung, Authentifizierung, Absturzberichte
- **Rezeptimport-Dienst** — Wenn Sie die Rezeptimportfunktion verwenden, werden die übermittelte URL, der Text oder das Bild an einen KI-basierten Parsing-Dienst gesendet, um das strukturierte Rezept zu extrahieren

Diese Anbieter verarbeiten Ihre Daten in unserem Auftrag und auf Grundlage eines Auftragsverarbeitungsvertrags.

## 7. Speicherdauer

- Konto- und Haushaltsdaten werden so lange gespeichert, wie Ihr Konto besteht.
- Wenn Sie einen Haushalt löschen, dessen Eigentümer Sie sind, werden dieser Haushalt und seine Inhalte entfernt.
- Wenn Sie Ihr Konto löschen, werden Ihr Benutzerprofil, die Haushalte, deren Eigentümer Sie sind, sowie Ihre Mitgliedschaft in anderen Haushalten entfernt. Inhalte, die Sie zu Haushalten anderer Eigentümer beigetragen haben (z. B. Einträge auf der Einkaufsliste oder Rezepte), können in diesen Haushalten verbleiben, da sie vom jeweiligen Eigentümer verwaltet werden.
- Absturzprotokolle werden gemäß den Firebase-Standardeinstellungen aufbewahrt (in der Regel bis zu 90 Tage).

## 8. Ihre Rechte

Wenn Sie sich in der EU/im EWR befinden, gewährt Ihnen die DSGVO folgende Rechte:

- Auskunft über die von uns gespeicherten personenbezogenen Daten
- Berichtigung unrichtiger Daten
- Löschung Ihrer Daten
- Datenübertragbarkeit in einem portablen Format
- Widerspruch gegen oder Einschränkung bestimmter Verarbeitungen
- Widerruf einer erteilten Einwilligung jederzeit
- Beschwerde bei einer Aufsichtsbehörde

Sie können Ihr Profil bearbeiten und Ihr Konto über den Einstellungen-Bildschirm in der App löschen.

## 9. Kinder

UnLoad richtet sich nicht an Kinder unter 13 Jahren (bzw. unter 16 Jahren in Rechtsordnungen, in denen dieses Alter maßgeblich ist). Bitte verwenden Sie die App nicht, wenn Sie unter diesem Alter sind.

## 10. Sicherheit

Wir verlassen uns auf die Sicherheitsfunktionen von Firebase (verschlüsselte Übertragung, verwaltete Authentifizierung, Firestore-Sicherheitsregeln), um Ihre Daten zu schützen. Kein System ist vollständig sicher — verwenden Sie ein starkes, einzigartiges Passwort und schützen Sie Ihr Gerät.

## 11. Änderungen dieser Erklärung

Wir können diese Datenschutzerklärung von Zeit zu Zeit aktualisieren. Bei wesentlichen Änderungen werden wir Sie vor Inkrafttreten in der App oder per E-Mail informieren. Das Datum „Zuletzt aktualisiert" am Anfang gibt die jeweils aktuelle Fassung an.

## 12. Kontakt

Bitte kontaktiere den Entwickler über den Play Store.
