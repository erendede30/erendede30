# Merhaba, ben Eren Dede 👋

**Doğuş Üniversitesi Yönetim Bilişim Sistemleri (MIS)** öğrencisiyim. İlişkisel veri tabanı mimarisi, işlem güvenliği (ACID) ve Python tabanlı arka uç (backend) sistemleri geliştirme üzerine odaklanıyorum.

---

### 🛠 Teknoloji ve Araçlar

* **Veri Tabanı:** PostgreSQL, PL/pgSQL (Triggers & Functions), İlişkisel Veri Modelleme (ER), Sorgu Optimizasyonu, JSONB
* **Backend & Programlama:** Python, Flask, RESTful API, SQL, Pandas
* **Frontend:** HTML5, CSS3, JavaScript
* **Araçlar & Ortam:** Git, GitHub, PyCharm, Visual Studio Code, Linux

---

### 🚀 Öne Çıkan Proje

#### [LedgerFlow — ACID-Compliant Double-Entry Wallet Engine](https://github.com/erendede30/ledgerflow-postgres)
PostgreSQL ve Python (Flask) kullanılarak geliştirilmiş, çift taraflı muhasebe (double-entry bookkeeping) mantığına dayalı cüzdan ve para transfer motoru.
* `CHECK (balance >= 0)` ve `ON DELETE RESTRICT` kısıtlamalarıyla veri tabanı katmanında finansal bütünlük.
* Eşzamanlı işlemlerde yarış durumunu (race condition) ve kilitlenmeyi (deadlock) önleyen `SELECT ... FOR UPDATE` satır kilitleme algoritması.
* Bakiye değişimlerini eski ve yeni değerleriyle kaydeden otomatik `PL/pgSQL` & `JSONB` denetim tetikleyicileri (audit triggers).

---

### 📫 İletişim
* **GitHub:** [github.com/erendede30](https://github.com/erendede30)
