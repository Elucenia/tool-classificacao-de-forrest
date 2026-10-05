<!-- ELUCENIA technical documentation · classificacao-de-forrest · ar · no clinical/professional/rights approval -->

# تصنيف Forrest

[الشروط والمصادر والأذونات](https://elucenia.org/ar/tools/classificacao-de-forrest)

## كيفية الاستخدام

استخدم الأداة في البوابة أو افتح index.html عبر خادم HTTP محلي. اختر اللغة، وأكمل الحقول، ثم أجرِ الحساب.

## المدخلات والوحدات

### مظهر القرحة في التنظير

`classe`

- `Ia` — Ia – نزف نشط نافوري
- `Ib` — Ib – نزف نشط نازّ
- `IIa` — IIa – وعاء ظاهر غير نازف
- `IIb` — IIb – خثرة ملتصقة
- `IIc` — IIc – بقعة مصطبغة مسطحة (هيماتين)
- `III` — III – قاعدة نظيفة (فيبرين)

## إصدار الطريقة

فورست 1974: Ia/Ib/IIa/IIb/IIc/III؛ سياق ESGE 2021

## المعادلة الموثقة

Forrest I (نزف نشط): Ia نافوري، Ib نازّ. Forrest II (علامات نزف حديث): IIa وعاء ظاهر، IIb خثرة ملتصقة، IIc هيماتين مسطّح. Forrest III: قاعدة نظيفة.

## الحدود والفئة السكانية

يصنّف Forrest المظهر التنظيري للقرحة الهضمية النازفة، وليس جميع حالات النزف الهضمي. اختر الفئة بناءً على الفحص؛ لا تحلّل الأداة الصور ولا تحدّد سبب النزف. تقرّ إرشادات ESGE لعام 2021 بوجود قيود على الاتفاق بين الفاحصين. لا توفّر الفئة أو النسب التاريخية المحتملة، بمفردها، توقعًا فرديًا لإعادة النزف ولا تحدّد الخروج من المستشفى أو العلاج.

## المراجع

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

## إعادة إجراء الاختبارات التقنية

شغّل node test.cjs في المجلد الجذري لهذا المستودع لتكرار الحالات الاصطناعية المسجلة. تُحفظ المدخلات والنتائج المتوقعة وحدود التفاوت الأصلية. لا تُعدّ الاختبارات التقنية تحققًا سريريًا.

```sh
node test.cjs
```

يحتوي tool.json على المصادر والإصدار ونطاق المراجعة. يحتفظ examples.json بالمدخلات والنتائج المتوقعة للحالات الاصطناعية؛ ويسجل results.json النتائج التي تم الحصول عليها.

[السجل والمراجع](../tool.json) · [شيفرة JavaScript](../calculator.js) · [حالات مرجعية](../examples.json) · [results.json](../results.json)

## المراجعة وشروط الاستخدام

لم تُجرَ مراجعة سريرية مستقلة.

هذه الواجهة ترجمة أعدّها مؤلفوها، وليست إصدارًا رسميًا أو معتمدًا. لم تُجرَ مراجعة سريرية مستقلة أو مراجعة لغوية مهنية، ولم تُستكمل الموافقة على حقوق استخدام الأدوات.

نتيجة المعادلة أو التصنيف. يعتمد التفسير والتصرف ومدى الانطباق على التقييم المهني والمصدر المحدد.

## الترخيص ونسبة العمل إلى أصحابه

ينطبق Apache-2.0 على كود ELUCENIA فقط. تبقى حقوق الأدوات والمنشورات والترجمات والبيانات لأصحابها المعنيين. احتفظ بملفّي LICENSE وNOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
