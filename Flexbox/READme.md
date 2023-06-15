# CSS Kurs

## Kursda CSS bilim va ko'nikmalari olinadi.

## Flexbox:asoslari va terminlari:

# Flexbox-float yoki position xossalari yordamisiz veb sahifasida moslashuvchan (flexible) layout yaratishda yordam beradi. Boshqacha qilib aytganda,veb sahifadagi elementlarni joylashtrish uchun xizmat qiladi.Flexbox 2 asosiy elementlardan tashkil topgan: flex contaiener va flex items

# Flex container - display xossasi uchun flex qiymatiga ega bo'lgan elementga aytiladi.

# Flex items - veb sahifamizdagi flex container ota-onaga ega bo'lgan elementlar.

## Flexbox model asoslari quyidagilardan tashkil topgan: flex container,flex item,asosiy o'q(main axis),kesuvchi o'q(cross axis)

# Asosiy o'q (main axis)-flex modelning asosiy o'qi hisoblanadi va elementlarimiz shu o'qga nisbatan joylashadi. Gorizantal ko'rinishdan vertikal ko'rinishga ham o'tkazsa bo'ladi.

# Asosiy boshi/tugashi(amin start/end)-flex elementlarimiz asosiy boshi va tugashi orasida joylashadi.Asosiy o'qning uzunligi etib belgilanadi.

# Asosiy uzunligi (main size) - asosiy o'qga qarab flex elementlarimizning kengligi yoki balanfliki asosiy uzunlik hisoblanadi.Asosiy o'qning o'lchoviga qarab kenglik yoki balandlik

# Kesuvchining boshi/tugashi(cross start/end) flex liniyalarimiz kesuvchi boshi va tugashi orasida joylashadi.

# Kesuvchi o'z(cross axis)-asosiy o'qga perpendikulyar o'q hisoblanadi. Uning yo'nalishi asosiy o'qga bog'liq bo'ladi.

# Kesuvchi uzunligi (cross size) - kesuvchi o'qga qarab flex elementning kengligi va balandligi kesuvchi uzunlik hisoblanadi. Kesuvchi o'qning o'lchoviga qarab kenglik yoki balandlik kesuvchi uzunliki etib belgilanadi.

# CSS xossalari:

# Flex container:

-   Flex-direction
-   flex-wrap
-   flex-flow
-   justify-content
-   align-items
-   align-content

# Flex item:

-   order
-   flex-grow
-   flex-shrink
-   flex-basis
-   flex
-   align-self

# Flex-direction - asosiy o'qning yo'nalishini belgilab beradi va flex items shu o'qga nisbatan joylashganligi uchun, ularning ham yo'nalishi belgilanadi.

# flex-directioning xossalri:

# Row-elementlarimiz chapdan o'ngga qarab joshlashadi.

# Row-reverse - elementlarimiz o'ngdan chapga qarab joylashadi.

# Column- elementlarimiz tepadan pastga qarab joylashadi.

# Column-reverse - elementlarimiz pastdan tepaga qarab joylashadi.

---

# Flex-wrap - odatda flex elementlarimiz bilan liniyada joylashadi.

# Flex-wrapning xossalari:

# Wrap-elementlar tepadan pastga bir necha liniyaga bo'linib joylashadi.

# Wrap-reverse-elementlar pastdan tepaga bir necha liniyaga olib joylashadi.

---

# Flex flow-flex direction va flex wrap xossalari uchun qisqartma hisoblanadi.

# Justify content - asosiy o'qi bo'ylab elementlarni joylashuvini belgilaydi va qo'shimcha bo'sh joyni taqsimlashga yordam beradi.

# Justify contentning xossalari:

flex-start-elementlarimiz flex connatiner boshida joylashadi.

flex-end-elementlarimiz flex connatiner oxirida joylashadi.

center-elementlarimiz flex connatiner markazida joylashadi.

space-between-elementlarimiz flex connatiner bo'yicha teng taqsimlanadi. Birinchi elementimiz container boshida,oxirgi elementimiz esa container oxirida joylashadi.

spasce-around-elementlarimiz flex connatiner bo'yicha teng taqsimlanadi va har bir element atrofida teng masofa bo'ladi.Faqatgina birinchi,oxirgi element va container chegralari orasidagi masofa boshqa masofalardan farq qiladi.

space-evenly-elementlarimiz flex connatiner bo'yicha teng taqsimlanadi va har bir element atrofida teng masofa bo'ladi

## Flexbox:

# Flexbox container:

# Align-items - kesuvchi o'qi (cross axis) bo'ylab elementlarni joylashuvini belgilaydi.

# Align-items xossalari:

Stretch(default)-elementlarimiz "flex container"ni to'ldirish uchun cho'ziladi.

Center-elementlarimiz kesuvchi o'qning markazida joylashadi.

Flex-start-elementlarimiz kesuvchi o'qning boshida joylashashadi.

Flex-end-elementlarimiz kesuvchi o'qning oxirida joylashadi.

# Align-content-kesuvchi o'q (cross axis) bo'ylab flex container liniyalarni joylashuvini belgilaydi va qo'shimcha bo'sh joyni taqsimlashga yordam beradi.

Stretch(default)-elementlarimiz "flex container"ni to'ldirish uchun cho'ziladi.

Flex-start-elementlarimiz kesuvchi o'qning boshida joylashashadi.

Flex-end-elementlarimiz kesuvchi o'qning oxirida joylashadi.

Center-elementlarimiz kesuvchi o'qning markazida joylashadi.

space-between- flrx liniyalarimiz flex connatiner bo'yicha teng taqsimlanadi. Birinchi flex elementimiz container boshida,oxirgi elementimiz esa container oxirida joylashadi.

spasce-around- flex linyalarimiz connatiner bo'yicha teng taqsimlanadi va har bir element atrofida teng masofa bo'ladi.Faqatgina birinchi,oxirgi element va container chegralari orasidagi masofa boshqa masofalardan farq qiladi.

## space-evenly- flex linyalarimiz connatiner bo'yicha teng taqsimlanadi va har bir element atrofida teng masofa bo'ladi

## Flexbox-items xossalari:

# Order-flex container ichida flex items odatiy oqimga (flow) ko'ra joylashadi,ya'ni html kodda birinchi yozilgan flex item veb sahifasida ham birinchi keladi,lekin order xossasi bu oqimni o'zgartirishi mumkin va flex items ketma-ketligini blgilab beradi.(order xossasi son ko'rinishidagi qiymatni qabul qiladi va qiymat qancha kichik bo'lsa flex item boshqa "item"lardan oldinroqda kelaveradi)

---

# flex-grow-"flex item"ni kerak payti o'z o'lchovini qanday oshirishini belgilab beradi. U son ko'rinishidagi qiymat qabul qilib,bo'sh qolgan joyni qancha qismini egallashni ko'rsatib beradi. Default qiymat 0 hisoblanadi.

---

# Flex-shrink-"flex item"ni kerak payti o'z o'lchovini qanday kichraytrishni belgilab beradi. U son ko'rinishidagi qiymat qabul qilib, joy qomlayotgan payt element qanday suratda kichrayishini belgilab beradi. Dwfault qiymat 1 hisoblanadi.
