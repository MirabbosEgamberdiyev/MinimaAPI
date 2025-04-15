# 🚀 **MinimaAPI** — Faqat Modelni Yozing, Barcha Qolganini Avtomatlashtiring

**MinimaAPI** — bu **.NET 8** asosidagi backend loyiha shabloni bo‘lib, siz faqat **Model** klasslarini yozasiz, qolgan barcha komponentlar (CRUD endpointlar, DTO-lar, servislar, repozitoriyalar, autentifikatsiya, va global xatoliklarni boshqarish) avtomatik ravishda yaratiladi. Bu yondashuv dasturchilarga vaqtni tejashga va takrorlanuvchi backend kodlarni yozishdan qochishga yordam beradi.

## 🎯 **Maqsad**

**MinimaAPI** dasturchilarning vaqtini tejash va ishlab chiqish tezligini maksimal darajaga oshirish uchun mo‘ljallangan. Barcha takrorlanuvchi backend komponentlarini avtomatik ravishda yaratish orqali, faqat kerakli biznes logikasi va **Model** klasslarini yaratishga imkon beradi.

---

## ⚙️ **Texnologiyalar**

- **.NET 8** — Asosiy backend platforma
- **ASP.NET Core Web API** — RESTful API yaratish
- **Entity Framework Core** — Ma'lumotlar bazasi bilan ishlash
- **AutoMapper** — DTO va entity mapping
- **JWT Authentication** — Xavfsiz login va avtorizatsiya
- **Swagger (Swashbuckle)** — Avtomatik API hujjatlash
- **PostgreSQL** (yoki SQL Server) — Ma'lumotlar bazasi

---

## 📦 **Xususiyatlar**

- ✅ **Avtomatik CRUD endpointlar**: Faqat **Model** yozish orqali avtomatik CRUD endpointlar yaratiladi.
- ✅ **DTO va servislar**: Har bir **Model** uchun **DTO-lar** va **servislar** avtomatik generatsiya qilinadi.
- 🔐 **JWT autentifikatsiyasi**: Login, ro‘yxatdan o‘tish va token yangilash tizimlari.
- 🚫 **Global exception handler**: Xatoliklarni boshqarish uchun global tizim.
- 📄 **Swagger UI**: API hujjatlari avtomatik ravishda Swagger UI orqali taqdim etiladi.
- 🧪 **Test strukturalari**: Tayyor **unit** va **integration** testlari.
- 🌐 **Toza arxitektura**: Asosiy arxitekturaviy qatlamlar bo‘yicha to‘liq ajratilgan loyiha.

---

## 🚀 **Loyihani Ishga Tushirish**

1. **Repository’ni Klonlash**:

   ```bash
   git clone https://github.com/MirabbosEgamberdiyev/MinimaAPI.git
   cd minimaapi
