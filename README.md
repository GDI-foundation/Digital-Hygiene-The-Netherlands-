<a href="/"><img src="https://gdi.foundation/img/logo.png" alt="GDI.foundation" width="58" height="100" border="0" /></a>

# Digitale hygiëne

## Inleiding
Digitalisering creëert over de hele wereld en dus ook binnen Nederland nieuwe kansen en mogelijkheden. Door de afhankelijkheid tussen de digitale wereld en onze reële wereld neemt ook de impact van digitale kwetsbaarheden voor ons dagelijks leven toe evenals het misbruik van deze kwetsbaarheden door cyber criminelen. Maar wat is de status van de digitale hygiëne van Nederland? Hoe kwetsbaar zijn we en wat is de impact hiervan?

In 2017 heeft het NCSC heeft opdracht gegeven aan GDI.Foundation om big data uit openbare bronnen te analyseren. 
De GDI.Foundation heeft bijvoorbeeld in kaart gebracht welke en hoeveel ICT-systemen aan het internet zijn gekoppeld. Ook werd onderzocht of deze ICT-systemen zijn verbonden met het Internet of Things (IoT). U kunt het [hele rapport inzien](https://www.dcypher.nl/sites/default/files/uploads/documents/Rapport%20_Digitale%20Hygiene%20Nederland%20-%20Juni%202018_.pdf) op de website van Dcypher.

GDI.Foundation heeft onderzoek verricht naar het Nederlandse digitale landschap, het Internet-of-Things (IoT) en de kwetsbaarheden in het Nederlandse digitale landschap. In juni 2018 is het onderzoek afgerond. Het voornaamste risico, zo wordt geconcludeerd, is het ontbreken van structureel inzicht over de toekomstige ontwikkelingen van IoT, de nieuwe kwetsbaarheden die het met zich meebrengt en de combinatie met reeds bestaande IT-kwetsbaarheden. De volgende punten vormen volgens het onderzoeksrapport belangrijke meerwaarde om dreigingen en de impact hiervan te beheersen:

- het hebben van industrie standaarden, 
- securityratings van leveranciers & producten, 
- meetbare hardeningsguidelines en connectiviteit-eisen,
- “Security by design” en 
- “Privacy by design” in de levenscyclus van een product of dienst.

Dit is het vervolg van het onderzoek dat in 2017 is gestart. 

## Voorwoord
De Cyber Security Raad heeft eerder dit jaar gepleit voor: “Een onafhankelijke monitor van gehackte en kwetsbare IoT-apparaten, zodat publieke informatie beschikbaar komt over welke fabrikanten en leveranciers hun apparaten onvoldoende beveiligen.” De GDI.Foundation steunt dit advies en hoopt hier op korte termijn concreet vorm aan te geven.

## Hoe staat het er nu echt voor?
In dit onderzoek willen de volgende drie vragen proberen te beantwoorden:

1. Hoe ziet het Nederlandse digitale landschap eruit in het algemeen?
Hoeveel ICT-systemen zijn er in Nederland aan het internet gekoppeld? Wat voor systemen (smartphones, servers)? Wat draait er op (Windows, Android)? Welke diensten worden daarop aangeboden (www, dns, ssh, etc.)?

2. Hoe ziet het Nederlandse Internet-of-Things (IoT) eruit?
Steeds meer ICT-systemen behoren tot het zogenaamde Internet-of-Things (IoT), zoals beveiligingscamera’s en slimme thermostaten. Hoe groot is het Nederlandse IoT? Hoeveel en welke type IoT-devices zijn bereikbaar vanaf het Nederlands internet?

3. Welk percentage van Nederlandse ICT is kwetsbaar?
Nadat het Nederlandse digitale landschap (inclusief IoT) in kaart is gebracht, is het belangrijk om te weten welk deel hiervan kwetsbaar is. Welk deel draait op verouderd software of een biedt een verouderd versie van een dienst aan? Welk deel van het IoT maakt gebruik van een standaard wachtwoord?

## Scope
Het Nederlandse Internet bestaat uit bijna [44 miljoen IPv4 adressen](https://docs.google.com/spreadsheets/d/1KlEocs50wZXzTr8stk9NcLht0PPbAbHk-cqlGZWE86U/edit?usp=sharing) en {nog niet in kaart gebracht} IPv6 adressen. Natuurlijk worden niet alle addressen gebruikt. Ook verschuift het eigenaarschap van sommige IP blocks. Ook is de eigenaar van deze IPadressen meestal niet de “bewoner/gebruiker” van dat adres. Het eigenaarschap is onder te verdelen naar Netblock eigenaar, ISP/Webhoster/Reseller -  Gebruiker.  Nu hoeft de gebruiker niet altijd de eigenaar te zijn van de gegevens die op de host aanwezig is. In dit onderzoek kijken we dus niet naar de eigenaar maar naar het device dat aangesloten is aan het internet.

## Scanning index

### Webcams
* Open camera’s
* Kwetsbare camera’s
* Camera’s met default credentials

### Routers/Modems
* Kwetsbare devices in the Netherlands
* HUAWEI
* ZTE
* ZyXEL
* TP
* TP-Link
* D-Link devices 
* ARRIS DOCSIS 1.1 / SIP 2.0 Touchstone Telephony Modem)

### Apparaten met niet veilige instellingen met unsafe default credentials
* Password exposure in the banner
* Default password in the banner 

### Networking 
* Dnsmasq
* gSOAP 

### Communication
* E-mail
* Exim 

### IOT
* Hardware
* RasPI 
* Teapots
* Thermstat 
* ICY Clever Thermostat
* Heatmiser Wifi Thermostat
* NSTEON SmartLinc Home gateway
* Philips Hue lightning
* Dreambox (DVB) Digital TV/Radio
* Google ChromeCast

### Software
* Busybox

### Services
* MQTT
* TR-069
* Other

### Network Storage
* iOmega
* Other

### Printers
* Aangesloten printers 

### Bitcoin / Blockchain routing devices

* Bitcoin miners
  * ...

* Network forwarders
  * ...
  * Overig


#### Remote Desktop
Zonder wachtwoord
* RDP
* VNC
* Apple remote desktop

### Remote control
* OpenSSH

### Remote transfer protocollen
* FTP ( Global: 3.756.801 / NL: 66.600) online
* ProFTPD (Global: 614.999 / NL:  28.362)

### Mobile devices
#### Smartphones
* Android
* Apple IOs
* Other

### Windows Workstations / Servers
#### Operating systems
#### Version
#### Services with version banner

### Non-protected services (unsafe defaults)

* Databases
  * MySQL
  * PostgreSQL 
  * MongoDB
  * ElasticSearch 
  * Redis 
  * Cassandra 
  * CouchDB 
  * Services
  * Memcached

### Known data leaks
* MongoDB
* ElasticSearch 
* Redis
* FTP
* Rsync
* Mysql
* Open Webdirectories

### Industrial Control Systems
#### ICS
* IEC 60870-5-104

#### PLC
* Siemens  
* GE-SRTP 
* PLC Works 
* FINS 
* ProCroNos 

#### SCADA
* HART
* Red Lion 

#### DCS
* Modbus 
* DNP3 
* Niageria Fox 
* MELSEC-Q   

#### RTU
* BACnet
* EtherNET 
* CODESYS
