<div align="center">

# Arabic Dialects + Arabizi Dictionary<br>قاموس العامية والعربيزي

**Gulf (incl. Saudi) · Levantine · Egyptian · Arabizi / Franco**<br>
**خليجي (ومنه السعودي) · شامي · مصري · عربيزي / فرانكو**

Make your Android keyboard understand how people really type in chats.<br>
خلّي كيبورد جوالك يفهم الكلام اللي نكتبه فعلاً في الشات.

**[English](#english) · [العربية](#arabic)**

</div>

---

<a name="english"></a>

# English

## What is this?

Your keyboard knows standard Arabic (فصحى). It doesn't know the words people actually type in chats, such as **عشان، هيك، شلونك، ازيك، لسه، دحين، تاني**, or Arabizi like **3shan, ya3ni, kifak, wesh**. So it underlines them in red, suggests the wrong word, or "fixes" them.

This repo gives your keyboard:

- about **50,000 everyday dialect words** in Arabic letters,
- about **22,000 Arabizi words** (Arabic written with English letters and numbers),
- **iPhone-style Arabic and English key layouts** (optional).

It is made for **[WM Keyboard](https://github.com/wasi-master/wmkeyboard)**, a free keyboard app for Android.

## What's inside

| File | What it is | Where it goes in WM Keyboard |
|---|---|---|
| [`arabic_dialects.txt`](arabic_dialects.txt) | 49,953 dialect words in Arabic letters | Arabic |
| [`arabizi_dialects.txt`](arabizi_dialects.txt) | 21,950 Arabizi words (3shan, ya3ni, kifak…) | Arabizi |
| [`arabic_ios.wmlayout.json`](arabic_ios.wmlayout.json) | Arabic keyboard layout like the iPhone's | Key layouts |
| [`english_ios.wmlayout.json`](english_ios.wmlayout.json) | English keyboard layout like the iPhone's | Key layouts |

You don't need all of them. **Most people only need `arabic_dialects.txt`.**

## Does it have swear words?

**No real swear words.** There are no sexual swear words and no cursing of religion or parents. Both lists were checked against five public bad-word lists, plus a hand search for about 90 swear-word roots in Arabic and Arabizi spellings. Everything found was removed.

**It does keep mild everyday insults** that friends use jokingly, like **حمار، غبي، كلب، زفت، تبن، طز** and **zeft, klb**. That's about 190 words in the Arabic list and 36 in the Arabizi list, under half a percent of each. They are ranked low, so they rarely come up as suggestions.

Don't want one of them? In WM Keyboard go to **Typing → Suggestions → Suggestion blacklist** and add the word. Found a real swear word that slipped through? [Open an issue](../../issues) and it will be removed.

## Before you start

You need:

1. An Android phone.
2. **WM Keyboard** installed and turned on. Get it from [Google Play](https://play.google.com/store/apps/details?id=com.wasimaster.wmkeyboard), [F-Droid](https://f-droid.org/packages/com.wasimaster.wmkeyboard/) or [GitHub](https://github.com/wasi-master/wmkeyboard/releases/latest).
3. Internet for one minute.

> **Tip:** if you can't find a setting, open WM Keyboard and tap the **search 🔍** at the top, then type the setting's name.

## Step 1: Add the Arabic dialect words (everyone should do this)

**Way A: paste a link (easiest, nothing to download)**

1. **Long-press** this link and tap **Copy link address** (or **Copy link**):<br>
   👉 [**arabic_dialects.txt**](arabic_dialects.txt?raw=true)
2. Open the **WM Keyboard** app.
3. Tap **Typing → Suggestions → Custom dictionaries**.
4. Look for the **Arabic** box.<br>
   No Arabic box? Tap **Add a word list for another language** and choose **Arabic**.
5. In the Arabic box, tap **From URL**.
6. Paste the link and tap **Download**.
7. Done ✅. You should see **arabic_dialects** with about **49,953 words**.

**Way B: download the file first**

1. Long-press 👉 [**arabic_dialects.txt**](arabic_dialects.txt?raw=true) and tap **Download link**.
2. Open **WM Keyboard → Typing → Suggestions → Custom dictionaries**.
3. In the **Arabic** box, tap **Import word list** and pick `arabic_dialects.txt` from your **Downloads**.

**Check it works:** open any chat, switch to WM Keyboard's **Arabic** layout and type **شلون** or **ازي**. You should see **شلونك** / **ازيك** in the suggestions.

## Step 2: Add the Arabizi words (only if you type Arabic in English letters)

**First, add the Arabizi language** (one time only):

1. Open **WM Keyboard → Languages & layouts**.
2. Search for **Arabizi** and tap **Arabizi · Arabic (Romanized)** to add it.

**Then add the word list:**

1. Long-press 👉 [**arabizi_dialects.txt**](arabizi_dialects.txt?raw=true) and tap **Copy link address**.
2. Open **WM Keyboard → Typing → Suggestions → Custom dictionaries**.
3. Tap **Add a word list for another language** and choose **Arabizi**. (If you already see an Arabizi box, skip this.)
4. In the Arabizi box, tap **From URL**, paste the link and tap **Download**.

**You type Arabizi on the English keyboard and don't want to switch?**

Go to **WM Keyboard → Languages & layouts → English → Also suggest from**, and turn on **Arabizi**. Now the English keyboard also suggests Arabizi words.

> ⚠️ **Don't import the Arabizi list under English.** Some Arabizi words are one letter away from English words (*ana* / and, *bas* / bad, *leh* / let), so English autocorrect may turn your English typos into Arabizi. Use **Also suggest from** instead, as shown above.

## Step 3 (optional): iPhone-style layouts

### Arabic

The iPhone puts the Arabic letters in a slightly different place than Android keyboards: **ة** is at the end of the middle row, and **ط ظ ذ** have their own keys on the bottom row. There's no Shift key.

```
‎ض‎ ص‎ ث‎ ق‎ ف‎ غ‎ ع‎ ه‎ خ‎ ح‎ ج‎
‎ ش‎ س‎ ي‎ ب‎ ل‎ ا‎ ت‎ ن‎ م‎ ك‎ ة‎
‎   ء‎ ظ‎ ط‎ ذ‎ د‎ ز‎ ر‎ و‎ ى‎ ⌫‎
```

Long-press a key for more letters:

| Key | Long-press gives |
|:-:|:-:|
| ء | أ إ ؤ ئ |
| ا | آ أ إ |
| ة | ه |
| ى | ئ ي |
| و | ؤ |
| ل | لا لأ لإ لآ |
| top row | vowel marks (harakat) |

**To install it:**

1. Long-press 👉 [**arabic_ios.wmlayout.json**](arabic_ios.wmlayout.json?raw=true) and tap **Download link**.
2. Open **WM Keyboard → Layout & size → Key layouts**.
3. Tap **Import a layout** and pick `arabic_ios.wmlayout.json` from **Downloads**.
4. Tap **Import and turn on**.
5. To switch to it: **swipe the space bar** or **hold the 🌐 key**.

(Another way: open the file from your **Files** app and choose **Import into WM Keyboard**.)

### English

Normal QWERTY, but built like the iPhone's:

- **No comma or period keys** on the letters page, just **123 · 🌐 · space · return**. Type a period by tapping space twice: turn it on in **WM Keyboard → Typing → Capitals, punctuation and spacing → Double space → Full stop**.
- The **123** page and the **#+=** page have the same keys in the same places as the iPhone.
- **Long-press a vowel for accents** (é, ü, ñ, ç…), like on the iPhone.
- No small hint letters on the keys.

**To install it:** do the same 5 steps as above, with 👉 [**english_ios.wmlayout.json**](english_ios.wmlayout.json?raw=true).

> Both layouts follow the iPhone's key positions. Apple doesn't publish its layouts, so a few long-press extras may differ from a real iPhone.

## Red lines under words? Read this

The red underline doesn't come from the keyboard. It comes from **Android's spell checker**, which is a separate setting. On many phones, especially GrapheneOS, the default spell checker doesn't know dialect words.

1. Open your phone's **Settings** and search for **Spell checker**.
2. Tap **Default spell checker** and choose **WM Keyboard**. Or turn off **Use spell checker** to get no red lines at all.
3. **Force stop** the chat app (Settings → Apps → WhatsApp → Force stop), then open it again. Words that were underlined before stay underlined until you retype them.
4. Using **Private Space**, a work profile or another user? Each one has **its own** spell checker setting. Change it there too.

## Something's wrong?

| Problem | Fix |
|---|---|
| "The app found no words in that file" | You copied the page link, not the file link. Use the 👉 links in this README, which end in `?raw=true`. |
| Dialect words don't show up | Make sure you're typing on WM Keyboard's **Arabic** layout and the list's switch is **on** in **Custom dictionaries**. |
| I can't find **Arabizi** under **Add a word list for another language** | Add the Arabizi language first (Step 2). |
| I want to remove it | **Custom dictionaries** → tap the 🗑️ next to the list, or turn its switch off. |

## Questions

**Is it safe? Does it collect anything?**<br>
No. These are plain text files with words and numbers. There's no app and no code, and nothing is sent anywhere.

**Will it replace normal Arabic?**<br>
No. It only *adds* dialect words. WM Keyboard's own Arabic word list keeps working.

**Will it slow down my keyboard?**<br>
No. The Arabic file is under 1 MB.

**What are the numbers next to each word?**<br>
How common the word is. Bigger numbers are suggested first.

**Does it work with other keyboards (Gboard, HeliBoard, FUTO…)?**<br>
It's made and tested for WM Keyboard. Other keyboards use different file formats.

**A word is missing or wrong.**<br>
[Open an issue](../../issues) with the word and the dialect.

## How the lists were made (short version)

1. Words were counted in hundreds of millions of words of real dialect writing: tweets, forums, chat, song lyrics, subtitles.
2. Each word's use in dialect text was compared with its use in standard Arabic. Words used much more in dialect were kept. Standard Arabic words were left out, because the keyboard already has them.
3. Junk was removed: names, spam, stretched words (حلوووو), laughing (هههه), Moroccan/Algerian-only words, and swear words.
4. Common words were added by hand, with their usual spellings (ة/ه, ى/ي, أ/ا) and attached forms (وعشان، بس، عشانك).
5. Each word got a number showing how common it is.

## Credits and licence

The word lists are shared under **[CC BY-SA 4.0](LICENSE)**: you can use, share and change them, as long as you credit this project and share changes under the same licence. The files contain only single words and numbers, no sentences, posts or lyrics from the sources.

They were built with the help of:

| Source | Licence |
|---|---|
| [CAMeL Lab Arabic Frequency Lists](https://github.com/CAMeL-Lab/Camel_Arabic_Frequency_Lists) | CC BY-SA 4.0 |
| [Gumar Corpus n-grams](https://github.com/CAMeL-Lab/Gumar-Ngrams) (NYU Abu Dhabi) | CC BY 3.0 |
| [Shami Corpus](https://github.com/GU-CLASP/shami-corpus) | Apache 2.0 |
| [Habibi Arabic lyrics corpus](https://github.com/ArabicNLP-UK/Habibi) | free for research use |
| [IADD dialect dataset](https://github.com/JihadZa/IADD) | — |
| [SADSLyC](https://github.com/SalwaAlahmari/SADSLyC_Corpus) | MIT |
| [Arabizi-Arabic parallel corpus](https://github.com/bashartalafha/Arabizi-Transliteration) (Talafha et al.) | — |
| [egyptian-arabizi-franco](https://github.com/BackendNeuron/egyptian-arabizi-franco) | MIT |
| [WM Keyboard data](https://github.com/wasi-master/wmkeyboard) (OpenSubtitles counts via [FrequencyWords](https://github.com/hermitdave/FrequencyWords), Arabizi counts via [ELNER-DZ](https://huggingface.co/datasets/HadjerHaninebgt7878/ELNER-DZ)) | MIT / CC BY-SA 4.0 / CC BY 4.0 |
| [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) standard-Arabic analyzer (used only to filter) | MIT |

The keyboard layout files use WM Keyboard's layout format, and the Arabic one starts from its built-in Arabic layout. MIT License, © 2026 Wasi Master; see [`LICENSE-layout-MIT.txt`](LICENSE-layout-MIT.txt).

<br>

---

<a name="arabic"></a>

<div dir="rtl">

# العربية

## وش هذا؟

الكيبورد يعرف الفصحى، بس ما يعرف الكلمات اللي نكتبها فعلاً في الشات، مثل **عشان، هيك، شلونك، ازيك، لسه، دحين، تاني**، ولا العربيزي مثل **3shan, ya3ni, kifak, wesh**. عشان كذا يحط تحتها خط أحمر، أو يقترح كلمة غلط، أو "يصححها".

هذا المشروع يعطي الكيبورد:

- تقريباً **50,000 كلمة عامية** بالحروف العربية،
- تقريباً **22,000 كلمة عربيزي** (عربي مكتوب بحروف إنجليزية وأرقام)،
- **ترتيب حروف عربي وإنجليزي مثل الآيفون** (اختياري).

المشروع مصمّم لتطبيق **[WM Keyboard](https://github.com/wasi-master/wmkeyboard)**، وهو كيبورد مجاني للأندرويد.

## وش فيه؟

| الملف | وش هو | وين يروح في WM Keyboard |
|---|---|---|
| [`arabic_dialects.txt`](arabic_dialects.txt) | 49,953 كلمة عامية بالحروف العربية | العربية |
| [`arabizi_dialects.txt`](arabizi_dialects.txt) | 21,950 كلمة عربيزي (3shan, ya3ni, kifak…) | Arabizi |
| [`arabic_ios.wmlayout.json`](arabic_ios.wmlayout.json) | ترتيب حروف عربي مثل الآيفون | تخطيطات المفاتيح |
| [`english_ios.wmlayout.json`](english_ios.wmlayout.json) | ترتيب حروف إنجليزي مثل الآيفون | تخطيطات المفاتيح |

ما تحتاجها كلها. **أغلب الناس يكفيهم `arabic_dialects.txt` بس.**

## فيه كلام وصخ أو شتايم؟

**لا، ما فيه شتايم حقيقية.** ما فيه ألفاظ جنسية، ولا سبّ للدين أو الأهل. تم فحص القائمتين بخمس قوائم عامة للكلمات البذيئة، وبعدها بحث يدوي عن حوالي 90 جذر من جذور الشتايم بالعربي والعربيزي. وأي شي انلقى انحذف.

**بس فيه كلمات زعل خفيفة** يقولها الأصحاب لبعض مزح، مثل **حمار، غبي، كلب، زفت، تبن، طز** و **zeft, klb**. عددها تقريباً 190 كلمة في القائمة العربية و36 في العربيزي، يعني أقل من نص بالمية من كل قائمة. وترتيبها منخفض، فنادراً تطلع في الاقتراحات.

ما تبي وحدة منها؟ في WM Keyboard روح إلى **الكتابة ← الاقتراحات ← القائمة السوداء للاقتراحات** وأضف الكلمة. لقيت شتيمة حقيقية فاتتنا؟ [افتح Issue](../../issues) وبتنحذف.

## قبل ما تبدأ

تحتاج:

1. جوال أندرويد.
2. تطبيق **WM Keyboard** مثبّت ومفعّل. حمّله من [Google Play](https://play.google.com/store/apps/details?id=com.wasimaster.wmkeyboard) أو [F-Droid](https://f-droid.org/packages/com.wasimaster.wmkeyboard/) أو [GitHub](https://github.com/wasi-master/wmkeyboard/releases/latest).
3. إنترنت لمدة دقيقة.

> **نصيحة:** إذا ما لقيت إعداد، افتح WM Keyboard واضغط **البحث 🔍** فوق، واكتب اسم الإعداد.
>
> الأسماء بين القوسين (مثل *Typing*) هي اسم الإعداد إذا كان جوالك بالإنجليزي.

## الخطوة 1: إضافة الكلمات العامية (للكل)

**الطريقة الأولى: الصق رابط (الأسهل، ما تحتاج تنزّل شي)**

1. **اضغط مطوّلاً** على هذا الرابط واختر **نسخ عنوان الرابط** (Copy link address):<br>
   👈 [**arabic_dialects.txt**](arabic_dialects.txt?raw=true)
2. افتح تطبيق **WM Keyboard**.
3. اضغط **الكتابة** (Typing) ← **الاقتراحات** (Suggestions) ← **القواميس المخصصة** (Custom dictionaries).
4. دوّر على مربع **العربية**.<br>
   ما فيه مربع للعربية؟ اضغط **إضافة قائمة كلمات للغة أخرى** واختر **العربية**.
5. في مربع العربية اضغط **من رابط** (From URL).
6. الصق الرابط واضغط **تنزيل** (Download).
7. خلاص ✅. بيطلع لك **arabic_dialects** وتحته تقريباً **49,953 كلمة**.

**الطريقة الثانية: نزّل الملف أول**

1. اضغط مطوّلاً على 👈 [**arabic_dialects.txt**](arabic_dialects.txt?raw=true) واختر **تنزيل الرابط** (Download link).
2. افتح **WM Keyboard ← الكتابة ← الاقتراحات ← القواميس المخصصة**.
3. في مربع **العربية** اضغط **استيراد قائمة الكلمات** واختر الملف `arabic_dialects.txt` من **التنزيلات**.

**تأكد إنه اشتغل:** افتح أي محادثة، وحوّل لكيبورد WM **العربي**، واكتب **شلون** أو **ازي**. المفروض تطلع لك **شلونك** أو **ازيك** في الاقتراحات.

## الخطوة 2: إضافة كلمات العربيزي (بس إذا تكتب عربي بحروف إنجليزية)

**أول شي أضف لغة Arabizi** (مرة وحدة بس):

1. افتح **WM Keyboard ← اللغات** (Languages & layouts).
2. ابحث عن **Arabizi** واضغط على **Arabizi · Arabic (Romanized)** عشان تضيفها.

**بعدين أضف قائمة الكلمات:**

1. اضغط مطوّلاً على 👈 [**arabizi_dialects.txt**](arabizi_dialects.txt?raw=true) واختر **نسخ عنوان الرابط**.
2. افتح **WM Keyboard ← الكتابة ← الاقتراحات ← القواميس المخصصة**.
3. اضغط **إضافة قائمة كلمات للغة أخرى** واختر **Arabizi**. (إذا مربع Arabizi موجود من قبل، تجاوز هذي الخطوة.)
4. في مربع Arabizi اضغط **من رابط**، والصق الرابط، واضغط **تنزيل**.

**تكتب عربيزي على الكيبورد الإنجليزي وما تبي تبدّل؟**

روح إلى **WM Keyboard ← اللغات ← English ← اقتراح أيضاً من** (Also suggest from)، وفعّل **Arabizi**. كذا الكيبورد الإنجليزي بيقترح لك كلمات عربيزي بعد.

> ⚠️ **لا تستورد قائمة العربيزي تحت English.** بعض كلمات العربيزي تفرق حرف واحد بس عن كلمات إنجليزية (مثلاً **ana** قريبة من **and**)، فالتصحيح التلقائي الإنجليزي ممكن يحوّل أخطاءك الإنجليزية لعربيزي. استخدم **اقتراح أيضاً من** مثل ما فوق.

## الخطوة 3 (اختيارية): ترتيب الحروف مثل الآيفون

### العربي

الآيفون يحط بعض الحروف العربية في أماكن غير عن كيبوردات الأندرويد: **ة** في آخر الصف الأوسط، و **ط ظ ذ** لها أزرار في الصف التحتاني. وما فيه زر Shift.

<div dir="ltr">

```
‎ض‎ ص‎ ث‎ ق‎ ف‎ غ‎ ع‎ ه‎ خ‎ ح‎ ج‎
‎ ش‎ س‎ ي‎ ب‎ ل‎ ا‎ ت‎ ن‎ م‎ ك‎ ة‎
‎   ء‎ ظ‎ ط‎ ذ‎ د‎ ز‎ ر‎ و‎ ى‎ ⌫‎
```

</div>

اضغط مطوّلاً على الزر عشان تطلع حروف زيادة:

| الزر | الضغط المطوّل يعطيك |
|:-:|:-:|
| ء | أ إ ؤ ئ |
| ا | آ أ إ |
| ة | ه |
| ى | ئ ي |
| و | ؤ |
| ل | لا لأ لإ لآ |
| الصف الفوقاني | التشكيل (الحركات) |

**طريقة التركيب:**

1. اضغط مطوّلاً على 👈 [**arabic_ios.wmlayout.json**](arabic_ios.wmlayout.json?raw=true) واختر **تنزيل الرابط**.
2. افتح **WM Keyboard ← التخطيط والحجم** (Layout & size) **← تخطيطات المفاتيح** (Key layouts).
3. اضغط **استيراد تخطيط** (Import a layout) واختر `arabic_ios.wmlayout.json` من **التنزيلات**.
4. اضغط **استيراد وتفعيل** (Import and turn on).
5. عشان تبدّل له: **اسحب على زر المسافة** أو **اضغط مطوّلاً على زر 🌐**.

(طريقة ثانية: افتح الملف من تطبيق **الملفات** واختر **استيراد إلى لوحة مفاتيح WM**.)

### الإنجليزي

ترتيب QWERTY العادي، بس مسوّى مثل الآيفون:

- **ما فيه زر فاصلة ولا نقطة** في صفحة الحروف، بس **123 · 🌐 · مسافة · إدخال**. النقطة تطلع لما تضغط المسافة مرتين: فعّلها من **WM Keyboard ← الكتابة ← Capitals, punctuation and spacing ← مسافة مزدوجة** (Double space) واختر **نقطة** (Full stop).
- صفحة **123** وصفحة **#+=** فيها نفس الأزرار وبنفس الأماكن اللي في الآيفون.
- **اضغط مطوّلاً على الحروف** عشان تطلع الحروف اللي عليها علامات (é، ü، ñ، ç…)، مثل الآيفون.
- ما فيه حروف صغيرة مكتوبة على الأزرار.

**طريقة التركيب:** نفس الخطوات الخمس اللي فوق، بس مع 👈 [**english_ios.wmlayout.json**](english_ios.wmlayout.json?raw=true).

> الترتيبين يتبعون أماكن الأزرار في الآيفون. أبل ما تنشر ترتيباتها، فممكن بعض حروف الضغط المطوّل تختلف شوي عن الآيفون الحقيقي.

## يطلع خط أحمر تحت الكلمات؟ اقرأ هذا

الخط الأحمر مو من الكيبورد. هو من **المدقق الإملائي حق الأندرويد**، وهذا إعداد منفصل. في جوالات كثيرة، وخصوصاً GrapheneOS، المدقق الإملائي الافتراضي ما يعرف الكلمات العامية.

1. افتح **الإعدادات** في جوالك وابحث عن **إملائي** (أو Spell checker).
2. اضغط **المدقق الإملائي الافتراضي** واختر **WM Keyboard**. أو طفّي **استخدام المدقق الإملائي** إذا ما تبي أي خط أحمر أبداً.
3. سوّ **فرض الإيقاف** (Force stop) لتطبيق الشات (الإعدادات ← التطبيقات ← واتساب ← فرض الإيقاف)، وافتحه من جديد. الكلمات اللي كان تحتها خط من قبل بيظل تحتها خط لين تكتبها من جديد.
4. تستخدم **المساحة الخاصة** (Private Space) أو ملف العمل أو مستخدم ثاني؟ كل واحد منها له إعداد مدقق إملائي **خاص فيه**. غيّره هناك بعد.

## فيه مشكلة؟

| المشكلة | الحل |
|---|---|
| يقول "لم يعثر التطبيق على أي كلمات في ذلك الملف" | نسخت رابط الصفحة مو رابط الملف. استخدم روابط 👈 اللي في هذي الصفحة، اللي آخرها `?raw=true`. |
| الكلمات العامية ما تطلع | تأكد إنك تكتب على كيبورد WM **العربي**، وإن مفتاح القائمة **شغّال** في **القواميس المخصصة**. |
| ما لقيت **Arabizi** في **إضافة قائمة كلمات للغة أخرى** | أضف لغة Arabizi أول (الخطوة 2). |
| أبي أشيلها | **القواميس المخصصة** ← اضغط 🗑️ جنب القائمة، أو طفّ المفتاح حقها. |

## أسئلة

**هل هو آمن؟ يجمع معلومات؟**<br>
لا. هذي ملفات نص عادية فيها كلمات وأرقام بس. ما فيها تطبيق ولا كود، وما ترسل أي شي لأي مكان.

**بيلغي الفصحى؟**<br>
لا. هو *يضيف* كلمات عامية بس، وقائمة WM Keyboard العربية الأصلية تظل شغّالة.

**بيبطّئ الكيبورد؟**<br>
لا. الملف العربي أقل من 1 ميجا.

**وش الأرقام اللي جنب كل كلمة؟**<br>
كم الكلمة منتشرة. الرقم الأكبر يطلع أول في الاقتراحات.

**يشتغل مع كيبوردات ثانية (Gboard، HeliBoard، FUTO…)؟**<br>
هو مسوّى ومجرّب على WM Keyboard. الكيبوردات الثانية تستخدم صيغ ملفات مختلفة.

**فيه كلمة ناقصة أو غلط.**<br>
[افتح Issue](../../issues) واكتب الكلمة واللهجة.

## كيف انسوّت القوائم (باختصار)

1. انحسبت الكلمات في مئات الملايين من الكلمات المكتوبة باللهجات: تغريدات، منتديات، شات، أغاني، ترجمات أفلام.
2. انقارن استخدام كل كلمة في اللهجات باستخدامها في الفصحى. الكلمات اللي تنستخدم في اللهجات أكثر بكثير هي اللي انحفظت. وكلمات الفصحى انشالت، لأن الكيبورد عنده إياها أصلاً.
3. انشالت الزوائد: الأسماء، والسبام، والكلمات الممطوطة (حلوووو)، والضحك (هههه)، وكلمات المغرب العربي بس، والشتايم.
4. انضافت كلمات منتشرة باليد مع طرق كتابتها المعروفة (ة/ه، ى/ي، أ/ا) والأشكال المتصلة (وعشان، بس، عشانك).
5. كل كلمة أخذت رقم يبيّن كم هي منتشرة.

## الشكر والرخصة

قوائم الكلمات منشورة برخصة **[CC BY-SA 4.0](LICENSE)**: تقدر تستخدمها وتنشرها وتعدّل عليها، بشرط تذكر هذا المشروع وتنشر تعديلاتك بنفس الرخصة. الملفات فيها كلمات مفردة وأرقام بس، وما فيها أي جمل أو منشورات أو كلمات أغاني من المصادر.

المصادر المستخدمة مذكورة في جدول **Credits and licence** في القسم الإنجليزي فوق.

ملفات ترتيب الحروف مسوّاة بصيغة WM Keyboard، والعربي منها مبني على الترتيب العربي الموجود فيه، برخصة MIT، © 2026 Wasi Master. شوف [`LICENSE-layout-MIT.txt`](LICENSE-layout-MIT.txt).

</div>
