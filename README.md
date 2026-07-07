# datenschutz-app-vinetime
Datenschutzerklärung

1. Allgemeine Hinweise und Pflichtinformationen
Der Schutz deiner persönlichen Daten ist uns ein ernstes Anliegen. Diese Datenschutzerklärung klärt dich über die Art, den Umfang und Zweck der Verarbeitung von personenbezogenen Daten innerhalb dieser mobilen Anwendung (nachfolgend „App“) auf. Der Betrieb dieser App erfolgt unter Beachtung der europäischen Datenschutz-Grundverordnung (DSGVO).

Verantwortlicher für die Datenverarbeitung:
Thomas Hupe
Rodenberger Str. 12
30459 Hannover
testwert@gmx.de

2. Datenverarbeitung und Speicherung
Die App kombiniert lokale Datenverarbeitung mit optionalen Cloud-Diensten zur Sicherung und Synchronisierung deiner Daten.

A. Lokale Speicherung:
Sämtliche von der App erfassten Artikeldaten, Inventarlisten und KI-generierten Such-Vektoren werden primär in einer geschützten SQLite-Datenbank lokal auf deinem Endgerät gespeichert.

B. Firebase Firestore & Authentication (Cloud-Sync):
Um deine Daten bei einem Gerätewechsel oder einer Neuinstallation wiederherzustellen, nutzt die App Google Firebase. Wenn du dich in der App anmeldest, werden deine Artikeldaten (inkl. Namen, Preise, Status und KI-Suchvektoren) verschlüsselt in der Google Firebase Firestore (Standort: EU) gespeichert. Der Zugriff erfolgt ausschließlich über dein persönliches, authentifiziertes Konto.

C. KI-Bildanalyse:
Die Bildanalyse zur Fotosuche erfolgt lokal auf deinem Gerät mittels TensorFlow.js. Die dabei erstellten mathematischen Fingerabdrücke (Vektoren) werden als Teil der Artikeldaten synchronisiert (siehe Punkt 2.B), um die Suchfunktion nach einer Neuinstallation sofort wieder verfügbar zu machen.

3. Nutzung von Drittanbietern und Diensten

A. Google AdMob (Werbung):
Die App nutzt Google AdMob, um Werbeanzeigen einzublenden. Google verwendet Werbe-IDs deines Endgeräts, um personalisierte oder nicht-personalisierte Werbung auszuspielen. Hierbei können Daten wie deine IP-Adresse und Geräte-Interaktionen an Google übertragen werden. Du kannst die Verwendung der Werbe-ID in deinen Android-Systemeinstellungen einschränken.

B. Firebase Analytics:
Zur Verbesserung der App-Stabilität und Fehleranalyse nutzen wir Firebase Analytics. Dabei werden anonymisierte Nutzungsinformationen (z.B. welche Funktionen wie oft genutzt werden) an Google übertragen. Es werden keine personenbezogenen Artikeldaten für Analysezwecke verwendet.

C. RevenueCat (Abonnements & Pro-Status):
Zur Verwaltung von In-App-Käufen und Abonnements wird der Dienst RevenueCat eingesetzt. Dabei wird eine anonyme ID verwendet, um deinen Kaufstatus (z.B. „Pro-Nutzer“) geräteübergreifend zu verifizieren. Es werden keine Zahlungsdaten (Kreditkarten etc.) durch den Entwickler oder RevenueCat gespeichert; diese verbleiben beim Google Play Store.

4. Google-Schnittstellen (Gmail & Drive)
Die App bietet optionale Funktionen, die eine Verbindung mit deinem Google-Konto erfordern (OAuth).

A. Gmail-Schnittstelle:
Auf deinen manuellen Wunsch hin liest die App Amazon-Vine-Bestellbestätigungen aus deinem Postfach aus. Diese Verarbeitung geschieht lokal auf deinem Smartphone. Nur die relevanten Bestelldaten werden in die App übernommen.

B. Google Drive-Schnittstelle:
Sofern aktiviert, nutzt die App einen isolierten Ordner auf deinem privaten Google Drive für Bilder und zusätzliche Backups oder Report-Exporte. Der Entwickler hat keinen Zugriff auf diesen Ordner.

5. Android-Berechtigungen
Internet (android.permission.INTERNET): Wird benötigt für Cloud-Sync, Werbung, Analytics und Google-Dienste.
Kamera (android.permission.CAMERA): Wird benötigt für die KI-Fotosuche und das Erfassen von Bildern.

6. Deine Rechte
Du hast das Recht auf Auskunft, Berichtigung und Löschung deiner Daten. Da die Cloud-Daten an dein Google-Konto gebunden sind, kannst du die Löschung der Cloud-Daten durch das Entfernen deines Kontos in der App oder durch Kontaktaufnahme mit dem Verantwortlichen einleiten. Lokale Daten werden durch Deinstallation der App gelöscht.

Solltest du Fragen zum Datenschutz haben, kannst du dich jederzeit an den oben genannten Verantwortlichen wenden. Zudem steht dir ein Beschwerderecht bei der zuständigen Aufsichtsbehörde zu.
