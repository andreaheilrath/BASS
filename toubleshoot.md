## Troubleshoot BASS-Devices

### Allgemeines

* Sollte das Problem nicht schnell lösbar sein, Ersatz-Device besorgen und in Ruhe troubleshooten.
* Have you tried turning it off and on again?

### Probleme und Lösungen
 * **kein WLAN:**
	1. Ist WLAN am Gerät an?
		-> falls nein, anschalten und prüfen ob das Problem behoben ist.
		-> falls ja, gehe zu 2.
	2. Haben andere Geräte in der Umgebung WLAN?
		-> falls ja, Streife anfunken und BASS-Device ersetzen
		-> falls nein (WLAN geht auch bei anderen Geräten nicht), Volkram / Nils anfunken
* **falsche App läuft**
	1. Von oben nach unten wischen um Benachrichtigung von Autostart and StaY! zu öffnen (Persist monitor task running.)
	2. In der Autostart and StaY! App die App bei der App auf EDIT klicken, die laufen soll (BASS-basic oder BASS-create).
	3. Persist aktivieren! Meldung, dass nur eine Persist-App erlaubt ist akzeptieren.
	4. Einmal zurück gehen und Persist Monitor aktivieren, evtl. Interval auf 1000ms stellen.
	5. Zurück auf den Home-Screen und irgendeine App öffnen. Nach einer Sekunde sollte BASS-basic oder BASS-create starten.
* **BASS-create lädt sehr lange**
	* Betrifft es nur ein BASS-Device -> Rouven (?) anfunken
	* Betrifft es alle BASS-Devices -> Volkram / Nils anfunken
* **BASS-Device Akku leer**
	* Powerbank anschließen
	* An Dockingstation anschließen (gibts in den PCR-Abstrich-Containern) / Device mit voll geladenen von dort austauschen)
* **BASS-create bleibt auf einer Farbe hängen**
	* _nicht_ die App beenden / neu starten
	* Gehe zu: Einstellungen -> Apps -> Bass-create -> Daten löschen -> App öffnen -> neu einloggen
	* Rouven anfunken und bescheid geben, dass das Problem aufgetreten ist.
* **BASS-basic zeigt widersprüchliche Daten an**
	* Checkt, dass Datum und Uhrzeit in der Leiste unten nicht länger als 30 Minuten her ist. Ansonsten nochmal die Systemzeit checken.
