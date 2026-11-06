---
name: uzlang
description: >-
  Oʻzbek tilida (lotin yozuvida) toʻgʻri imlo, tinish belgilari va uslub bilan
  yozish, tahrirlash va matnni tekshirish. Oʻzbekcha matn yozilganda, tarjima
  qilinganda, korrektura yoki tahrir soʻralganda ishlating: maqola, ilmiy ish,
  ariza, xat, post, hujjat, interfeys matni. 1995-yil alifbosi (oʻ, gʻ, sh,
  ch) va 2026-yil yangi alifbosi (ö, ğ, ş, ç), ular orasida oʻgirish. Write,
  edit, proofread or check Uzbek (Latin script) text with correct orthography,
  punctuation and style, in the 1995 or the new 2026 alphabet, and convert
  between them — use whenever output is in Uzbek, including translation.
---

# Oʻzbek tili (uzlang)

Bu skill oʻzbekcha matnni lotin alifbosi va imlo qoidalariga mos yozish
uchun. U ikki alifboni qoʻllab-quvvatlaydi: 1995-yil alifbosi va 2026-yilda
qabul qilingan yangi alifbo (2-boʻlim). U dasturchilar, muharrirlar, talabalar, tarjimonlar va matn bilan
ishlaydigan har bir kishi uchun moʻljallangan.

## 1. Eng muhim qoida: ikki belgi

1995-yil alifbosida apostrofga oʻxshash **ikki xil** belgi bor. Ularni har
doim shu Unicode belgilari bilan yozing. Yangi alifboda `ʻ` ishlatilmaydi
(`oʻ` → `ö`, `gʻ` → `ğ`), tutuq belgisi `ʼ` esa xuddi shunday qoladi.

| Vazifasi | Belgi | Unicode | Misollar |
|---|---|---|---|
| `oʻ`, `gʻ` harflari | `ʻ` | U+02BB MODIFIER LETTER TURNED COMMA | oʻqituvchi, togʻ, Oʻzbekiston, Gʻafur |
| Tutuq belgisi | `ʼ` | U+02BC MODIFIER LETTER APOSTROPHE | maʼno, taʼlim, sanʼat, eʼlon, Qurʼon |

