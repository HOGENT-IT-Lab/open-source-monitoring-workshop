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


---

![bg left:100% 80%](./img/logo.png) <!-- Plaats voor logo voor openingsslide, foefel gerust met de sizes van de bg -->

---


# Meevolgen op:

https://hogent-it-lab.github.io/open-source-monitoring/slides <!-- URL naar de slides -->

<!-- ![QR bg right contain](./img/link_qr.png) QR-code naar de slides -->

---

# Wat is (open source) server monitoring?

- Monitoring = systemen bekijken 
- Bepaalde parameters in het oog houden (*metrics*)
- Real-time of historisch overzicht van gebeurtenissen



---

# Waarom monitoring?

- Knowledge is power!
- Problemen detecteren
- Problemen in hun geheel vermijden!
- Indrukwekkende dashboards...

---

# Mogelijkheden?

<!-- Hier een slide met letterlijk allemaal logo's -->

---

# Waarom open source??

- Inzage in de broncode
- Mogelijkheden tot customisation en aanpassing
- Actieve communities
- Mooi meegenomen: vaak gratis...

---

# Basic monitoring - what do we need?

- Manier om bepaalde metrics te gaan blootstellen
- Eventueel historische data gaan bijhouden
- Overzicht genereren van deze informatie 
- Optioneel: alerting!

---

# Metrics en hoe ze te verzamelen

- Prometheus:
- Node Exporter:

---

# Prometheus

---

# Node Exporter

---

# Dashboards, dashboards, dashboards

- We willen data gaan structureren
- Overzichtelijk maken
- Gevoel dat we in ons eigen command center zitten
- Tool: Grafana

---

# Grafana

- Custom dashboards maken
- Bestaande dashboards importeren en customizen
- Verbinden met de correcte data-sources (Prometheus)
- Optioneel: alerting instellen!

---

# Alerting

- Problemen vaststellen en inlichten
- Problemen proberen vermijden! (bv. 80% disk space volzet)
- Integratie met veelgebruikte software (Teams, Slack, Discord, ...)

---

# Availability checken

- Is mijn machine bereikbaar?
- Is mijn website nog online?
- Tool: Uptime Kuma!

---

# Uptime Kuma

---


# Praktische demo

- Disclaimer: geen productie-setting
- Indien interesse: source files inbegrepen in repo!
- Ter illustratie van mogelijkheden

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