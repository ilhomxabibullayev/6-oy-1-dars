.1 NPM

Agar "npm nima" deb so'rasangiz, bu **Node Package Manager** (npm) haqida savol berayotganingizni anglatadi.

**npm** – bu **Node.js** uchun rasmiy paket menejeri. Node.js dasturlash muhitida ishlatiladigan kutubxonalar, modullar va asboblarni osonlik bilan o'rnatish va boshqarish imkonini beradi. npm orqali siz loyihangizdagi barcha tashqi bog'liqliklarni (dependencies) boshqarishingiz mumkin.


- **npm install [paket-nomi]**: Berilgan paketni o'rnatish.
- **npm init**: Yangi `package.json` faylini yaratish.
- **npm update**: Paketlarni yangilash.
- **npm run [skript-nomi]**: `package.json` faylida aniqlangan skriptni ishga tushirish.

Agar sizning savolingizda boshqa biror ma'no bo'lsa yoki "nima" so'zi boshqa bir narsaga ishora qilsa, iltimos, batafsilroq tushuntirib bering, shunda sizga yaxshiroq yordam bera olishim mumkin.

.2 NODE

**Node.js** – bu ochiq manba kodli, server tomonida JavaScript ishlatishga imkon beruvchi platformadir. U **V8 JavaScript engine** (Google Chrome’dagi JavaScript dvigatelidan foydalanadi) asosida ishlaydi va yuqori samarali, kengaytirilgan va bir vaqtning o'zida ko'p mijozlarga xizmat ko'rsatish imkoniyatiga ega.

Node.js server dasturlari, web ilovalar, real vaqtda ishlovchi ilovalar, chat tizimlari va boshqa ko'plab tarmoqlar uchun ishlatiladi. U asosan **event-driven** va **non-blocking I/O model**ni qo'llab-quvvatlaydi, bu esa yuqori yuk ostidagi tizimlarda juda samarali ishlashini ta'minlaydi.

- **Asinxron va notekis ishlash**: Node.js asinxron ishlaydi, ya'ni kod bir vaqtning o'zida ko'plab so'rovlarni bajarish imkoniyatiga ega.
- **Yuqori samaradorlik**: V8 JavaScript dvigateli yordamida ishlaydi, bu esa uni juda tez qiladi.
- **JavaScript server tomonida**: Node.js JavaScript tilini server tomonida ham ishlatish imkonini beradi, bu esa frontend va backend dasturlashni bir xil tilda yozishga imkon yaratadi.
- **Keng kutubxonalar**: npm (Node Package Manager) orqali juda ko'plab modullarni o'rnatish mumkin, bu esa rivojlantirish jarayonini osonlashtiradi.

- **Web serverlar** (Express.js kabi framework’lar bilan).
- **RESTful API'lar**.
- **Real-time ilovalar** (masalan, chat tizimlari).
- **File system operatsiyalari**.
- **Streaming va media serverlar**.


Node.js yordamida JavaScriptni server tomonida ishlatish mumkin. Bu dasturchilarga ko'plab imkoniyatlar yaratadi, chunki ular bir xil tilni frontend va backendda ishlatishi mumkin, va bu platforma juda samarali va keng qo'llaniladigan bo'lib, zamonaviy web ilovalarini yaratishda muhim rol o'ynaydi.

.4 REACT

**React** — bu **JavaScript kutubxonasi**, asosan **foydalanuvchi interfeyslari (UI)** yaratish uchun mo'ljallangan. Uni **Facebook** (hozir Meta) tomonidan ishlab chiqilgan va hozirda dunyoning eng mashhur front-end texnologiyalaridan biri bo'lib, keng qo'llaniladi. React'ni asosan **single-page applications (SPA)** va dinamik web-ilovalar yaratish uchun ishlatishadi.

   - Reactda ilovalar **komponentlar** orqali quriladi. Har bir komponent — bu o'z ichida UI va uning logikasini saqlaydigan, qayta ishlatiladigan bir qismdir. Komponentlar boshqa komponentlarga ulanib, katta va murakkab interfeyslarni yaratadi.

   - React **Virtual DOM** (Virtual Document Object Model) texnologiyasidan foydalanadi. Bu — asl DOMning yengil versiyasi bo'lib, React dasturlari ma'lumotlar o'zgarganda faqat o'zgarishlar qayta render qilishga harakat qiladi, shu tariqa tezlik va samaradorlikni oshiradi.

   - Reactda ma'lumotlar bir yo'nalishda uzatiladi — bu degani, yuqoridan pastga (parentdan childga) komponentlar orqali uzatiladi. Bu boshqaruvni va xatoliklarni kamaytiradi.

   - JSX — bu React’ning o'ziga xos sintaksisi bo'lib, unda HTML va JavaScript kodlari birlashtiriladi. JSXni ishlatish orqali, siz HTMLni JavaScript kodida yozishingiz mumkin.

   - **Hooks** — bu React komponentlariga holat (state) va boshqa React funksiyalarini, sinflar (class) ishlatmasdan, ishlatish imkonini beradi. Masalan, `useState`, `useEffect` kabi hooklar.


   - React juda kuchli ekotizimga ega: unga integratsiya qilish uchun ko'plab kutubxonalar va vositalar mavjud (masalan, **React Router** — marshrutizatsiya, **Redux** — holatni boshqarish).

React ilovasi yaratish uchun, ko'pincha **Create React App** nomli vosita ishlatiladi, bu React dasturini boshlashni juda osonlashtiradi. Masalan:


Bu buyruqlar yordamida yangi React ilovasi yaratilib, uni o'z brauzeringizda ko'rishingiz mumkin.

- **Tezlik**: Virtual DOM va samarali qayta render qilish usuli Reactni juda tez ishlashiga yordam beradi.
- **Kengaytirilgan ekotizim**: React uchun turli kutubxonalar va vositalar mavjud, bu esa dasturchilarga keng imkoniyatlar yaratadi.
- **Qayta ishlatish**: Komponentlar yordamida kodni qayta ishlatish va boshqarishni osonlashtiradi.
- **Keng jamoa**: React global miqyosda keng qo'llaniladi, shuning uchun sizga yordam olish oson.

- **Single-page applications (SPA)**: Bir sahifali ilovalar, masalan, Facebook, Instagram, Twitter kabi ilovalar.
- **Mobile ilovalar**: **React Native** yordamida React yordamida mobil ilovalar yaratish mumkin.
- **Interaktiv veb-ilovalar**: Reaktsiya bilan interaktiv interfeyslar yaratish uchun juda yaxshi.

Bu `Salom` komponenti ekranda "Salom, dunyo!" matnini ko'rsatadi. Siz uni boshqa komponentlarda ishlatishingiz mumkin.

React — bu foydalanuvchi interfeyslarini yaratishda juda qulay va samarali kutubxona. U yuqori darajadagi ishlash tezligi, qayta ishlatiladigan komponentlar va kuchli jamoa tomonidan qo'llab-quvvatlanadigan texnologiya bo'lib, zamonaviy veb-ilovalarni yaratishda juda keng qo'llaniladi.