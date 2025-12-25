# My APK Site (sadə nümunə)

Bu layihə sadə bir APK yükləmə və siyahılama saytının nümunəsidir.

Tələblər:
- Node.js 18+
- npm

Quraşdırma və işə salma:
1. `npm install`
2. `npm start`
3. Brauzerdə: `http://localhost:3000`

API:
- `GET /api/apks` — mövcud APK fayllarının siyahısı (metadata).
- `POST /api/upload` — APK yükləmək (form-data: `apk` fayl, isteğe bağlı `title` və `description`).
- `GET /download/:filename` — faylı yükləmək.

Qeyd:
- Bu nümunə sadədir və istehsalat üçün təhlükəsizlik, autentifikasiya və fayl yoxlamaları əlavə edilməlidir.
- Qanunlara və lisenziyaya zidd olmayan faylları paylaşın.
