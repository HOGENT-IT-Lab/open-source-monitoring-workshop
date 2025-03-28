---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

![bg left:40% 80%](./img/logo.png)

# **Open Source Monitoring**

Slides voor Open Source Monitoring workshop van het IT-lab



# Meevolgen op:

https://hogent-it-lab.github.io/open-source-monitoring/slides <!-- URL naar de slides -->

<!-- ![QR bg right contain](./img/link_qr.png) QR-code naar de slides -->

---

# Wat is (open source) server monitoring?

- Monitoring = systemen bekijken en gadeslagen
- Bepaalde parameters in het oog houden (*metrics*)
- Real-time of historisch overzicht van gebeurtenissen



---

# Waarom monitoring?

- Knowledge is power!
- Problemen detecteren
- Problemen in hun geheel vermijden!
- Indrukwekkende dashboards...

---

# Waarom open source??

- Inzage in de broncode
- Mogelijkheden tot customisation en aanpassing
- Actieve communities
- Mooi meegenomen: vaak gratis...

---

# Vandaag - introductie en voorbeelden

- Testomgeving demonstreren
- Tools kortstondig showcasen
- Disclaimer: geen productie-setting
- Ter illustratie van mogelijkheden

---


# Basic monitoring - what do we need?

- Manier om bepaalde metrics te gaan blootstellen
- Eventueel historische data gaan bijhouden
- Overzicht genereren van deze informatie 
- Optioneel: alerting!

---

# Metrics en hoe ze te verzamelen

- Metrics: komen in veel geuren en kleuren
- We willen metrics van kritische toestellen verzamelen
- Voorbeelden: memory usage, CPU usage, netwerkactiviteit, ...

---

# Prometheus

- Staat in voor het verzamelen van de data
- Instellingen voor de targets en frequentie
- Kan data ook historisch gaan bijhouden 
- Open Source!

---

# Node Exporter

- Installeren we op het te monitoren toestellen
- Onafscheidelijk van onze Prometheus instantie
- De Node-exporter zal bepaalde data blootstellen die we willen gaan zien
- Belangrijk: bescherm de eindpoint goed...

---

# Dashboards, dashboards, dashboards

- We willen data gaan structureren
- Overzichtelijk maken
- Gevoel dat we in ons eigen command center zitten
- Tool: Grafana

---

# Grafana

- Custom dashboards maken
- Bestaande dashboards importeren/stelen en customizen
- Verbinden met de correcte data-sources (Prometheus)
- Optioneel: alerting instellen!

---

# Alerting

- Problemen vaststellen en inlichten
- Problemen proberen vermijden! (bv. 80% disk space volzet)
- Integratie met veelgebruikte software (Teams, Slack, Discord, ...)
- Vandaag niet aan bod, maar kan zeker!

---

# Availability checken

- Is mijn machine bereikbaar?
- Is mijn website nog online?
- Tool: Uptime Kuma!

---

# Uptime Kuma

- Simpele applicatie die connectivity tests doet
- Mogelijkheden: ping tests, URL checks
- Ook: TCP/UDP poorten checken, ...

---

# Monitoring - advanced

- Er bestaat veel geavanceerde software (zowel FOSS als proprietary)
- Tech-stacks zoals ELK (Elasticsearch, Logstash, Kibana)
- Tools zoals Zabbix, Nagios, Icinga, ...

---

# Take aways

- Ga na wat voor jouw systeem belangrijk is
- Ga op onderzoek uit (blogs, YouTube, vage IT-Lab workshops, ...)
- Prutsen, prutsen, prutsen!