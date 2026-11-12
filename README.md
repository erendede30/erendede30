# Merhaba, ben Eren Dede 👋

**Doğuş Üniversitesi Yönetim Bilişim Sistemleri (MIS)** öğrencisiyim. İlişkisel veri tabanı mimarisi, işlem güvenliği (ACID), yüksek eşzamanlılık kontrolü ve Python tabanlı arka uç (backend) / veri ambarı sistemleri geliştirme üzerine odaklanıyorum.

🌐 **Canlı Web CV:** [erendede30.github.io](https://erendede30.github.io)

---

### 🛠 Teknoloji ve Araçlar

* **Veri Tabanı & Veri Mühendisliği:** PostgreSQL, PL/pgSQL (Triggers & Functions), ACID Transactions, Row-Level Locking, Star Schema, ETL Pipelines, Materialized Views, Window Functions, JSONB
* **Backend & Programlama:** Python, Flask, Pandas, RESTful API, SQL
* **Frontend:** HTML5, CSS3, JavaScript
* **Araçlar & Ortam:** Git, GitHub, PyCharm, Visual Studio Code, Linux

---

### 🚀 Öne Çıkan Projeler

#### 1. [LedgerFlow — ACID-Compliant Double-Entry Wallet Engine](https://github.com/erendede30/ledgerflow-postgres)
PostgreSQL ve Python (Flask) kullanılarak geliştirilmiş, çift taraflı muhasebe (double-entry bookkeeping) mantığına dayalı cüzdan ve para transfer motoru.
* `CHECK (balance >= 0)` ve `ON DELETE RESTRICT` kısıtlamalarıyla veri tabanı katmanında finansal bütünlük.
* Eşzamanlı işlemlerde yarış durumunu (race condition) ve kilitlenmeyi (deadlock) önleyen `SELECT ... FOR UPDATE` satır kilitleme algoritması.
* Bakiye değişimlerini eski ve yeni değerleriyle kaydeden otomatik `PL/pgSQL` & `JSONB` denetim tetikleyicileri.

#### 2. [MetricFlow — Automated ETL Data Warehouse & Analytics API](https://github.com/erendede30/metricflow-dw)
PostgreSQL Yıldız Şema (Star Schema) veri ambarı mimarisi ve Python Pandas tabanlı otomatik veri temizleme/aktarım (ETL) sistemi.
* `fact_sales` olgu tablosu ile `dim_date`, `dim_customers` ve `dim_products` boyut tablolarından oluşan analitik veri modeli.
* Mükerrer ve hatalı kayıtları filtreleyip 10.000+ satırı PostgreSQL `COPY FROM STDIN` protokolüyle milisaniyeler içinde yükleyen ETL hattı.
* `Materialized View` ve SQL `Window Functions` (`RANK`, `PARTITION BY`) ile aylık kategori KPI ve segment sıralaması sunan REST API.

---

### 📫 İletişim
* **Web CV:** [erendede30.github.io](https://erendede30.github.io)
* **GitHub:** [github.com/erendede30](https://github.com/erendede30)
