# 📊 Mijozlar Tahlili — Power BI Dashboard

Bu loyiha mijozlar xatti-harakatini 4 sahifali interaktiv Power BI dashboard orqali tahlil qiladi: umumiy ko'rsatkichlar, mijozlar segmentatsiyasi, kohort (ushlab qolish) tahlili va alohida mijozlar kesimi.

Tahlil davri: 2024–2025 (asosiy filtr: 2025 yil).

---

## 🎯 Loyiha maqsadi

- Daromad va faol mijozlar dinamikasini kuzatish
- Mijozlarni segmentlarga ajratish (Chempionlar, Sodiq, Xavf ostida va h.k.)
- Mijozlar birinchi xariddan keyin qanchalik ushlab qolinishini kohort tahlili bilan baholash
- Eng yirik mijozlarni aniqlash va ular bo'yicha batafsil ma'lumot olish

---

## 🗂 Dashboard sahifalari

Barcha sahifalarda Yil, Region va Kanal bo'yicha filtrlar mavjud.

### 1️⃣ Umumiy

<img width="1269" height="793" alt="image" src="https://github.com/user-attachments/assets/bed57336-1ad9-4efc-831e-a4300d67415c" />

Asosiy KPI ko'rsatkichlari (2025):

| Ko'rsatkich | Qiymat |
|---|---|
| Daromad | 1.93 mlrd |
| Faol mijozlar | 480 |
| Qaytgan mijozlar | 157 |
| Takroriy xarid | 76.29% |

Vizuallar:
- Qaytgan va Yangi mijozlar — oylar kesimida area chart
- Region bo'yicha daromad — Toshkent yetakchi, undan keyin Samarqand, Namangan, Farg'ona, Buxoro
- Yangi va Qaytgan mijozlar — donut chart (323 ta yangi — 67.29%, 157 ta qaytgan — 32.71%)
- Eng yirik mijozlar — buyurtmalar, daromad va segment bilan jadval

![Umumiy](images/1_umumiy.jpg)

### 2️⃣ Segmentlar

<img width="1280" height="788" alt="image" src="https://github.com/user-attachments/assets/bd27dd93-c528-4fa0-9a3c-97b554d5ce47" />


Mijozlar 6 ta segmentga ajratilgan:

| Segment | Mijozlar soni |
|---|---|
| Chempionlar | 103 |
| Sodiq | 154 |
| Xavf ostida | 110 |
| Yo'qotilgan | 131 |
| Xarid qilmagan | 39 |
| Yangi | 63 |

Vizuallar:
- Segment va jins bo'yicha daromad (ustunli diagramma)
- Segment × Region matritsasi (heatmap)
- Segmentlar jadvali: mijozlar soni, daromad, o'rtacha daromad, buyurtmalar soni, o'rtacha buyurtma

Asosiy kuzatuv: Chempionlar segmenti eng yuqori daromadni (≈738.6 mln) va eng yuqori o'rtacha buyurtmalar sonini (5.58) beradi.

![Segmentlar](images/2_segmentlar.jpg)

### 3️⃣ Kohortlar

<img width="1280" height="776" alt="image" src="https://github.com/user-attachments/assets/a1329bea-cb24-4e8d-898d-d8ce4c65e5c0" />


Birinchi xariddan keyin mijozlarni ushlab qolish (retention):

| Davr | Ushlab qolish |
|---|---|
| 1-oy | 30.51% |
| 3-oy | 27.00% |
| 6-oy | 22.07% |
| 11-oy | 15.44% |

Vizuallar:
- Kohort choragi bo'yicha retention matritsasi (2024 Q1 – 2025 Q4)
- Ushlab qolish egri chizig'i
- Kohort hajmi (48 tadan 98 tagacha o'sgan)
- Xulosa bloki

Asosiy xulosalar:
- Birinchi xariddan keyingi 1-oyda mijozlarning 30.51% qaytadi
- 2025 Q3 kohorti keyingi chorakda eng yuqori ko'rsatkichni (62%) ko'rsatdi
- 11-oyga kelib mijozlarning 15.44% faol qoladi

![Kohortlar](images/3_kohortlar.jpg)

### 4️⃣ Mijozlar

<img width="1280" height="790" alt="image" src="https://github.com/user-attachments/assets/9d4fcdf0-591f-493e-acf7-497cc8225cdc" />

| Ko'rsatkich | Qiymat |
|---|---|
| Jami mijozlar | 600 |
| Xarid qilgan | 561 (93.5%) |
| Xarid qilmagan | 39 (6.5%) |
| Yo'qotilgan (to'g'ridan) | 160 (xarid qilganlarning 28.5%) |

Vizuallar:
- Top 12 mijoz (2024–2025) — ID, ism, region, kanal, buyurtmalar, daromad, segment
- Mijozni tanlang paneli — tanlangan mijoz bo'yicha buyurtmalar, daromad, o'rtacha chek va oylik buyurtmalar dinamikasi

![Mijozlar](images/4_mijozlar.jpg)

---

## 🛠 Texnologiyalar

- Power BI Desktop — vizualizatsiya va dashboard
- DAX — hisoblangan ko'rsatkichlar (measures)
- Segmentatsiya va kohort tahlili

---

## 📁 Loyiha tuzilishi

├── images/              # dashboard skrinshotlari
├── dashboard.pbix       # Power BI fayli
└── README.md
---

## 📬 Aloqa

O'rinboyev Saidakbar — Data Analyst

- 💬 Telegram: [@saidakbar4751](https://t.me/saidakbar4751)
- 📞 Telefon: [+998 93 777 47 51](tel:+998937774751)
- 🐙 GitHub: [saidakbarorunboyev3-ai](https://github.com/saidakbarorunboyev3-ai)
