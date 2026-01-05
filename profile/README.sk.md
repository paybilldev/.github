# Paybill

**Paybill** buduje základné platformy pre **moderné SaaS systémy** a **bezpečné aplikácie poháňané AI**.

Zameriavame sa na **kontrolu, predvídateľnosť a bezpečnosť** — umožňujeme platformám a agentom fungovať v jasne definovaných hraniciach, namiesto nekontrolovanej automatizácie.

---

## 🧭 Naše zameranie

Paybill je postavený okolo **dvoch hlavných systémov**, ktoré riešia náročné problémy infraštruktúry a AI v rozsahu:

### 1️⃣ Paybill Control Plane  
**Viactenantná orchestrácia SaaS systémov explicitne.**

`paybill-control-plane` je špičková riadiaca platforma navrhnutá na zjednodušenie:

- Onboarding a životný cyklus tenantov  
- Správa predplatného, plánov a licenčných úrovní  
- Automatizované poskytovanie tenantov  
- Stratégie izolácie infraštruktúry  

Podporuje **viacero modelov izolácie**:

- **Silo** – úplne izolovaná infraštruktúra pre každého tenanta  
- **Pooled** – zdieľaná infraštruktúra s logickou izoláciou  
- **Bridge** – hybridná izolácia pre postupné škálovanie  

Riadiaca platforma sa hlboko integruje s poskytovateľmi cloudov a infraštruktúrnymi nástrojmi:

- AWS, Azure, Google Cloud, Oracle Cloud, IBM Cloud  
- Provisioning riadený Terraformom  
- Orchestrácia databáz a kontrola životného cyklu  
- Workflowy poskytovania služieb s ohľadom na fakturáciu  

> **Filozofia dizajnu:**  
> Infraštruktúra by mala byť *deterministická*, *auditovateľná* a *vedomá predplatného* — nie len zbierka skriptov.

📦 **Hlavné repozitórium:**  
👉 `paybill-control-plane`

---

### 2️⃣ Paybill Framework  
**Dáva AI agentom moc — bez straty kontroly.**

`paybill` je TypeScript framework, ktorý umožňuje **AI agentom pôsobiť bezpečne a spoľahlivo** v produkčných systémoch.

Namiesto voľne pôsobiacich agentov Paybill vynucuje:

- Kontrolované workflowy  
- Explicitné riadenie prístupu (ACL)  
- Operácie s databázou riadené schémou  
- Predvídateľné hranice vykonávania  

Framework je navrhnutý tak, aby odpovedal na kľúčovú otázku:

> *Ako umožniť AI konať — bez toho, aby narušila systémy, unikla dáta alebo obchádzala pravidlá?*

Hlavné schopnosti zahŕňajú:

- Silne typované schémy  
- Prístup k databáze s ohľadom na oprávnenia  
- Akcie agentov viazané na workflow  
- Deterministické cesty vykonávania  

To robí Paybill ideálnym pre:

- Backendové systémy asistované AI  
- Autonómne interné nástroje  
- Operácie s dátami riadené agentmi  
- Regulované alebo bezpečnostne citlivé systémy  

📦 **Hlavné repozitórium:**  
👉 `paybill`

---

## 🧠 Principy, podľa ktorých budujeme

- **Obmedzenia pred slobodou**  
- **Workflowy pred promptmi**  
- **Schémy pred predpokladmi**  
- **Bezpečnosť dizajnom**  
- **Predvídateľnosť vo veľkom meradle**

Nebudujeme *mágie*.  
Budujeme **systémy, nad ktorými môžete premýšľať**.

---

## 🛠️ Technologický stack

- **TypeScript** (hlavný jazyk)
- **Terraform** (orchestrace infraštruktúry)
- **Relačné databázy** (prístup „schema-first“)
- **Cloud-agnostická architektúra**
- **Explicitné ACL a modely politiky**

---

## 🌍 Open Source & komunita

Paybill je **open-source a riadený komunitou**.

Vítame:
- Infraštruktúrnych inžinierov  
- Platformových inžinierov  
- Architektov SaaS systémov  
- AI inžinierov, ktorí oceňujú bezpečnosť a štruktúru  

Ak vám záleží na **budovaní systémov, ktoré škálujú zodpovedne**, budete sa tu cítiť ako doma.

---

## 🤝 Prispievanie

Každé repozitórium obsahuje:
- Jasný rozsah a zodpovednosti  
- Názorovú architektúru  
- Pravidlá prispievania  

Začnite s issues, diskusiami alebo návrhmi dizajnu — kvalitné príspevky sú cennejšie než kvantita.

---

## 📫 Kontakt

🌐 https://paybill.dev  
🐙 https://github.com/paybilldev  

---

**Paybill Developers**  
> *Kontrolujte platformu.  
> Obmedzujte agenta.  
> Škálujte s dôverou.*
