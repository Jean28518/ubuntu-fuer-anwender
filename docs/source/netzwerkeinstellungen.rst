Netzwerkeinstellungen
=====================

Da das Erklären aller Netzwerkeinstellungen Tage benötigt
und man vieles als Anwender nie brauchen wird, beschränken wir uns hier auf reelle Anwendungsfälle.


WLAN Hotspot
------------
Es kann ein WLAN Hotspot erstellt werden, auf diesen sich weitere Geräte verbinden können, um ins Internet oder lokal zu kommunizieren.
Die Einrichtung ist selbsterklärend und kann in den Einstellungen im Abschnitt ``Netzwerk`` gefunden werden.


VPN einrichten
--------------

Es gibt viele verschiedene Möglichkeiten, sich zu einem VPN zu verbinden.
Jeder gute VPN-Anbieter sollte eine Anleitung für Linux liefern.
Die Installation von zusätzlichen Paketen ist hierfür häufig erforderlich.
Sollte hier Hilfe benötigt werden, können wir diese gerne im Kurs einrichten.


OpenVPN aus Datei
^^^^^^^^^^^^^^^^^

Gute Anbieter bieten eine .ovpn Datei zum Download an.
Diese kann man dann in den Netzwerkeinstellungen im Abschnitt ``VPN`` unter dem ``+ -> Aus Datei importieren...`` einlesen.
In der Regel muss man dann nur noch seine Anmeldedaten des VPN Anbieters eintragen.


DNS-Server umstellen
--------------------

Um eventuell schnellere DNS-Antworten zu bekommen, kann man einen anderen DNS-Server konfigurieren.
Dies kann man in den Einstellungen der jeweiligen Verbindung unter ``IPv4`` und/oder ``IPv6`` erledigen.
Ein möglicher DNS-Server ist beispielsweise `OpenDNS <https://www.opendns.com/>`_.
Unbedingt benötigt wird dieser Schritt aber nicht und bringt in der Regel keine nennenswerten Vorteile.