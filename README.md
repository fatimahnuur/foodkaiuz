

# 🥗 FoodKAI - Sun'iy Intellekt Asosidagi Shaxsiy Diyetolog

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B)
![YOLOv8](https://img.shields.io/badge/AI-YOLOv8-green)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)

**FoodKAI** — bu O‘zbekiston milliy taomlarini rasm orqali aniqlovchi va ularning kaloriyasini hisoblab, foydalanuvchiga sog‘lom ovqatlanish bo‘yicha tavsiyalar beruvchi intellektual tizim. Loyiha **Computer Vision** (Kompyuter ko‘rishi) texnologiyalari va mobil ilovalar integratsiyasini o‘z ichiga oladi.

---

## 🚀 Loyihaning Asosiy Imkoniyatlari

* 📷 **Taomni aniqlash:** Rasmdagi taom turini (Palov, Somsa, Shashlik va h.k.) real vaqt rejimida aniqlash.
* 🔥 **Kaloriya hisobi:** Aniqlangan taomning energetik qiymatini (kkal) va BJU (Oqsil, Yog', Uglevod) balansini ko'rsatish.
* 🤖 **Telegram Bot:** Tezkor foydalanish uchun Telegram bot integratsiyasi.
* 📱 **Mobil Ilova (Flutter):** Kunlik statistika, BMI hisobi va tarixni saqlash imkoniyati.
* ☁️ **Cloud Integration:** Barcha ma'lumotlar Firebase bulutli bazasida sinxronlanadi.

---

## 🛠 Texnologik Stek

Loyihada quyidagi zamonaviy texnologiyalardan foydalanildi:

| Yo'nalish | Texnologiya | Izoh |
| :--- | :--- | :--- |
| **Sun'iy Intellekt** | **YOLOv8 (Nano)** | Obyektlarni aniqlash (Object Detection) |
| **Dasturlash Tili** | **Python** | Modelni o'qitish va Telegram bot uchun |
| **Mobil Ilova** | **Flutter (Dart)** | Android va iOS uchun kross-platforma ilova |
| **Backend** | **Firebase** | Firestore Database & Cloud Storage |
| **Bot Framework** | **Aiogram 3.x** | Asinxron Telegram bot |

---

## 📊 Dataset va Model Natijalari

Modelni o'qitish uchun **1200+** ta original rasmdan iborat **"Custom Dataset"** yig'ildi va **Kaggle** platformasida (Tesla T4 GPU) o'qitildi.

### Qo'llab-quvvatlanadigan taomlar (Classes):
1.  🍛 Palov
2.  🥟 Somsa
3.  🍲 Sho'rva
4.  🍡 Shashlik
5.  🍗 Tovuq
6.  🍕 Pizza
7.  🥗 Grek Salati
8.  🥔 Kartoshka Chips
9.  🍇 Do'lma
10. 🥐 Cinnamon Rolls

### 📈 Natijalar:
* **mAP@50 (Aniqlik):** 99.5%
* **Inference Time:** ~1.7ms (juda tezkor)
* **Precision:** 99.9%

---

## 📂 Repozitoriy Tuzilishi

* `foodkaiuz_model/` - O'qitilgan YOLOv8 modeli fayllari (best.pt, best.tflite).
* `food_kai.zip` - Flutter mobil ilovasining to'liq manba kodi (Source Code).
* `food_kai_modelini_tekshirish.ipynb` - Modelni tekshirish va test qilish uchun Jupyter Notebook (Kaggle/Colab uchun).

---

## 💻 O'rnatish va Ishlatish

### 1. Modelni tekshirish
`food_kai_modelini_tekshirish.ipynb` faylini Google Colab yoki Kaggle-da oching va quyidagi kutubxonani o'rnating:
```bash
pip install ultralytics

```

### 2. Telegram Botni ishga tushirish

* Python o'rnatilganligiga ishonch hosil qiling.
* Kerakli kutubxonalarni o'rnating:
```bash
pip install aiogram ultralytics firebase-admin

```


* Bot tokenini va model yo'lini kodga kiriting va `main.py` ni ishga tushiring.

### 3. Mobil ilovani ishga tushirish

* Flutter SDK o'rnatilgan bo'lishi kerak.
* Zip faylni oching va terminalda quyidagi buyruqni bering:
```bash
flutter pub get
flutter run

```



---

## 👤 Muallif

**Isaqova Fotimaxon**

* Farg'ona Davlat Texnika Universiteti talabasi
* AI Student

---

⭐ **Agar loyiha sizga yoqqan bo'lsa, "Star" bosishni unutmang!**

```





```
