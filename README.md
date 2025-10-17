# 🌡️ Temperaturregulator med PID-kontroll
**Fagskoleprosjekt – Høst 2025**

Et semesterprosjekt ved [Fagskolen i Viken] for å utvikle et komplett system for **temperaturregulering basert på PID-kontroll**.  
Systemet består av et egendesignet PCB med innebygd varmesløyfe, temperatursensor og mikrokontroller (ESP32 med MicroPython).  
Prosjektet demonstrerer hvordan PID-regulering kan stabilisere temperatur i et tregt system med ytre forstyrrelser, som f.eks. vifte eller varmelekkasje.

---

## 🧠 Prosjektbeskrivelse

Prosjektet kombinerer **teori, simulering og praktisk implementering** for å bygge et fysisk system som kan:
- Regulere temperatur ved hjelp av P-, PI- og PID-algoritmer  
- Vise sanntidsdata via **webgrensesnitt** (Web UI)  
- Samhandle lokalt via **LCD-skjerm, knapper og vribrytere**  
- Logge temperaturforløp og PID-respons  
- Sammenlignes med simulering i **MATLAB/Simulink**

---

## ⚙️ Systemkomponenter

| Komponent | Beskrivelse |
|------------|-------------|
| **ESP32 (MicroPython)** | Mikrokontroller som kjører PID-algoritmen |
| **PCB med varmesløyfe** | Integrert varmeelement og temperatursensor |
| **Strømforsyning** | Ekstern 5–12 V forsyning for stabil drift |
| **Vifte / forstyrrelse** | Simulerer kjøling eller ekstern påvirkning |
| **Webportal (UI)** | Sanntidsgraf, parameterjustering og datalogging |
| **MATLAB/Simulink** | Brukt til simulering, tuning og analyse av PID-oppsett |

---

🧩 Mål og læringsutbytte

- Forstå praktisk bruk av PID-regulering i termiske systemer  
- Lære tuningmetoder (manuell og Ziegler–Nichols)  
- Sammenligne simulert og fysisk respons  
- Mestre bruk av GitHub til samarbeid og dokumentasjon  
- Koble teori (modellering) og praksis (implementering)

---

## 🗂️ Mappestruktur

```

fagskolen-pid/
│
├── pcb/                → PCB-design, komponentliste og skjema
├── code/               → MicroPython-kode for PID-regulering
├── webui/              → Frontend-filer for Web UI
├── matlab/             → Simuleringer og analyser
├── docs/               → Rapport, presentasjon og bilder
└── README.md           → Prosjektbeskrivelse (denne filen)

````

---

## 🧰 Installasjon og oppsett



## 🧪 Testing og simulering

* MATLAB/Simulink brukes til å simulere varmesystemets treghet og PID-respons.
* Faktiske målinger fra PCB kobles inn via UART eller WiFi.
* Temperaturdata logges og sammenlignes i grafer.

---

## 📜 Lisens

Dette prosjektet er lisensiert under [MIT License](LICENSE).

---

© 2025 – Fagskolen i Viken
Prosjektgruppe: Håkon Hjertnes Simonsen, Stian Emil Johansen, Francis Billy Rath
