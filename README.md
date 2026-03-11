# Kindle_hacks
## My Kindle is version "PW2", current firmware 5.12.2.2

## jailbreak kindle  
### tba

## install KUAL
- Der Kindle muss bereits gejailbreakt sein (Dateien wie main-htmlviewer.tar.gz oder der Hotfix wurden bereits erfolgreich angewendet).
### Schritt 1
- Laden Sie die folgenden Pakete auf Ihren PC herunter:
  - MRPI (MobileRead Package Installer):
    - Funktion: Das Backend, das .bin-Installationspakete verarbeitet.
    - Link: [kual-mrinstaller-1.7.N.tar.xz ](https://www.mobileread.com/forums/showthread.php?t=225030)
    - my used version: here: https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/mr-public/KUAL/kual-mrinstaller-1.7.N-r19303.tar.xz
  - KUAL (Coplate/Booklet Version):
    - Funktion: Das grafische Menü zum Starten von Apps. Für FW > 5.5 wird die Booklet-Version benötigt.
    - [Link: KUAL-v2.7.36-g6136d8e-20240401.tar.xz](https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/mr-public/KUAL/KUAL-v2.7.37-gfcb45b5-20250419.tar.xz)
    - 

### Schritt 2: Dateien auf den Kindle übertragen
- Verbinden Sie den Kindle per USB mit dem PC.
- MRPI installieren:
- Entpacken Sie das MRPI-Archiv (z. B. mit 7-Zip).
- Kopieren Sie die Ordner extensions und mrpackages direkt in das Hauptverzeichnis (Root) Ihres Kindles. Falls sie bereits existieren, führen Sie sie zusammen.
- KUAL vorbereiten:
- Entpacken Sie das KUAL-Archiv.
- Suchen Sie die Datei Update_KUALBooklet_v2.7.36_install.bin (oder ähnlich benannt).
- Kopieren Sie diese .bin-Datei in den Ordner mrpackages, den Sie gerade auf den Kindle kopiert haben.

### Schritt 3: Installation auf dem Kindle auslösen
- Da Sie kein SSH haben, nutzen Sie das Suchfeld, um den Installer zu starten:
- Werfen Sie den Kindle sicher am PC aus und ziehen Sie das USB-Kabel ab.
- Tippen Sie auf dem Kindle oben in das Suchfeld.
- Geben Sie exakt den folgenden Befehl ein (inklusive Semikolon): `;log mrpi`
- Bestätigen Sie mit der Enter-Taste.
- Der Bildschirm wird flackern, und Textmeldungen des Installers erscheinen. Warten Sie, bis der Kindle die Benutzeroberfläche neu lädt.

### Schritt 4: Erfolgskontrolle
- In Ihrer Bibliothek sollte nun ein neues "Buch" namens KUAL erscheinen.
- Öffnen Sie KUAL. Wenn das Menü geladen wird, war die Installation erfolgreich.
- Sie können nun weitere Erweiterungen (z. B. KOReader) installieren, indem Sie deren .bin-Dateien in den Ordner mrpackages legen und erneut ;log mrpi ausführen.
