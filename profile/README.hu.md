# Paybill

**A Paybill** alapvető platformokat épít **modern SaaS rendszerekhez** és **biztonságos, AI-alapú alkalmazásokhoz**.

Fókuszunk a **kontroll, kiszámíthatóság és biztonság** — lehetővé téve, hogy a platformok és az ügynökök jól definiált keretek között működjenek, ahelyett, hogy ellenőrizetlen automatizálásra támaszkodnának.

---

## 🧭 Fókuszunk

A Paybill **két fő rendszer** köré épül, amelyek nagy léptékben oldják meg az infrastruktúra és az AI kihívásait:

### 1️⃣ Paybill Control Plane  
**Több-bérlős SaaS irányítás explicit módon.**

A `paybill-control-plane` egy élvonalbeli irányítási réteg, amely egyszerűsíti:

- Bérlők felvétele és életciklus-kezelése  
- Előfizetések, csomagok és licenc szintek kezelése  
- Automatizált bérlő-provisioning  
- Infrastruktúra-izolációs stratégiák  

Támogat **többféle izolációs modellt**:

- **Silo** – teljesen elkülönített infrastruktúra bérlőnként  
- **Pooled** – megosztott infrastruktúra logikai izolációval  
- **Bridge** – hibrid izoláció fokozatos skálázáshoz  

Az irányítási réteg mélyen integrálódik a felhőszolgáltatókkal és az infrastruktúra eszközökkel:

- AWS, Azure, Google Cloud, Oracle Cloud, IBM Cloud  
- Terraform-alapú provisioning  
- Adatbázis-orchestration és életciklus-kezelés  
- Számlázást figyelembe vevő provisioning munkafolyamatok  

> **Tervezési filozófia:**  
> Az infrastruktúrának *deterministának*, *auditálhatónak* és *előfizetés-tudatosnak* kell lennie — nem pusztán script-gyűjteménynek.

📦 **Fő repozitórium:**  
👉 `paybill-control-plane`

---

### 2️⃣ Paybill Framework  
**AI ügynökök ereje — kontroll megtartása mellett.**

A `paybill` egy TypeScript keretrendszer, amely lehetővé teszi, hogy **AI ügynökök biztonságosan és megbízhatóan** működjenek a termelési rendszerekben.

A szabad formátumú ügynökök helyett a Paybill érvényesíti:

- Kontrollált munkafolyamatokat  
- Explicit hozzáférés-kezelést (ACL)  
- Sémára épülő adatbázis-műveleteket  
- Kiszámítható végrehajtási határokat  

A keretrendszer egy kritikus kérdésre ad választ:

> *Hogyan engedhetjük az AI-t cselekedni — anélkül, hogy megtörné a rendszereket, adatot szivárogtatna, vagy megkerülné a szabályokat?*

Fő képességek:

- Erősen típusos sémák  
- Jogosultság-tudatos adatbázis-hozzáférés  
- Munkafolyamathoz kötött ügynök-akciók  
- Determinisztikus végrehajtási utak  

Ez a Paybill-t ideálissá teszi:

- AI által segített backendekhez  
- Autonóm belső eszközökhöz  
- Ügynök-vezérelt adatműveletekhez  
- Szabályozott vagy biztonságérzékeny rendszerekhez  

📦 **Fő repozitórium:**  
👉 `paybill`

---

## 🧠 Alapelvek, amik mentén építünk

- **Korlátok a szabadság felett**  
- **Munkafolyamatok a promptok felett**  
- **Sémák a feltételezések felett**  
- **Biztonság a tervezésben**  
- **Kiszámíthatóság nagy léptékben**

Nem *varázslatot* építünk.  
Olyan **rendszereket építünk, amiket értelmezni tudsz**.

---

## 🛠️ Technológiai stack

- **TypeScript** (alap nyelv)  
- **Terraform** (infrastruktúra-orchestration)  
- **Relációs adatbázisok** (séma-első tervezés)  
- **Felhőfüggetlen architektúra**  
- **Explicit ACL & szabályzati modellek**

---

## 🌍 Open Source & Közösség

A Paybill **nyílt forráskódú és közösség által vezérelt**.

Üdvözöljük:

- Infrastruktúra mérnököket  
- Platform mérnököket  
- SaaS architektokat  
- AI mérnököket, akik értékelik a biztonságot és a struktúrát  

Ha fontos számodra, hogy **felelősen skálázódó rendszereket építs**, itt otthon érezheted magad.

---

## 🤝 Hozzájárulás

Minden repozitórium tartalmaz:

- Egyértelmű hatásköröket  
- Véleményvezérelt architektúrát  
- Hozzájárulási útmutatót  

Kezdj az issue-kkal, beszélgetésekkel vagy tervezési javaslatokkal — a gondosan átgondolt hozzájárulás többet ér, mint a mennyiség.

---

## 📫 Kapcsolat

🌐 https://paybill.dev  
🐙 https://github.com/paybilldev  

---

**Paybill Fejlesztők**  
> *Irányítsd a platformot.  
> Korlátozd az ügynököt.  
> Skálázz magabiztosan.*
