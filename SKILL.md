---
name: uzlang
description: >-
  Oʻzbek tilida (lotin yozuvida) toʻgʻri imlo, tinish belgilari va uslub bilan
  yozish, tahrirlash va matnni tekshirish. Oʻzbekcha matn yozilganda, tarjima
  qilinganda, korrektura yoki tahrir soʻralganda ishlating: maqola, ilmiy ish,
  ariza, xat, post, hujjat, interfeys matni. Write, edit, proofread or check
  Uzbek (Latin script) text with correct orthography, punctuation and style —
  use whenever output is in Uzbek, including translation into Uzbek.
---

# Oʻzbek tili (uzlang)

Bu skill oʻzbekcha matnni amaldagi lotin alifbosi va imlo qoidalariga mos
yozish uchun. U dasturchilar, muharrirlar, talabalar, tarjimonlar va matn bilan
ishlaydigan har bir kishi uchun moʻljallangan.

## 1. Eng muhim qoida: ikki belgi

Oʻzbek lotin yozuvida apostrofga oʻxshash **ikki xil** belgi bor. Ularni har
doim shu Unicode belgilari bilan yozing:

| Vazifasi | Belgi | Unicode | Misollar |
|---|---|---|---|
| `oʻ`, `gʻ` harflari | `ʻ` | U+02BB MODIFIER LETTER TURNED COMMA | oʻqituvchi, togʻ, Oʻzbekiston, Gʻafur |
| Tutuq belgisi | `ʼ` | U+02BC MODIFIER LETTER APOSTROPHE | maʼno, taʼlim, sanʼat, eʼlon, Qurʼon |

**Hech qachon ishlatmang:** `'` (U+0027), `` ` `` (U+0060), `‘` (U+2018),
`’` (U+2019), `´` (U+00B4), `ʹ` (U+02B9). Ular koʻrinishidan oʻxshash, lekin
notoʻgʻri: qidiruv, saralash va imlo tekshiruvini buzadi.

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

Amaldagi alifbo (1995-yil): A B D E F G H I J K L M N O P Q R S T U V X Y Z
Oʻ Gʻ Sh Ch, tutuq belgisi `ʼ` va `ng` birikmasi.

- Boshqa tillarning harflarini aralashtirmang: `ş`, `ç`, `ğ`, `ı`, `ö`, `ü`,
  `ä`, `ñ` oʻzbek lotin yozuvida **yoʻq**. `Oʻzbek` — toʻgʻri, `Özbek` — xato.
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
(«`'` → `ʻ`/`ʼ`: 37 ta joyda»).

### Tahrir
Korrekturadan tashqari uslubni ham yaxshilang: kalkalar, takrorlar, ortiqcha
uzun gaplar, notoʻgʻri atamalar. Mazmunni oʻzgartirmang. Katta oʻzgarishlarni
roʻyxatda sababi bilan koʻrsating.

### Tekshirish
Matnni **oʻzgartirmang**. Faqat xatolar roʻyxatini bering: qayerda, nima xato,
qanday boʻlishi kerak va qaysi qoidaga koʻra. Oxirida qisqa umumiy baho.

## 4. Uslublar

- **Rasmiy-idoraviy** (ariza, xat, buyruq, bayonnoma): «Siz» bosh harf bilan,
  aniq va qisqa gaplar, hissiy soʻzlarsiz, belgilangan andozalarga rioya.
- **Ilmiy** (maqola, dissertatsiya, referat): shaxssiz yoki «biz» shaklidagi
  bayon, aniq atamalar, dalil va manbaga tayanish, baholovchi sifatlardan
  qochish.
- **Publitsistik** (maqola, yangilik, post): jonli, tushunarli, lekin adabiy
  meʼyorda.
- **Soʻzlashuv** (chat, ijtimoiy tarmoq): erkinroq, lekin imlo baribir toʻgʻri.

Murojaat shakli standart holatda — «siz». «Sen» faqat foydalanuvchi shuni
xohlasa yoki matn turi talab qilsa.

## 5. Tez-tez uchraydigan xatolar

- **Apostroflar** — eng koʻp xato. 1-boʻlimga qarang.
- **x / h**: `xabar`, `xalq`, `xursand` ↔ `hamma`, `hikoya`, `hayot`;
  maʼnosi farqlanadi: `xol` (dogʻ) ↔ `hol` (ahvol).
- **Kirill `е` soʻz boshida** → `ye`: `yer`, `yetti`, `Yevropa`. Kirill `э`
  → `e`: `eshik`, `ekin`.
- **`-ga`, `-gan` qoʻshimchalari**: `k`/`g` dan keyin `-ka`/`-kan`, `q`/`gʻ`
  dan keyin `-qa`/`-qan`: `tilakka`, `qishloqqa`, `chiqqan`.
- **Tartib son raqamda**: `5-sinf`, `3-bob`, `2026-yil`; `5-chi sinf` emas.
- **Oy, kun, millat va til nomlari** kichik harf bilan: `6-noyabr`,
  `dushanba`, `oʻzbek tili`.
- **Qoʻshtirnoq**: `«...»`, ichma-ich — `„...“`. Inglizcha `"..."` emas.
- **Kalkalar**: ruscha va inglizcha iboralarni soʻzma-soʻz koʻchirmang;
  oʻzbekcha tabiiy muqobilini tanlang.

Batafsil qoidalar:

- Imlo (harflar, qoʻshimchalar, qoʻshib va ajratib yozish, bosh harf):
  [references/imlo.md](references/imlo.md)
- Tinish belgilari, raqamlar, sanalar, qisqartmalar:
  [references/punktuatsiya.md](references/punktuatsiya.md)

Murakkab holatda tegishli faylni oʻqing.

## 6. Yakuniy tekshiruv

Javobni berishdan oldin oʻzbekcha matnni koʻzdan kechiring:

1. `'`, `` ` ``, `‘`, `’` qolmadimi? `o`/`g` dan keyin — `ʻ`, boshqa joyda — `ʼ`.
2. Begona harflar (`ş`, `ç`, `ğ`, `ı`, `ö`, `ü`) yoʻqmi?
3. Qoʻshtirnoqlar `«»` shaklidami?
4. Kod, URL va boshqa tildagi parchalar oʻzgarmay qoldimi?
5. Tanlangan rejim talablari bajarildimi (korrekturada uslubga tegilmadimi)?
