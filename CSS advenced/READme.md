# CSS Kurs

## Kursda CSS bilim va ko'nikmalari olinadi.

## CSS Advenced:

# 2d - geometrik model bo'lib elementni joylashivini aniqlash uchun 2 ta nuqta yetarli bo'ladi.

## Transforms:

# Transmorm - veb sahifamizdagi elementlarni aylantrish,siljititsh,o'lchovini o'zgartirish, va og'dirish uchun ishlatiladigan CSS xossasi. Uning 2 ko'rinishi mavjud 2D va 3D.

### Transformerninf metodlari.(Rotate,Scale,Skew,Translate)

# Rotate- Elementni css da aylantrish.Elementimizni soat strelkasi yoki unga teskari bo'lgan yo'nalishda burish, (aylantrish) uchun ishlatiladi. Musbat qiymat soat strelkasi bo'yicha,manfiy esa teskari yo'nalishda buriladi.

# Scale - Elementimizni o'lchovini o'zgartirish.

# Skew - Elementimizni og'dirish.

# Translate - Elementimizni siljitish.

# Transform origin - O'zgartirish (transform) amal qiladigan nuqta/

## Transform origin xossalari:

# Center - burilish elemenni markaziga qarab.

# Top,left - bu tepa chapdan buriladi.

# Px da beriladi unga ko'ra.

# Bottom right,px - bunda pastdan o'ng va piksilda burilish.

# Translate - elementlarimizni hozirgi joyida siljitish (surish) uchun ishlatiladi.Musbat qiymat o'ng va pastga qarab,manfiy esa chap yuqoriga qarab siljitish uchun ishlatiladi.

# Scale - elementimizni o'lchovni oshirish yoki kamaytrish uchun ishlatiladi.0 bilan 1 orasida berilgan qiymat uning o'lchovini kamaytiradi, 1 dan katta qiymat esa o'lchovini oshiradi.

# Skew - elementimizni ma'lum bir darajaga (degree) ga og'dirish uchun ishlatiladi. Manfiy qiymat og'ish yo'nalishini teskari tomonga o'zgartiradi.

### 3d:

3d-geometrik model bo'lib elementimizning fazodagi joylashuvini aniqlash uchun 3 ta nuqtadan foydalaniladi.

## 3d transforms-veb sahifamizdagi elementlarni uch o'lchovlik fazoda aylantrih,siljitish,o'lchovini o'zgartirish hisoblanadi.

## 3d tranform uchun ishlatiladigan "metod" lar:

# rotate3d(aylantrish)-elementni fazoda ko'rsatilgan qiymatlar bo'yicha aylantrish uchun ishlatiladi.

# Perspective - element foydalanuvchidanqanday uzoqlikda turganini belgilab beradi.Qiymat qancha kichik bo'lsa,foydalanuvchi elementga shuncha yaqin bo'ladi.

# translate3d(siljitish) - elementning fazoda ko'rsatilgan qiymatlar bo'yicha siljitish uchun ishlatiladi.

# Scale - elementni fazoda ko'rsatilgan qiymatlar bo'yicha o'lchovini o'zgartirish uchun ishlatiladi.

# scale3d(o'zgartirish) - elementni fazoda ko'rsatilgan qiytmatlar o'lchovini o'zgartirish uchun ishlatiladi.

### Transtion - elementimizning xossa qiymatlatlarini ko'rsatilgan vaqt davomida ravon o'zgarishini ta'minlaydi. Transition yaratish uchun unga ikki qiymat ko'rsatilishi shart effekt qo'shmoqchi bo'lgab ellementimiz xossasi va effektning davomiyligi. Effektimiz davomiyligi son ko'rinishidagi qiymatga ega bo'lib,o'lchov birligi s (soniya) yoki ms (millisoniya)larda ko'rsatilishi kerak.

# ! Hamma CSS xossalari ham transtion effektiga ega bo'la olmaydi.Ko'rsatilgan havola orqali qaysi xossalarga transtion effektini ko'rsatish mumkin ekanligini bilib olishingiz mumkin.(Animatable Css properties(CSS Animation or CSS TRanstions))

## Transtion timing function - effektimizni tezligi qanday egri chiziqga ega bo'lishini belgilab beradi.

## Transtion timing functionning xossalari.

# ESSE - effektimiz sekin boshlanib, keyin tezlashib va yana sekinlik bilan tugaydi.

# Linear - effektimiz ko'rsatilgan vaqt davomida bir xil tezlikka ega bo'ladi.

# ESSE-in - effektimizni sekin boshlanadi.

# ESSE - out - effektimiz sekin tugaydi.

# ESSE - in - out - effektimizni sekin boshlanadi va sekin tugaydi.

# Cublic - bezeir(x,y,z,k) - cublic - beier funksiyasi orqali,ko'rsatilgan egri chiziq effektiga ega bo'ladi. x,y,z,k o'rniga qiymat ko'rsatiladi.

## Transtion delay - effektimiz qachon boshlanishini (kechikishini) belgilab beradi. Son ko'rinishidagi qiymatga egab bo'lib, o'lchov birligini s (soniya) yoki ms (millisoniyallarda) ko'rsatilishi kerak.
