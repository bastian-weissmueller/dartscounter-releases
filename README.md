# 🎯 Darts Counter

Eine App zum Zählen von Dart-Spielen (X01: 301, 501, …) — mit lokalem Mehrspieler,
Statistik, Sound-Kommentaren und einem Online-Modus für zwei Geräte. Die App ist
**ausschließlich für den privaten Gebrauch** gedacht und nicht in App-Stores
veröffentlicht.

> ℹ️ Weil die App nicht über den Google Play Store verteilt wird, installierst du
> sie als APK direkt auf dein Handy. Wie das geht und warum dabei Warnungen
> erscheinen, steht weiter unten unter **[Installation](#-installation)**.

---

## ✨ Funktionen

- **X01-Spiele** (301 / 501 / frei wählbarer Startwert) mit **Double Out** und
  **Single Out**.
- **Lokaler Mehrspieler** – mehrere Spieler an einem Gerät, mit Sets und Legs.
- **Checkout-Vorschläge** – die App zeigt mögliche Finish-Wege an.
- **Statistik** – Averages, Siege und Verlauf werden pro Spieler gespeichert.
- **Sound & Kommentare** – Score-Ansagen und Kommentare, in den Einstellungen
  ein-/ausschaltbar.
- **Online-Modus** – zwei Geräte spielen über eine gemeinsame Sitzung zusammen.
- **Automatische Updates** – neue Versionen werden beim App-Start erkannt und
  können direkt installiert werden (siehe **[Automatische Updates](#-automatische-updates)**).

---

## 📷 Screenshots

<!-- Screenshots später hier einfügen. Lege die Bilder z. B. unter docs/screenshots/
     ab und ersetze die Platzhalter durch Bild-Einbindungen, etwa:
     ![Startbildschirm](docs/screenshots/landing.png) -->

| Startseite | Spielerauswahl | Spiel |
|------------|----------------|-------|
| _📷 folgt_ | _📷 folgt_ | _📷 folgt_ |

---

## 📲 Installation

> Die App wird als **APK-Datei** verteilt. Für die allererste Installation sind ein
> paar Schritte nötig, weil das Handy Apps außerhalb des Play Stores besonders
> vorsichtig behandelt. **Das ist normal** – siehe
> **[Warum erscheinen Warnungen?](#-warum-erscheinen-warnungen)**.

### Schritt 1 – APK herunterladen
Lade dir die aktuelle `dartscounter-<version>.apk` herunter (du bekommst den Link
vom Entwickler bzw. aus dem Release-Bereich). Tippe die Datei anschließend an, um
die Installation zu starten.

_📷 folgt: Download-Ansicht_

### Schritt 2 – Installation aus dieser Quelle erlauben
Beim ersten Mal fragt Android, ob Apps aus dieser Quelle (z. B. deinem Browser
oder Messenger) installiert werden dürfen. Tippe auf **Einstellungen** und
aktiviere **„Apps aus dieser Quelle zulassen"**, dann zurück.

_📷 folgt: Dialog „Unbekannte Apps installieren"_

### Schritt 3 – Sicherheitswarnung bestätigen
Es kann eine Meldung von **Google Play Protect** erscheinen, die App sei
möglicherweise schädlich. **Das ist ein Fehlalarm** – warum, steht unten. Wähle
**„Details"** bzw. **„Trotzdem installieren"**, um fortzufahren.

_📷 folgt: Play-Protect-Hinweis_

### Schritt 4 – Fertig
Nach der Installation kannst du die App öffnen und loslegen. 🎉

---

## ⚠️ Warum erscheinen Warnungen?

Beim Installieren können zwei Hinweise auftauchen:

1. **„Apps aus unbekannten Quellen"** – erscheint, weil die App nicht aus dem Play
   Store kommt, sondern direkt als Datei installiert wird. Das ist bei jeder
   sideloaded App so.
2. **Google Play Protect: „App könnte schädlich sein"** – das klingt dramatisch,
   ist aber eine **Vorsichts-/Reputations-Warnung, kein Virenfund.**

**Warum wird gerade diese App markiert?** Vor allem wegen der **Auto-Update-Funktion.**
Damit die App sich selbst aktualisieren kann, braucht sie die Berechtigung, Apps zu
installieren. Diese Berechtigung ist ein typisches Muster, das Play Protect genauer
prüft – völlig unabhängig davon, was die App tatsächlich tut. Dazu kommen:

- Die App wird **außerhalb des Play Stores** installiert.
- Sie ist auf **sehr wenigen Geräten** installiert, Play Protect „kennt" sie also
  nicht (unbekannte Reputation → vorsichtshalber Warnung).
- Sie ist mit einem **privaten Signatur-Zertifikat** signiert, nicht über ein
  Store-Konto.

**Ist die App schädlich? Nein.** Es handelt sich um eine private Dart-App ohne
schädliche Funktionen. Die Warnung ist die Folge davon, dass sie privat verteilt
wird und sich selbst aktualisieren darf – nicht davon, dass etwas Bösartiges darin
steckt. Eine vollständig warnungsfreie Installation gäbe es nur über den Play Store,
der sich mit dem Selbst-Update-Ansatz jedoch nicht verträgt.

Der Hinweis kann auch beim späteren automatischen Update noch einmal erscheinen –
dann gilt dasselbe: bewusst **„Trotzdem installieren"** wählen.

---

## 🔄 Automatische Updates

Ab dieser Version musst du neue Versionen **nicht mehr manuell** zugeschickt
bekommen:

- Beim **Start der App** wird geprüft, ob eine neuere Version verfügbar ist.
- Wenn ja, erscheint ein Hinweis **„Update verfügbar"** mit den Neuerungen.
- Mit **„Aktualisieren"** wird die neue Version heruntergeladen und installiert
  (einmalig musst du ggf. wieder die Installation erlauben, Schritt 2 oben).
- Mit **„Später"** kannst du normal weiterspielen (außer das Update ist als
  erforderlich markiert – dann bitte zuerst aktualisieren).

Ist keine Internetverbindung da oder gibt es kein Update, startet die App einfach
ganz normal.

### Hinweis für bestehende Nutzer (einmalig)
Wenn du bereits eine **ältere Version** hattest, die noch ohne Auto-Update
verteilt wurde, musst du diese **einmalig deinstallieren** und die neue APK frisch
installieren. Grund: Die neue Version ist anders signiert und lässt sich nicht
„drüber" installieren. **Dabei gehen lokale Statistiken und gespeicherte Spiele
verloren.** Das passiert nur dieses eine Mal – alle folgenden Updates installieren
sich ohne Deinstallation und ohne Datenverlust.

---

## 🔒 Hinweis

Private App, nur für den eigenen Gebrauch. Keine Veröffentlichung in App-Stores
vorgesehen.
