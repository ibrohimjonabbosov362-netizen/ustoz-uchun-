# Geometriya olami 3D

2D shakllar, 3D jismlar, formulalar, Pifagor teoremasi va test. Sof HTML/CSS/JS: hech qanday oʻrnatish yoki build kerak emas.

## Fayllar
- `index.html`: butun sayt (barcha sahifalar shu faylda)
- `manifest.webmanifest`, `sw.js`, `icons/`: telefonga ilova kabi oʻrnatish va oflayn ishlash uchun

## 1. Kompyuterda tekshirish
Papkada terminal ochib: `python3 -m http.server 8000`, keyin brauzerda `http://localhost:8000`.
(`index.html` ni ikki marta bosib ochsangiz ham ishlaydi, faqat oʻrnatish va oflayn rejim ishlamaydi.)

## 2. GitHub ga yuklash
1. github.com da yangi repository oching (masalan `geometriya`).
2. Shu papkada:
```
git init
git add .
git commit -m "Geometriya sayti"
git branch -M main
git remote add origin https://github.com/FOYDALANUVCHI/geometriya.git
git push -u origin main
```
(`FOYDALANUVCHI` oʻrniga oʻz GitHub nomingizni yozing.)

## 3. Vercel ga ulash
1. vercel.com ga GitHub orqali kiring.
2. **Add New → Project** va `geometriya` repositorysini tanlang.
3. Sozlamalarni oʻzgartirmang (Framework: **Other**, Build Command boʻsh). **Deploy** ni bosing.
4. Bir daqiqada `https://geometriya-xxxx.vercel.app` manzili tayyor boʻladi. Keyin har safar `git push` qilsangiz sayt oʻzi yangilanadi.

## 4. Telefonga yuklab olish (ilova sifatida)
- **Android (Chrome):** saytni oching, sahifadagi **“Ilovani oʻrnatish”** tugmasini bosing yoki ⋮ menyu → **Install app / Add to Home screen**.
- **iPhone (Safari):** saytni Safari da oching → **Ulashish** tugmasi → **Add to Home Screen** (Bosh ekranga qoʻshish).

Oʻrnatilgach ikonka telefon ekranida paydo boʻladi, toʻliq ekranda ochiladi va internetsiz ham ishlaydi.
