# Fars dili — Claude üçün təlimat

Bu repozitoriya fars dili üzrə dərs materialları üçündür: dərsliklər, lüğətlər, çalışmalar.
Bu fayldakı qaydalara hər söhbətdə əməl et.

## Ünsiyyət

- Həmişə **Azərbaycan dilində** cavab ver. Farsca yalnız öyrədilən söz və cümlələrdə işlənir.
- Sadə, aydın izah et. Texniki terminləri lazım olmadıqca işlətmə, işlədəndə izah et.
- Bilmədiyin və ya yoxlaya bilmədiyin şeyi açıq de (məs. səsin tələffüzünü qulaqla yoxlaya bilməmək). Uydurma.

## Git qaydaları

- Bu repozitoriyada dəyişiklikləri **birbaşa `main` budağına** yaz və göndər.
- Hər yeni material əlavə olunanda kök `README.md`-dəki mündəricat cədvəlini yenilə.

## Qovluq quruluşu

- Dərsliklər: `dersler/<nömrə>-<mövzu>/` — içində hazır PDF, onu yaradan mənbə faylı (HTML/skript) və qısa `README.md`.
- Video lüğətləri: `lugetler/<qısa-ad>/` — PDF, videonun mətni, skript, `README.md`.

## Dərslik qaydaları

- Format: rəngli, öz dizaynında **A4 PDF**. Quruluş: üz qabığı → **lüğət (~20 söz)** → qaydalar → **çalışmalar** → **cavablar**.
- Dizayn əvvəlki fars dili dərsliklərinin üslubunda olsun (bax: aşağıdakı "Mövcud materiallar").
- **Yalnız istifadəçinin verdiyi qaydaları** yaz; öz tərəfindən yeni qayda əlavə etmə.
- Misalları və oxunuşları istifadəçinin yazdığı şəkildə saxla.
- Lüğətdə hər söz üçün: farsca yazılışı, Azərbaycan hərfləri ilə oxunuşu, mənası (lazım olanda qeyd).
- Texniki:
  - PDF-i HTML-dən brauzer (Playwright/Chromium) ilə yarat ki, fars hərfləri düzgün birləşsin və sağdan sola düzgün düzülsün.
  - Fars hərflərini (پ چ ژ گ ی ک) dəstəkləyən şrift işlət: məs. **Vazirmatn** və ya **Noto Naskh Arabic** (`@fontsource` paketləri). Latın mətni üçün **Inter / Montserrat** (Azərbaycan hərflərini, böyük Ə daxil, dəstəkləyir).
  - Hər səhifənin sığdığını və mətnin daşmadığını yoxla.

## Video lüğəti qaydaları (YouTube linkindən)

- Bütün sözlər videonun əvvəlindən sonuna, ilk səsləndikləri ardıcıllıqla; təkrarlanan söz bir dəfə, ayrıca "Dəfə" sütunu ilə.
- Sütunlar: **#**, **Farsca**, **Oxunuşu** (Azərbaycan hərfləri ilə), **Tərcümə** (videodakı mənasına görə), **Dəfə**.
- Nəticə A4 PDF olur və istifadəçiyə göndərilir.

## Mövcud materiallar

- `dersler/01-elifba-salamlasma/` — 1-ci dərs: əlifba (32 hərf), salamlaşma, «mən» (10 səh.).
- `dersler/02-saylar-aile/` — 2-ci dərs: saylar 0–10, fars rəqəmləri, ailə, «Bu nədir?» (8 səh.).
- Yeni dərslər bu iki dərsin dizaynında və davamı kimi hazırlanır (3-cü dərs → `dersler/03-...`). Hər iki dərs sıfırdan başlayanlar üçündür, müraciət "sən" formasındadır.

## Yeni qaydalar

İstifadəçi yeni qayda və ya üstünlük deyəndə (məs. "bundan sonra belə et"):
1. Onu bu fayla, uyğun bölməyə əlavə et (uyğun bölmə yoxdursa, aşağıdakı siyahıya).
2. Dəyişikliyi dərhal `main`-ə göndər.
3. İstifadəçiyə qısaca hansı qaydanı yadda saxladığını de.

### Əlavə olunmuş qaydalar (tarixlə)

- 2026-11-25 — Bu fayl yaradıldı.