**`ʻ` va `ʼ` oʻrnida hech qachon ishlatmang:** `'` (U+0027), `` ` `` (U+0060),
`‘` (U+2018), `’` (U+2019), `´` (U+00B4), `ʹ` (U+02B9). Ular koʻrinishidan
oʻxshash, lekin notoʻgʻri: qidiruv, saralash va imlo tekshiruvini buzadi.

`‘` (U+2018) va `’` (U+2019) faqat **ichma-ich qoʻshtirnoq** sifatida
ishlatiladi (5-boʻlim). Ichki qoʻshtirnoqni yopishda tutuq belgisi `ʼ` emas,
`’` (U+2019) yoziladi.

### Qaysi birini tanlash

1. `o` yoki `g` (katta-kichik farqsiz) dan keyin → `ʻ`: `oʻ`, `gʻ`, `Oʻ`, `Gʻ`.
2. Boshqa har qanday harfdan keyin → `ʼ` (tutuq): `maʼno`, `qatʼiy`, `Isʼhoq`.
3. `oʻ` dan keyin alohida tutuq yozilmaydi: `moʻjiza`, `moʻtabar`, `moʻmin`.
4. Bosh harflarda ham belgi oʻzgarmaydi: `OʻZBEKISTON`, `GʻALABA`.

### Tegmaslik kerak boʻlgan joylar

Quyidagilarda apostrofni **almashtirmang**:

- dastur kodi, kod bloklari, buyruqlar, JSON/YAML kalitlari, formulalar;
- URL, e-pochta, fayl nomlari, identifikatorlar, hashtaglar;
- boshqa tildagi matn (`don't`, `l'homme`) va tilshunoslikka oid misollar;
- foydalanuvchi aynan saqlashni soʻragan iqtibos yoki hujjat.

Slug, fayl nomi yoki domen kabi ASCII kerak boʻlgan joyda belgini tushirib
qoldiring: `oʻzbekiston` → `ozbekiston`, `maʼruza` → `maruza`.

## 2. Alifbo

Ikki alifbo bor:

| | 1995-yil alifbosi | Yangi alifbo (2026) |
|---|---|---|
| Harflar | A B D E F G H I J K L M N O P Q R S T U V X Y Z Oʻ Gʻ Sh Ch | A B D E F G Ğ H I J K L M N O Ö P Q R S Ş Ç T U V X Y Z |
| Tutuq | `ʼ` (U+02BC) | `ʼ` (U+02BC) |
| Farqi | `oʻ`, `gʻ`, `sh`, `ch` | `ö`, `ğ`, `ş`, `ç` |
| Misol | `Oʻzbekiston, togʻ, shahar, choy` | `Özbekiston, toğ, şahar, çoy` |
| Holati | amalda | qonun 2026-yil 21-oktyabrda qabul qilingan, 2027-yil 22-apreldan kuchga kiradi, bosqichma-bosqich joriy etiladi |

### Qaysi alifboni tanlash

1. Foydalanuvchi aniq aytgan boʻlsa — oʻsha alifbo.
2. Foydalanuvchining matni, hujjati yoki loyihasi qaysi alifboda boʻlsa —
   oʻsha alifbo. Tahrir va korrekturada matnning alifbosi **oʻzgartirilmaydi**,
   agar buni soʻramasa.
3. Boshqa hollarda — **1995-yil alifbosi**, chunki u hali amalda va yangi
   alifbo uchun imlo qoidalari eʼlon qilinmagan.
4. Bitta matnda ikki alifboni **aralashtirmang**.

Yangi alifbo, harflarning Unicode kodlari, oʻgirish qoidalari va hali aniq
boʻlmagan holatlar: [references/yangi-alifbo.md](references/yangi-alifbo.md).
Yangi alifboda yozish yoki oʻgirishdan oldin shu faylni oʻqing.

### Begona harflar

- `ı`, `ü`, `ä`, `ñ`, `ș`, `ǧ` ikkala alifboda ham **yoʻq**.
- `ö`, `ğ`, `ş`, `ç` faqat yangi alifboda bor. 1995-yil alifbosidagi matnda
  ular xato: `Oʻzbek` — toʻgʻri, `Özbek` — xato (va aksincha).
- Turkcha, qozoqcha yoki qirgʻizcha soʻzlarni oʻzbekcha oʻrniga ishlatmang
  (`bilgisayar` emas, `kompyuter`; `teşekkür` emas, `rahmat`).
- Foydalanuvchi kirill yozuvida yozsa yoki kirillcha matn soʻrasa, kirillda
  javob bering. Aks holda standart — lotin yozuvi.

## 3. Ish rejimlari

Soʻrovdan rejimni aniqlang. Aniq boʻlmasa, matn yozish soʻralgan boʻlsa
**Yozish**, tayyor matn berilgan boʻlsa **Korrektura** deb hisoblang.

### Yozish
Yangi matnni shu skill qoidalariga toʻliq mos yozing. Uslubni matn turiga
qarab tanlang (4-boʻlim).

### Korrektura
Faqat imlo, tinish belgilari, harf va belgilar xatolarini tuzating. Soʻz
tanlash, gap tuzilishi, uslub va mazmunga **tegmang**. Muallifning ovozi
saqlanishi shart.

Natija: avval tuzatilgan matn, keyin oʻzgarishlar roʻyxati:

| Edi | Boʻldi | Sabab |
|---|---|---|
| `o'quvchi` | `oʻquvchi` | `oʻ` harfi U+02BB bilan yoziladi |

Belgi almashtirishlari koʻp boʻlsa, ularni bitta qatorda umumlashtiring
(“`'` → `ʻ`/`ʼ`: 37 ta joyda”).

### Tahrir
Korrekturadan tashqari uslubni ham yaxshilang: kalkalar, takrorlar, ortiqcha
uzun gaplar, notoʻgʻri atamalar. Mazmunni oʻzgartirmang. Katta oʻzgarishlarni
roʻyxatda sababi bilan koʻrsating.

