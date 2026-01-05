# Paybill

**Paybill** gradi temeljne platforme za **sodobne SaaS sisteme** in **varne aplikacije, ki jih poganja AI**.

Osredotočamo se na **nadzor, predvidljivost in varnost** — omogočamo platformam in agentom delovanje znotraj jasno določenih meja, namesto nekontrolirane avtomatizacije.

---

## 🧭 Naš fokus

Paybill je zgrajen okoli **dveh ključnih sistemov**, ki rešujejo zahtevne infrastrukturne in AI izzive v velikem obsegu:

### 1️⃣ Paybill Control Plane  
**Večstanovanjska SaaS orkestracija, narejena jasna in pregledna.**

`paybill-control-plane` je napreden kontrolni sistem, zasnovan za poenostavitev:

- Onboarding in upravljanje življenjskega cikla najemnikov  
- Upravljanje naročnin, načrtov in licenčnih stopenj  
- Avtomatizirano zagotavljanje virov za najemnike  
- Strategije izolacije infrastrukture  

Podpira **več modelov izolacije**:

- **Silo** – popolnoma izolirana infrastruktura za vsakega najemnika  
- **Pooled** – deljena infrastruktura z logično izolacijo  
- **Bridge** – hibridna izolacija za postopno skaliranje  

Kontrolni sistem se globoko integrira s ponudniki oblačnih storitev in orodji za infrastrukturo:

- AWS, Azure, Google Cloud, Oracle Cloud, IBM Cloud  
- Provisioning z uporabo Terraform  
- Orkestracija in upravljanje življenjskega cikla baz podatkov  
- Delovni procesi z upoštevanjem obračunavanja  

> **Filozofija oblikovanja:**  
> Infrastruktura mora biti *deterministična*, *revizijska* in *zavedajoča se naročnin* — ne le zbirka skript.

📦 **Glavno repozitorij:**  
👉 `paybill-control-plane`

---

### 2️⃣ Paybill Framework  
**Omogoča AI agentom moč — brez izgube nadzora.**

`paybill` je TypeScript ogrodje, ki omogoča **AI agentom varno in zanesljivo delovanje** v produkcijskih sistemih.

Namesto prostorskih agentov Paybill uvaja:

- Nadzorovane delovne procese  
- Jasno upravljanje dostopa (ACL)  
- Operacije baz podatkov, vodene s shemami  
- Predvidljive meje izvajanja  

Ogrodje odgovarja na ključno vprašanje:

> *Kako dovolimo AI delovati — ne da bi sistem pokvarila, razkrila podatke ali obšla pravila?*

Ključne zmogljivosti vključujejo:

- Močno tipizirane sheme  
- Dostop do baz podatkov, občutljiv na dovoljenja  
- Dejanja agentov vezana na delovne procese  
- Deterministične poti izvajanja  

To naredi Paybill idealen za:

- AI-podprte backend sisteme  
- Avtonomna notranja orodja  
- Agenti, ki izvajajo podatkovne operacije  
- Regulatorne ali varnostno občutljive sisteme  

📦 **Glavno repozitorij:**  
👉 `paybill`

---

## 🧠 Principi, po katerih gradimo

- **Omejitve pred svobodo**  
- **Delovni procesi pred pozivi**  
- **Sheme pred domnevanji**  
- **Varnost po načelu oblikovanja**  
- **Predvidljivost v velikem obsegu**

Ne gradimo *magije*.  
Gradimo **sisteme, o katerih lahko razmišljate**.

---

## 🛠️ Tehnološki sklad

- **TypeScript** (osnovni jezik)  
- **Terraform** (orkestracija infrastrukture)  
- **Relacijske baze podatkov** (shema-prva zasnova)  
- **Neodvisna arhitektura oblačnih storitev**  
- **Jasni ACL & modeli politik**

---

## 🌍 Open Source & Skupnost

Paybill je **odprtokoden in voden s skupnostjo**.

Dobrodošli so:
- Infrastrukturni inženirji  
- Platformni inženirji  
- SaaS arhitekti  
- AI inženirji, ki cenijo varnost in strukturo  

Če vam je mar za **gradnjo sistemov, ki odgovorno skalirajo**, se boste tukaj počutili domače.

---

## 🤝 Prispevanje

Vsak repozitorij vključuje:
- Jasno določen obseg in odgovornosti  
- Mnenjsko arhitekturo  
- Navodila za prispevanje  

Začnite z issues, razpravami ali predlogi za oblikovanje — premišljeni prispevki so vredni več kot količina.

---

## 📫 Kontakt

🌐 https://paybill.dev  
🐙 https://github.com/paybilldev  

---

**Paybill Developers**  
> *Nadzorujte platformo.  
> Omejite agenta.  
> Skalirajte s samozavestjo.*
