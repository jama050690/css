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

### CSS Animations:

# CSS Animations- elementni bir "style"dan boshqa "style"ga asta-sekinlik bilan o'tishini ta'minlaydi. Animation istalgan CSS xossani istalgan marta o'zgartrish imkonini beradi.

## Animation yaratish uchun ishlatiladigan CSS xossalari va qoidasi:

-   @keyframes
-   animation-name
-   animation-duration
-   animation-delay
-   animation-iteration-count
-   animation-direction
-   animation-timing-function
-   animation- fill-mode
-   animation-play-state
-   animation

## @keyframes-animatsiya stillarni qaysi qiymatga o'zgartrishni belgilab beradi.

@keyframes animatsiya-nomi {
keyframe-interval-1 {
xossa-1: qiymat-1:
xossa-2: qiymat-2:
....
xossa-n: qiymat-n:
}
}
keyframes-intervali-n {
xossa-1: yangi qiymat-1:
xossa-2: yangi qiymat-2:
...
xossa-n: yangi qiymat - n:

}

# Animatsiyamizga xoxlagan nomimizni bersak bo'ladi. Keyframe interval uchun esa 0-100% ga bo'lgan qiymatlarni ko'rsatib o'tishimiz mumkin. 0 dan 100% from va to kalit so'zlaridan foydalanishimiz mumkin.

## Animation name-elementimiz ega bo'ladigan animatsiya nomi @keyframe uchun ko'rsatilgan animatsiya nomi qiymat ko'rinishida ishlatiladi.

## Animation duration - animatsiyani qanday davomiylikga ega bo'lishini belgilab beradi. Son ko'rinishidagi qiymatga ega bo'lib,o'lchov birligi s (soniya) ms(millisoniya)larda ko'rsatilishi kerak.

# Animation delay-animatsiyamiz qachon boshlanishini (kechikishini) boshlab beradi. Son ko'rinishidagi qiymatga ega bo'lib,o'lchov birligi s(soniya) yoki ms(millisoniya)larda ko'rsatilishi kerak.

# Animation iteration count - animatsiyamiz necha marta qaytarilishini belgilab beradi. Default qiymkati 1ga teng.

# Animation direction-animatsiya odinga (forwards),orqaga (backwards) yoki almashish (alremate) qo'yilishini belgilab beradi.

# normal - animatsiya oldinga qarab qo'yiladi.

# Reverse - animatsiya orqaga qarab qo'yiladi.

# Alternate- aniamtiya birinchi oldinga keyin orqaga qarab qo'yiladi(qiymat animation-iteration-count 1 dan katta bo'lganda).

# Alternate - reverse - Animatsiya birinchi orqaga keyin esa oldinga qarab qo'yiladi.

## Animation timing function-animatsiya tezligi qanday egri chiziqga ega bo'lishini belgilab beradi.

# esse-animatsiya sekin boshlanib,keyin tezlashib va yana sekinlik bilan tugaydi.

# linear - anmatsiya ko'rsatilgan vaqt davomida bir hil tezlikga ega bo'ladi.

# esse-in - animatsiya sekin boshlanadi.

# esse-out- animatsiya sekin tugaydi.

# esse-in-out - animatsiya sekin boshlanadi va sekin tugaydi.

# cublic-bezier(x,y,z,k)-Cublic-bezier funksiyasi orqali, ko'rsatilgan egri chiziq animatsiyasiga ega bo'ladi(x,y.z.k) o'rniga qiymat ko'rsatiladi.

## Animation fill mode -animatsiya boshlanishidan oldin va tugagandan so'ng elementimiz o'zining oldingi xossalariga eg bo'ladi lekin quyidagi xossa orqali, bu holatni o'zgartirish mumkin.

# none(default(oldingi xossasi)) - animatsiya tugaganidan e=keyin elementning oldingi xossalariga tasir qilmaydi.

# forwards - element animatsiyaning oxirgi keyframe intervali tomonidan ko'rsatilgan xossalarga ega bo'ladi.

# backwords-element animatsiyaning birinchi keyframe interval tomonidan ko'rsatilgan xossalirga ega bo'ladi.

# both - elemetnt animatsiyaning birinchi va oxirgi keyframe interval tomonidan ko'rsatilgan xossalriga ega bo'ladi.

## Animation play state-nimatsiya qanday holatda ekanini belgilab beradi. Uning 2 qiymati mavjud: running (animatsiya davom etayotgan holat) va paused (animatsiya to'xtatib qo'yilgan holat)

## Animation-animatsiyaga tegishli bo'lgan xossalar uchun qisqartma(shorthand).

animation: name duration timing - function delay iteration-count fill-mode direction,play-state]
