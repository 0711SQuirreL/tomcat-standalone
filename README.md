## Tomcat Standalone!

### Installation

1. Das war-File unter [\webapps](\webapps) ablegen
2. Port einstellen [\conf\server.xml](\conf\server.xml)

	_<Connector port="9090" protocol="HTTP/1.1"
		connectionTimeout="20000" redirectPort="8443" />_
3. Startparameter und Datenbankverbindung konfigurieren [\conf\web.xml](\conf\web.xml)
4. [startup.bat](\bin\startup.bat) ausführen

Please see [RUNNING.txt](RUNNING.txt) for more info.