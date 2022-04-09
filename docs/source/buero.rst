Büroanwendungen
===============

Empfohlene Büroanwendungen
--------------------------

- Dokumente/Rechnungen/Präsentationen/Tabellen erstellen: **Libre Office**, alternativ: **Only Office**
- Ausfüllen und (visuelles) Unterschreiben von PDFs: **Xournal++**
- Erstellen einfacher Protokolle, Notizen: **gedit**, `Markdown Exporter <https://www.markdowntopdf.com/>`_
- E-Mail Kommunikation (inklusive Vorlagen): **Thunderbird**
- Finanz-Buchhaltung: **GnuCash**
- Internet Browser: **Firefox**
- Kalender: **Kalender** (gnome-calendar)
- Meetings abhalten: **Jitsi**
- Team-Chat: **Rocket.Chat**
- Projektmanagement: **OpenProject**
- Synchronisation von Daten, Kalender, Organisation von Teams, ...: **Nextcloud**
- Virtuelle Klebezettel: **Notizen** (sticky)

Alternativen zu Microsoft Office
--------------------------------

Leider funktioniert bis jetzt Microsoft Office nicht unter Linux.
Dennoch gibt es mittlerweile zahlreiche Alternativen, die dies beheben.
Auch Sie werden Ihren vollwertigen Ersatz finden.

Libre Office
^^^^^^^^^^^^
Wir empfehlen ganz klar Libre Office. Es ist bei Linux Mint bereits vorinstalliert.
Libre Office hat Tonnen von Funktionen und deckt nahezu jeden erdenklichen Anwendungsfall ab:
Man kann Präsentationen, Formulare, Rechnungen, Vorlagen, Dokumentationen, funktionale Tabellen, Mathematische Formeln, Postkarten, Briefe und vieles mehr erstellen.

.. tip::
    Sollte Ihnen die Oberfläche nicht gefallen, kann man dies unter ``Ansicht -> Benutzeroberfläche`` einstellen.
    Unsere Empfehlung ist ``In Registern``. Diese Oberfläche bietet mehr Funktionen als die Standard-Oberfläche und erinnert stark an MS Office.

Einen Nachteil hat Libre Office jedoch: Die Kompatibilität zu Microsoft-Formaten wie .docx, .ppt oder .xls ist leider nicht so hoch.
Sollte man an diese angewiesen sein, empfehlen wir stattdessen entweder die  `Online-Variante von MS Office <https://www.office.com/>`_,
`Softmaker Office <https://www.softmaker.de/softmaker-office>`_ oder `Only Office <https://www.onlyoffice.com/de/download-desktop.aspx?from=desktop>`_.

Softmaker Office
^^^^^^^^^^^^^^^^
Viele Linux Nutzer sind mit dem kostenpflichtigen `Softmaker Office <https://www.softmaker.de/softmaker-office>`_ sehr zufrieden.
Das proprietäre Programm wird von einem Nürnberger Unternehmen entwickelt und bietet eine sehr hohe Kompatibilität zu den Microsoft Formaten.

Eine kostenlose Test-Version mit eingeschränkter, älterer Funktionalität gibt es auch: `FreeOffice <https://www.freeoffice.com/de>`_

Weitere Alternativen
^^^^^^^^^^^^^^^^^^^^
Weitere Alternativen zu MS Office sind unter anderem:

- `Online-Variante von MS Office <https://www.office.com/>`_
- `Google Docs <https://www.google.de/intl/de/docs/about/>`_
- `WPS Office <https://www.wps.com/de-DE>`_
- `Only Office <https://www.onlyoffice.com/>`_


Microsoft Schriftarten installieren
-----------------------------------
Viele Nutzer sind die Microsoft Schriftarten gewohnt und möchten diese unter Linux weiter nutzen.
Man kann die Schriftarten mit dem Paket ``ttf-mscorefonts-installer`` nachinstallieren (Beispielsweise über das Terminal oder den Synaptic Package Manager).

.. note::
    Hier muss man während der Installation die EULA-Lizenz akzeptieren:
    Den Haken im aufploppenden Fenster setzen und auf ``Next`` klicken.

Danach müssen alle Office-Anwendungen neu gestartet werden, damit diese die neuen Schriftarten erkennen.
