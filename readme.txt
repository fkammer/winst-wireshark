== Installation Wireshark ==
Die Installation von Wireshark kann über den Schalter /S still durchgeführt
werden. Allerdings wird in diesem Fall nicht, wie bei der regulären Installation
WinPcap mitinstalliert (s. unten).

== Desktop-Icon und Quicklaunch-Icon ==
Während der Installation kann angegeben werden, ob ein Desktop-Icon und ob ein
Quicklaunch-Icon angelegt werden soll.

Desktop-Icon:
	/desktopicon=yes/no

Quicklaunch-Icon:
	/quicklaunchicon=yes/no

Beide Einstellungen können bei diesem Paket über eine ProductProperty gewählt
werden.

== WinPcap ==
Bei der regulären Installation wird WinPcap vom Wireshark-Installer direkt
mitinstalliert. Dies geschiet (warum auch immer) bei der Silent-Installation
nicht.

Aus dem offiziellen WinPcap-Installer der Open-Soure-Version wurde der Silent-
Schalter leider entfernt. Er ist nur noch im WinPcap-Pro-Installer enthalten.

Aus diesem Grund muss auf den inoffiziellen Installer der Windows-Version von
nmap zurückgegriffen werden. Der in diesem Paket verwendete Installer stammt aus
dem Windows Binary: http://nmap.org/download.html#windows