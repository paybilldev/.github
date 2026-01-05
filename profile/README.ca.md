# Paybill

**Paybill** construeix plataformes fonamentals per a **sistemes SaaS moderns** i **aplicacions d’IA segures i guiades**.

Ens centrem en el **control, la predictibilitat i la seguretat** — permetent que les plataformes i els agents operin dins de límits clarament definits, en lloc d’una automatització sense control.

---

## 🧭 El nostre focus

Paybill es construeix al voltant de **dos sistemes clau** que resolen problemes complexos d’infraestructura i d’IA a gran escala:

### 1️⃣ Paybill Control Plane  
**Orquestració SaaS multi-tenant feta explícita.**

`paybill-control-plane` és un control plane d’última generació dissenyat per simplificar:

- Incorporació de tenants i gestió del cicle de vida  
- Gestió de subscripcions, plans i nivells de llicència  
- Aprovisionament automatitzat de tenants  
- Estratègies d’aïllament d’infraestructura  

Admet **múltiples models d’aïllament**:

- **Silo** – infraestructura completament aïllada per tenant  
- **Pooled** – infraestructura compartida amb aïllament lògic  
- **Bridge** – aïllament híbrid per a un escalat gradual  

El control plane s’integra profundament amb proveïdors de núvol i eines d’infraestructura:

- AWS, Azure, Google Cloud, Oracle Cloud, IBM Cloud  
- Aprovisionament basat en Terraform  
- Orquestració de bases de dades i control del cicle de vida  
- Fluxos d’aprovisionament conscients de la facturació  

> **Filosofia de disseny:**  
> La infraestructura ha de ser *determinista*, *auditable* i *conscient de la subscripció* — no una col·lecció d’scripts.

📦 **Repositori principal:**  
👉 `paybill-control-plane`

---

### 2️⃣ Paybill Framework  
**Donar poder als agents d’IA — sense perdre el control.**

`paybill` és un framework en TypeScript que permet que els **agents d’IA actuïn de manera segura i fiable** dins de sistemes en producció.

En lloc d’agents de forma lliure, Paybill imposa:

- Fluxos de treball controlats  
- Gestió d’accés explícita (ACL)  
- Operacions de base de dades guiades per esquemes  
- Límits d’execució predictibles  

El framework està construït per respondre una pregunta crítica:

> *Com permetem que la IA actuï — sense deixar que trenqui sistemes, filtri dades o eviti les regles?*

Les capacitats principals inclouen:

- Esquemes fortament tipats  
- Accés a bases de dades conscient de permisos  
- Accions d’agents lligades a fluxos de treball  
- Camins d’execució deterministes  

Això fa que Paybill sigui ideal per a:

- Backends assistits per IA  
- Eines internes autònomes  
- Operacions de dades impulsades per agents  
- Sistemes regulats o sensibles a la seguretat  

📦 **Repositori principal:**  
👉 `paybill`

---

## 🧠 Principis amb què construïm

- **Restriccions per sobre de llibertat**  
- **Fluxos de treball per sobre de prompts**  
- **Esquemes per sobre de supòsits**  
- **Seguretat per disseny**  
- **Predictibilitat a escala**

No construïm *màgia*.  
Construïm **sistemes que es poden raonar**.

---

## 🛠️ Pila tecnològica

- **TypeScript** (llenguatge principal)
- **Terraform** (orquestració d’infraestructura)
- **Bases de dades relacionals** (disseny schema-first)
- **Arquitectura agnòstica al núvol**
- **Models explícits d’ACL i polítiques**

---

## 🌍 Codi obert i comunitat

Paybill és **codi obert i impulsat per la comunitat**.

Donem la benvinguda a:
- Enginyers d’infraestructura  
- Enginyers de plataforma  
- Arquitectes SaaS  
- Enginyers d’IA que valoren la seguretat i l’estructura  

Si t’importa **construir sistemes que escalin de manera responsable**, aquí t’hi sentiràs com a casa.

---

## 🤝 Contribuir

Cada repositori inclou:
- Abast i responsabilitats clars  
- Arquitectura amb criteri  
- Directrius de contribució  

Comença amb issues, discussions o propostes de disseny — es valoren més les contribucions reflexives que no pas el volum.

---

## 📫 Contacte

🌐 https://paybill.dev  
🐙 https://github.com/paybilldev  

---

**Desenvolupadors de Paybill**  
> *Controla la plataforma.  
> Restringeix l’agent.  
> Escala amb confiança.*