### Tekshirish
Matnni **oʻzgartirmang**. Faqat xatolar roʻyxatini bering: qayerda, nima xato,
qanday boʻlishi kerak va qaysi qoidaga koʻra. Oxirida qisqa umumiy baho.

### Alifboga oʻgirish
Matnni bir alifbodan ikkinchisiga (1995 ↔ yangi) yoki kirilldan lotinga
oʻgiring. Faqat harflar oʻzgaradi: soʻz, tinish belgilari va uslubga tegilmaydi.
Kod, URL, xorijiy soʻzlar va rasmiy roʻyxatdan oʻtgan nomlar oʻgirilmaydi.
Qoidasi hali aniq boʻlmagan joylarni (masalan, `Isʼhoq`, `AQSh`) oʻzgartirmay
qoldiring va oxirida roʻyxat qilib koʻrsating.

## 4. Uslublar

- **Rasmiy-idoraviy** (ariza, xat, buyruq, bayonnoma): “Siz” bosh harf bilan,
  aniq va qisqa gaplar, hissiy soʻzlarsiz, belgilangan andozalarga rioya.
- **Ilmiy** (maqola, dissertatsiya, referat): shaxssiz yoki “biz” shaklidagi
  bayon, aniq atamalar, dalil va manbaga tayanish, baholovchi sifatlardan
  qochish.
- **Publitsistik** (maqola, yangilik, post): jonli, tushunarli, lekin adabiy
  meʼyorda.
- **Soʻzlashuv** (chat, ijtimoiy tarmoq): erkinroq, lekin imlo baribir toʻgʻri.

Murojaat shakli standart holatda — “siz”. “Sen” faqat foydalanuvchi shuni
xohlasa yoki matn turi talab qilsa.

### Tireni kam ishlating

Til modellari tireni (`—`) haddan tashqari koʻp ishlatadi va matn sunʼiy
koʻrinadi. Tireni faqat grammatik zarur oʻrinda qoʻying:

- ot bilan ifodalangan ega va kesim orasida: `Bilim — kuch.`;
- umumlashtiruvchi soʻz oldida: `Olma, nok, uzum — hammasi pishdi.`;
- koʻchirma gapda muallif gapi oldida: `“Kelaman”, — dedi u.`

Izoh, qoʻshimcha fikr, taʼkid yoki ikki gapni ulash uchun tire oʻrniga
vergul, ikki nuqta yoki qavs ishlating, yoki gapni ikkiga boʻling.

| Notoʻgʻri | Toʻgʻri |
|---|---|
| `Bu usul — eng tez va arzon — shuning uchun uni tanladik.` | `Bu usul eng tez va arzon. Shuning uchun uni tanladik.` |
| `Natija kutilganidan yaxshi — 95 foiz.` | `Natija kutilganidan yaxshi: 95 foiz.` |

Bitta xatboshida bittadan ortiq tire boʻlsa, matnni qayta koʻrib chiqing.
Bu qoida Yozish, Tahrir va tarjimaga taalluqli. Korrekturada muallifning
tirelariga tegmang (grammatik xato boʻlmasa).

### Tarjimada uzun gaplar

Inglizchada uzun gap tuzish oson: `which`, `that`, `while` bilan fikrlarni
ketma-ket ulash mumkin. Oʻzbek tilida kesim gap oxirida, aniqlovchilar esa
aniqlanmishdan oldin keladi. Shuning uchun inglizcha gap oʻzbekchaga aynan
koʻchirilsa, baʼzan ogʻir va tushunarsiz boʻlib qoladi.

Koʻp hollarda uzun gap oʻzbekchada ham yaxshi chiqadi. Gapni oʻzgartirishga
faqat u **haqiqatan ogʻir oʻqilsa** murojaat qiling. Masalan, kesimdan oldin
uzun aniqlovchi zanjiri yigʻilib qolsa yoki bitta gapga juda koʻp fikr
sigʻdirilgan boʻlsa.

Bunday holda bir nechta yoʻl bor. Matnga mosini tanlang:

- soʻz tartibini oʻzgartirish yoki aniqlovchini qisqartirish;
- uzun aniqlovchini alohida ergash gap yoki `-ib` bilan bogʻlangan qismga
  aylantirish;
