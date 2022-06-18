Remotezugriff
=============

Es gibt verschiedene Möglichkeiten, auf einen Rechner über das Netzwerk zuzugreifen.

Die einfachste und gängigste Methode unter Linux ist die *Secure Shell* (SSH).
Diese baut lediglich eine "Terminal"-Verbindung auf.
Für Server-Administratoren ist dies super, für uns als Anwender aber sicher wenig hilfreich.

Neben SSH gibt es noch weitere Methoden, sich mit dem Rechner zu verbinden. 
Eines der verbreitesten Protokolle ist das *Remote Desktop Protokoll* (RDP).
Dadurch kann man mit einem Programm auf den Desktop des entfernten Rechners zugreifen.

Entfernter Rechner
^^^^^^^^^^^^^^^^^^
Um auf unseren Rechner über die Ferne zuzugreifen, müssen wir auf diesem das Paket ``xrdp`` in bspw. Synaptic installieren.
Außerdem benötigen wir die IP-Adresse unseres Rechners, um auf diesen später zugreifen zu können.
Dies kann man ganz einfach in den Netzwerkeinstellungen unter dem Zahnrad ablesen (IPv4-Adresse bevorzugt).

.. note:: 
    Wenn die Firewall aktiv ist, muss man in den Firewall-Einstellungen die Anwendung 'RDP' erlauben.

Rechner vor Ort
^^^^^^^^^^^^^^^
Auf diesem Rechner muss das Programm ``Remmina`` installiert sein.
Bei Ubuntu ist das Programm schon vorinstalliert.

In Remmina fügen wir eine neue Verbindung links oben über das '+' hinzu:

- Als Protokoll wählen wir ``RDP - Remote Desktop Protokoll``
- Unter 'Server' tragen wir Dir IP-Adresse des entfernten Rechners ein.
- Als Benutzername und Passwort tragen wir die ganz normalen Anmeldedaten des entfernten Rechners ein. (Benutzername muss klein geschrieben sein)
- Unter Auflösung ist die Einstellung ``Auflösung des Client verwenden`` empfohlen.
- Am Ende können Sie auf ``Speichern und verbinden`` klicken.

Ein korrektes Einstellungsfenster sieht so aus:

.. image:: images/remmina_verbindungsprofil.png


Die Remote-Ansicht von Ubuntu sieht leicht anders aus. Bitte lassen Sie sich nicht davon irritieren. 
Zum Menü kommen sie immer über ``Aktivvitäten`` in der linken oberen Ecke.
Beenden tut man die Verbindung, in dem man sich "normal" abmeldet.
Möchte man sich danach wieder vor Ort auf dem Rechner anmelden, ist es empfohlen, den Rechner zuvor einmal neuzustarten.

.. image:: images/ubuntu_remote.png



.. note:: 
    Ein Benutzer kann grafisch nur einmal angemeldet sein. 
    Es ist nicht möglich, dass der gleiche Benutzer vor Ort und einmal entfernt gleichzeitig angemeldet ist.
    
    Auf dem entfernten Rechner sieht man auch nichts auf dem Bildschirm,
    wenn jemand aus der Ferne angemeldet ist.

    Die Rechner sollten miteinander im gleichen lokalen Netzwerk sein. 

.. tip:: 
    Richtet man zusätzlich eine VPN Verbindung ein, 
    kann man so ohne Probleme auch auf Rechner in hunderten km Entfernung zugreifen.

