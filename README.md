# 🚗 AutoParts — Sistem de gestiune a unui magazin de piese auto

![Figma Design](https://img.shields.io/badge/Design-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Platformă](https://img.shields.io/badge/Platform%C4%83-Desktop%20App-2EA44F?style=for-the-badge)
![Versiune](https://img.shields.io/badge/Versiune-1.0.0-blue?style=for-the-badge)

> **Lucrarea Individuală nr. 1 — Varianta 30**  
> **Instituția:** IP Colegiul „Iulia Hasdeu” din Cahul  
> **Disciplina:** S.03.0.018 Planificarea aplicațiilor desktop  
> **Student:** Rusu Ilie | **Grupa:** P2521 | **Data:** 21.10.2026

---

## 🔗 Link către proiectul în Figma
👉 **[Deschide macheta interactivă AutoParts în Figma](https://www.figma.com/proto/yfnpD87GBeag0Qmj1DLfRa/LL4-Rusu-Ilie-Catalog-scolar?node-id=35-1544&p=f&t=uDduyB0UZAfWJATB-1&scaling=min-zoom&content-scaling=fixed&page-id=1%3A3&starting-point-node-id=35%3A1544)**

---


### 👥 Utilizatorii aplicației (Roluri)
* **Directorul magazinului** — monitorizare generală, rapoarte și administrare.
* **Vânzătorul-consultant** — căutarea pieselor, vânzare cu amănuntul și angro, rezervări.
* **Gestionarul** — recepția mărfii, organizarea pe rafturi și controlul stocurilor minime.
* **Clientul angro (service auto)** — comenzi cu prețuri preferențiale și limită de credit.
* **Contabilul** — facturare, evidența datoriilor și rapoarte financiare.
* 
## ⚙️ Funcționalități principale

1. **📦 Catalogul pieselor**
   * Evidența detaliată (cod producător, cod original OEM, denumire, fotografie, specificații).
   * Căutare rapidă după marcă, model, an, motorizare sau **seria VIN**.
   * Afișarea automată a pieselor echivalente de la alți producători (cu stoc și preț).
   * Importul cataloagelor și listelor de prețuri din fișiere **Excel**.

2. **🏭 Stoc și depozit**
   * Evidența stocurilor pe locații exacte (raft, nivel, cutie) și pe magazine.
   * Recepția mărfii prin scanarea codurilor de bare.
   * Alerte pentru stocuri minime și generarea automată a comenzilor către furnizori.

3. **💰 Vânzări**
   * Vânzare cu amănuntul (bon fiscal) și vânzare angro (factură fiscală).
   * Grilă de prețuri diferențiată pentru clienții angro, în funcție de volumul lunar.
   * Rezervarea pieselor și preluarea comenzilor pentru articolele aflate în drum.
   * Gestionarea limitei de credit și a termenelor de plată pentru service-urile partenere.

4. **🔄 Retururi și garanții**
   * Procesarea retururilor cu verificarea stării ambalajului și a termenului legal.
   * Evidența reclamațiilor în garanție și urmărirea statusului la furnizor.

5. **📊 Rapoarte și analiză**
   * Analiza vânzărilor pe categorii, producători, vânzători și clienți.
   * Identificarea stocului imobilizat (piese fără vânzări în ultimele 6 luni).
   * Monitorizarea datoriilor clienților angro și a termenelor depășite.

6. **🔒 Administrare și securitate**
   * Autentificare pe bază de roluri și permisiuni, cu blocare automată după 15 minute de inactivitate.
   * **Mod Offline:** funcționare fără conexiune la internet și sincronizare automată la reconectare.
   * Scurtături de la tastatură, ajutor integrat (`F1`) și sistem de actualizare automată a aplicației.