- gapni ikkiga boʻlish.

Gapni boʻlish shulardan faqat biri, majburiy emas. Mazmun va fikrlar
orasidagi bogʻlanish har doim saqlanishi kerak.

| Inglizcha | Ogʻirroq tarjima | Yengilroq variant |
|---|---|---|
| The committee, which was set up in 2020 to oversee the reform that had been delayed several times, published its final report. | 2020-yilda bir necha marta kechiktirilgan islohotni nazorat qilish uchun tuzilgan qoʻmita yakuniy hisobotini eʼlon qildi. | Bir necha marta kechiktirilgan islohotni nazorat qilish uchun 2020-yilda qoʻmita tuzilgan edi. U yakuniy hisobotini eʼlon qildi. |

Huquqiy matn, rasmiy hujjat, iqtibos, badiiy asar va soʻzma-soʻz tarjimada
gap tuzilishini imkon qadar asliyatdagidek saqlang.

## 5. Tez-tez uchraydigan xatolar

- **Apostroflar** — eng koʻp xato. 1-boʻlimga qarang.
- **x / h**: `xabar`, `xalq`, `xursand` ↔ `hamma`, `hikoya`, `hayot`;
  maʼnosi farqlanadi: `xol` (dogʻ) ↔ `hol` (ahvol).
- **Kirill `е` soʻz boshida** → `ye`: `yer`, `yetti`, `Yevropa`. Kirill `э`
  → `e`: `eshik`, `ekin`.
- **`-ga`, `-gan` qoʻshimchalari**: faqat `k` dan keyin `-ka`/`-kan`, faqat
  `q` dan keyin `-qa`/`-qan` (`tilakka`, `qishloqqa`, `chiqqan`). Qolgan
  hollarda `g` yoziladi: `togʻga`, `bargga` (`toqqa`, `bargka` emas).
- **Tartib son raqamda**: `5-sinf`, `3-bob`, `2026-yil`; `5-chi sinf` emas.
- **Oy, kun, millat va til nomlari** kichik harf bilan: `6-noyabr`,
  `dushanba`, `oʻzbek tili`.
- **Qoʻshtirnoq**: `“...”` (U+201C, U+201D), ichma-ich — `‘...’` (U+2018,
  U+2019). Toʻgʻri `"..."` (U+0022), `«...»` yoki `„...“` emas.
- **Kalkalar**: ruscha va inglizcha iboralarni soʻzma-soʻz koʻchirmang;
  oʻzbekcha tabiiy muqobilini tanlang.

Batafsil qoidalar:

- Imlo (harflar, qoʻshimchalar, qoʻshib va ajratib yozish, bosh harf):
  [references/imlo.md](references/imlo.md)
- Tinish belgilari, raqamlar, sanalar, qisqartmalar:
  [references/punktuatsiya.md](references/punktuatsiya.md)
- Yangi alifbo va oʻgirish:
  [references/yangi-alifbo.md](references/yangi-alifbo.md)

`imlo.md` va `punktuatsiya.md` dagi misollar 1995-yil alifbosida. Yangi
alifboda ham shu qoidalar amal qiladi, faqat harflar oʻgiriladi.

Murakkab holatda tegishli faylni oʻqing.

## 6. Yakuniy tekshiruv

Javobni berishdan oldin oʻzbekcha matnni koʻzdan kechiring:

1. Soʻz ichida `'`, `` ` ``, `‘`, `’` qolmadimi? `o`/`g` dan keyin — `ʻ`,
   boshqa joyda — `ʼ`.
2. Butun matn bitta alifbodami? 1995-yil alifbosida `ö`, `ğ`, `ş`, `ç`
   yoʻqmi; yangi alifboda `oʻ`, `gʻ`, `sh`, `ch` qolmadimi? `ı`, `ü` kabi
   begona harflar yoʻqmi?
3. Qoʻshtirnoqlar `“...”`, ichma-ich `‘...’` shaklidami?
4. Kod, URL va boshqa tildagi parchalar oʻzgarmay qoldimi?
5. Tanlangan rejim talablari bajarildimi (korrekturada uslubga tegilmadimi)?
