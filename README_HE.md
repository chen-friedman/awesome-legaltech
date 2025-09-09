# Awesome Legal AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub Stars](https://img.shields.io/github/stars/lawcal-ai/awesome-legal-ai?style=social)](https://github.com/lawcal-ai/awesome-legal-ai) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<div align="center">

### **האוסף המובחר של כלי Legal Tech ובינה מלאכותית לתחום המשפטי בקוד פתוח**

*אוצרים את הכלים הטובים ביותר שמוכנים לשימוש מסחרי, מאגרי נתונים וקהילות למקצוענים משפטיים ומפתחים*

[![Legal Tech](https://img.shields.io/badge/Legal%20Tech-Open%20Source-blue?style=for-the-badge&logo=scale&logoColor=white)](https://github.com/topics/legal-tech)
[![AI Powered](https://img.shields.io/badge/AI%20Powered-Legal%20Solutions-purple?style=for-the-badge&logo=brain&logoColor=white)](https://github.com/topics/legal-ai)
[![Global Scope](https://img.shields.io/badge/Global-Jurisdiction%20Tagged-green?style=for-the-badge&logo=world&logoColor=white)](https://github.com/topics/global)

**[🇬🇧 English](README.md) | [🇮🇱 עברית](README_HE.md)**

</div>

---

## מה הופך את הרשימה הזו למיוחדת?

**אוצרות איכותית בראש וראשונה** ← רק פרויקטים מתוחזקים באופן פעיל ומוכנים לשימוש מסחרי  
**כיסוי עולמי** ← היקף עולמי עם תיוג ספציפי למשפט השיפוט (🇺🇸 🇪🇺 🇬🇧 🇩🇪 🇮🇳)  
**התמקדות בפתרונות מסחריים** ← כלים מהעולם האמיתי שמקצוענים משפטיים משתמשים בהם בפועל  
**מאגרי נתונים עשירים** ← מדדי איכות גבוהה ונתוני אימון לפיתוח בינה מלאכותית  
**קהילות פעילות** ← מערכות אקולוגיות משגשגות ופרויקטים שיתופיים  

> **חדש לתחום Legal AI?** התחל עם [המדריך המהיר שלנו](#מדריך-מהיר) למטה!

---

## תוכן עניינים

| **ניווט מהיר** | **מספר** | **הטוב ביותר עבור** |
|-----------------|-----------|---------------------|
| [ספריות NLP ומודלי תחום](#ספריות-nlp-ומודלי-תחום) | 6 פרויקטים | עיבוד וניתוח טקסט |
| [ניתוח חוזים ומסמכים מבוסס בינה מלאכותית](#ניתוח-חוזים-ומסמכים-מבוסס-בינה-מלאכותית) | 5 פלטפורמות | אינטליגנציה חוזית |
| [מחקר משפטי ונתוני פסיקה/APIs](#מחקר-משפטי-ונתוני-פסיקהapis) | 6 משאבים | מחקר וציטוטים |
| [גילוי אלקטרוני ותביעות](#גילוי-אלקטרוני-ותביעות) | 3 כלים | גילוי משפטי |
| [ניהול מסמכים, OCR ו-PDF](#ניהול-מסמכים-ocr-ו-pdf) | 4 פתרונות | עיבוד מסמכים |
| [הרכבת מסמכים וכללים כקוד](#הרכבת-מסמכים-וכללים-כקוד) | 4 פלטפורמות | אוטומציה וזרימות עבודה |
| [מאגרי נתונים ומדדים](#מאגרי-נתונים-ומדדים) | 8 אוספים | אימון והערכה |
| [אינטליגנציה מסמכים כללית](#אינטליגנציה-מסמכים-כללית-שימושית-למשפטי) | 6 כלים | הבנת מסמכים |
| [למידה, קהילות ואוספים](#למידה-קהילות-ואוספים) | 2 קהילות | חינוך ורשתות |

**סה"כ: יותר מ-44 משאבי Legal Tech איכותיים בקוד פתוח**

---

## מדריך מהיר

### למקצוענים משפטיים
1. **התחל עם**: [ניתוח חוזים מבוסס בינה מלאכותית](#ניתוח-חוזים-ומסמכים-מבוסס-בינה-מלאכותית) לבדיקת מסמכים
2. **כלי מחקר**: [מחקר משפטי ו-APIs של נתוני פסיקה](#מחקר-משפטי-ונתוני-פסיקהapis) לגילוי תקדימים
3. **עיבוד מסמכים**: [ניהול מסמכים ו-OCR](#ניהול-מסמכים-ocr-ו-pdf) לדיגיטציה

### למפתחים
1. **התחל עם**: [ספריות NLP ומודלים](#ספריות-nlp-ומודלי-תחום) לעיבוד טקסט
2. **נתוני אימון**: [מאגרי נתונים ומדדים](#מאגרי-נתונים-ומדדים) לפיתוח מודלים  
3. **תשתית**: [אינטליגנציה מסמכים](#אינטליגנציה-מסמכים-כללית-שימושית-למשפטי) לצינורות עבודה

### לארגונים
1. **פתרונות אנטרפרייז**: [OpenContracts](https://github.com/JSv4/OpenContracts) לניתוח חוזים
2. **זרימות עבודה מסמכים**: [docassemble](https://github.com/jhpyle/docassemble) לאוטומציה
3. **ניהול תיקים**: [CourtListener](https://github.com/freelawproject/courtlistener) לנתונים משפטיים

---

## ספריות NLP ומודלי תחום

*כלים חיוניים לעיבוד והבנת טקסט משפטי עם מודלי שפה מתמחים*

| **פרויקט** | **התמחות** | **היקף** | **סטטוס** |
|-------------|-------------|-----------|------------|
| **[LexNLP](https://github.com/LexPredict/lexpredict-lexnlp)** | חילוץ מידע מטקסט משפטי לא מובנה (Python) | עולמי | ![Active](https://img.shields.io/badge/status-active-green) |
| **[Blackstone](https://github.com/ICLRandD/Blackstone)** | צינור spaCy לעיבוד טקסט משפטי ארוך | עולמי | ![Active](https://img.shields.io/badge/status-active-green) |
| **[LEGAL-BERT](https://huggingface.co/nlpaueb/legal-bert-base-uncased)** | וריאנטים מאומנים מראש של BERT לקורפוסים משפטיים | EU/עולמי | ![Stable](https://img.shields.io/badge/status-stable-blue) |
| **[InLegalBERT](https://github.com/Law-AI/pretraining-bert)** 🇮🇳 | מודלים ומתכונים של BERT לקורפוסי חוק הודי | הודו | ![Active](https://img.shields.io/badge/status-active-green) |
| **[CaseHOLD](https://github.com/reglab/casehold)** | משימות ובסיס לניתוח פסיקות | עולמי | ![Research](https://img.shields.io/badge/status-research-orange) |
| **[LeXLMs](https://github.com/coastalcph/lexlms)** | קורפוסים ומשימות בדיקה למודלי שפה משפטיים | רב-לשוני | ![Research](https://img.shields.io/badge/status-research-orange) |

---

## ניתוח חוזים ומסמכים מבוסס בינה מלאכותית

*פלטפורמות ברמת אנטרפרייז לניתוח חוזים אינטליגנטי והבנת מסמכים*

| **פרויקט** | **תכונות** | **הטוב ביותר עבור** | **בגרות** |
|-------------|-------------|----------------------|------------|
| **[OpenContracts](https://github.com/JSv4/OpenContracts)** | ניתוח מסמכים אנטרפרייז עם ניתוח מבוסס בינה מלאכותית (GPL-3) | ארגונים גדולים | ![Enterprise](https://img.shields.io/badge/maturity-enterprise-darkgreen) |
| **[ContraxSuite](https://github.com/LexPredict/lexpredict-contraxsuite)** | פלטפורמת ניתוח חוזים ומסמכים מלאה (AGPL) | שימוש מסחרי | ![Production](https://img.shields.io/badge/maturity-production-green) |
| **[LawGlance](https://github.com/lawglance/lawglance)** | עוזר משפטי בינה מלאכותית מבוסס RAG חינמי וקוד פתוח | עסקים קטנים ואנשים פרטיים | ![Community](https://img.shields.io/badge/maturity-community-blue) |
| **[OpenEDGAR](https://github.com/LexPredict/openedgar)** 🇺🇸 | מסגרת למאגרי נתונים חיפושיים של EDGAR filings | ניירות ערך אמריקאיים | ![Stable](https://img.shields.io/badge/maturity-stable-lightblue) |
| **[CUAD Tools](https://github.com/TheAtticusProject/cuad)** | קוד וממשקי נתונים להבנת חוזים | מחקר | ![Research](https://img.shields.io/badge/maturity-research-orange) |

---

## מחקר משפטי ונתוני פסיקה/APIs

*מאגרי נתונים ו-APIs מקיפים למחקר משפטי וגילוי פסיקה*

| **פרויקט** | **כיסוי** | **שיפוט** | **גישה ל-API** |
|-------------|-----------|------------|----------------|
| **[CourtListener](https://github.com/freelawproject/courtlistener)** 🇺🇸 | פלטפורמה ראשית לנתונים ומחקר משפטי | ארצות הברית | ![API](https://img.shields.io/badge/API-available-green) |
| **[Juriscraper](https://github.com/freelawproject/juriscraper)** 🇺🇸 | מגרדים לחוות דעת, טיעונים בעל פה, תוכן PACER | ארצות הברית | ![Tools](https://img.shields.io/badge/type-tools-blue) |
| **[Eyecite](https://github.com/freelawproject/eyecite)** 🇺🇸 | חולץ ציטוטים משפטיים מהיר וחזק | ארצות הברית | ![Library](https://img.shields.io/badge/type-library-purple) |
| **[Caselaw Access Project](https://lil.law.harvard.edu/our-work/caselaw-access-project/)** 🇺🇸 | יותר מ-6.7 מיליון החלטות בית משפט אמריקאי עם API | ארצות הברית | ![API](https://img.shields.io/badge/API-available-green) |
| **[UK National Archives](https://nationalarchives.github.io/ds-find-caselaw-docs/public/)** 🇬🇧 | API ציבורי לפסקי דין בריטיים | בריטניה | ![API](https://img.shields.io/badge/API-available-green) |
| **[Open Legal Data](https://github.com/openlegaldata/oldp)** 🇩🇪 | פלטפורמה ו-API לנתונים משפטיים גרמניים | גרמניה | ![Platform](https://img.shields.io/badge/type-platform-orange) |

---

## גילוי אלקטרוני ותביעות

*כלים מתמחים לגילוי משפטי, בדיקת מסמכים ותמיכה בתביעות*

| **פרויקט** | **יכולות** | **מקרה שימוש** | **רישיון** |
|-------------|-------------|------------------|------------|
| **[FreeEed](https://github.com/shmsoft/FreeEed)** | עיבוד eDiscovery מלא (OCR, אינדקס, מטאדאטה) | גילוי בקנה מידה גדול | ![Open Source](https://img.shields.io/badge/license-Apache-blue) |
| **[FreeDiscovery](https://github.com/FreeDiscovery/FreeDiscovery)** | מנוע איחזור מידע מבוסס scikit-learn | ניתוח מסמכים | ![Open Source](https://img.shields.io/badge/license-BSD-green) |
| **[FOIAMachine](https://github.com/cirlabs/foiamachine)** 🇺🇸 | ניהול ושליחת בקשות FOIA עם ספריית סוכנויות | שקיפות ממשלתית | ![Open Source](https://img.shields.io/badge/license-MIT-lightblue) |

---

## ניהול מסמכים, OCR ו-PDF

*כלים חיוניים לדיגיטציה, ניהול ועיבוד זרימות עבודה של מסמכים*

| **פרויקט** | **פונקציה מרכזית** | **ביצועים** | **תכונות מיוחדות** |
|-------------|-------------------|--------------|---------------------|
| **[paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** | מערכת ניהול מסמכים מארחת עצמית | ![High](https://img.shields.io/badge/performance-high-green) | ארכיון חיפושי, תיוג בינה מלאכותית |
| **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** | ארגז כלים PDF מבוסס רשת מקומי | ![Fast](https://img.shields.io/badge/performance-fast-brightgreen) | פיצול/מיזוג/המרה/אופטימיזציה |
| **[OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)** | הוספת שכבת טקסט OCR ל-PDFs סרוקים | ![Reliable](https://img.shields.io/badge/performance-reliable-blue) | יציאת PDF/A חיפושית |
| **[Paperless-AI](https://github.com/clusterzx/paperless-ai)** | תוסף בינה מלאכותית ל-paperless-ngx | ![Smart](https://img.shields.io/badge/performance-smart-purple) | חיפוש סמנטי, סיווג אוטומטי |

---

## הרכבת מסמכים וכללים כקוד

*פלטפורמות לאוטומציה של יצירת מסמכים משפטיים ויישום היגיון משפטי*

| **פרויקט** | **שימוש ראשי** | **משתמשי יעד** | **רמה טכנית** |
|-------------|-----------------|-----------------|----------------|
| **[docassemble](https://github.com/jhpyle/docassemble)** | פלטפורמת מערכת מומחים לראיונות מודרכים | מקצוענים משפטיים | ![Medium](https://img.shields.io/badge/technical-medium-orange) |
| **[AssemblyLine](https://github.com/SuffolkLITLab/docassemble-AssemblyLine)** 🇺🇸 | ערכת כלים לאוטומציה של טפסי בית משפט | מערכות בית משפט | ![Low](https://img.shields.io/badge/technical-low-green) |
| **[Blawx](https://github.com/Lexpedite/blawx)** | סביבת כללים כקוד ויזואלית | טכנולוגים משפטיים | ![High](https://img.shields.io/badge/technical-high-red) |
| **[Catala](https://github.com/CatalaLang/catala)** | שפת תכנות ליישום נאמן של חוקים | מפתחים | ![High](https://img.shields.io/badge/technical-high-red) |

---

## מאגרי נתונים ומדדים

*נתוני אימון איכותיים ומדדי הערכה לפיתוח בינה מלאכותית משפטית*

| **מאגר נתונים** | **סוג תוכן** | **כיסוי** | **קנה מידה** | **הטוב ביותר עבור** |
|------------------|--------------|-----------|---------------|---------------------|
| **[Pile of Law](https://github.com/Breakend/PileOfLaw)** 🇺🇸 | טקסטים משפטיים/מנהליים | ממוקד אמריקאי | ![Large](https://img.shields.io/badge/scale-large-green) | אימון מודלי שפה |
| **[MultiLegalPile](https://huggingface.co/datasets/joelniklaus/Multi_Legal_Pile)** 🌍 | קורפוס משפטי רב-לשוני | 24 שפות | ![Massive](https://img.shields.io/badge/scale-massive-darkgreen) | מודלים רב-לשוניים |
| **[LexGLUE](https://github.com/coastalcph/lex-glue)** 🇪🇺🇺🇸 | מדד רב-משימתי | EU/US/רב | ![Medium](https://img.shields.io/badge/scale-medium-blue) | הערכת NLU משפטי |
| **[LEXTREME](https://arxiv.org/html/2301.13126v3)** 🌍 | משימות משפטיות רב-לשוניות | 24 שפות | ![Large](https://img.shields.io/badge/scale-large-green) | הערכה חוצת שפות |
| **[LegalBench](https://github.com/HazyResearch/legalbench)** | משימות חשיבה משפטית | עולמי | ![Comprehensive](https://img.shields.io/badge/scale-comprehensive-purple) | חשיבה משפטית LLM |
| **[LegalBench-RAG](https://github.com/zeroentropy-ai/legalbenchrag)** | מדד איחזור חוזים | עולמי | ![Focused](https://img.shields.io/badge/scale-focused-orange) | הערכת מערכות RAG |
| **[CUAD](https://github.com/TheAtticusProject/cuad)** | הערות סעיפי חוזה | עולמי | ![Specialized](https://img.shields.io/badge/scale-specialized-lightblue) | הבנת חוזים |
| **[CaseHOLD](https://github.com/reglab/casehold)** 🇺🇸 | ניתוח פסיקות | ארצות הברית | ![Targeted](https://img.shields.io/badge/scale-targeted-yellow) | חשיבה משפטית |

---

## אינטליגנציה מסמכים כללית (שימושית למשפטי)

*לא ספציפי למשפט, אבל נמצא בשימוש נרחב בצינורות בינה מלאכותית משפטית לעיבוד מסמכים*

| **פרויקט** | **התמחות** | **סוגי קלט** | **ביצועים** |
|-------------|-------------|--------------|--------------|
| **[GROBID](https://github.com/kermitt2/grobid)** | חילוץ מבנה מסמכים באמצעות למידת מכונה | PDF → TEI/XML | ![High](https://img.shields.io/badge/accuracy-high-green) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | עיבוד מקדים לצינורות RAG | PDF/Office/HTML | ![Versatile](https://img.shields.io/badge/type-versatile-blue) |
| **[Layout Parser](https://github.com/Layout-Parser/layout-parser)** | זיהוי פריסה באמצעות למידה עמוקה | פורמטים מרובים | ![Advanced](https://img.shields.io/badge/tech-advanced-purple) |
| **[Docling](https://github.com/docling-project/docling)** | ניתוח מסמכים מודרני | PDF/DOCX/PPTX/HTML | ![Modern](https://img.shields.io/badge/approach-modern-lightgreen) |
| **[Nougat](https://github.com/facebookresearch/nougat)** | OCR עצבי למסמכים אקדמיים | PDFs אקדמיים | ![Specialized](https://img.shields.io/badge/focus-specialized-orange) |
| **[Marker](https://github.com/datalab-to/marker)** | המרה מהירה של PDF ל-Markdown | PDF | ![Fast](https://img.shields.io/badge/speed-fast-brightgreen) |

---

## למידה, קהילות ואוספים

*קהילות ומשאבי למידה חיוניים למקצוענים בתחום הבינה המלאכותית המשפטית*

| **משאב** | **התמקדות** | **גודל קהילה** | **רמת פעילות** |
|-----------|-------------|----------------|-----------------|
| **[Free Law Project](https://github.com/freelawproject)** | מערכת אקולוגית של נתונים משפטיים פתוחים | ![Large](https://img.shields.io/badge/size-large-green) | ![Very Active](https://img.shields.io/badge/activity-very_active-brightgreen) |
| **[Awesome Legal NLP](https://github.com/maastrichtlawtech/awesome-legal-nlp)** | מחקר אקדמי מאוצר | ![Medium](https://img.shields.io/badge/size-medium-blue) | ![Active](https://img.shields.io/badge/activity-active-green) |

---

## תרומה

נשמח לעזרתכם להפוך את הרשימה הזו לטובה עוד יותר! כך תוכלו לתרום:

### הנחיות הגשה

**חובה:**
- קוד פתוח עם רישיון מאושר OSI
- תיעוד ו-README ברורים
- תחזוקה פעילה (commits בתוך 12 חודשים)
- רלוונטיות ברורה לזרימות עבודה משפטיות

**רצוי:**
- אימוץ קהילתי (כוכבי GitHub)
- דוגמאות שימוש מסחרי
- בדיקות ו-CI/CD
- מדדי ביצועים

### איך להגיש

1. **Fork** את המאגר הזה
2. **הוסף** את הפרויקט שלך בקטע המתאים (סדר אלפביתי)
3. **כלול**: שם, תיאור בשורה אחת, קישור/ים ראשיים, דגל שיפוט אם רלוונטי
4. **בדוק** את הקישורים והעיצוב שלך
5. **הגש** pull request עם תיאור ברור

### בדיקות איכות אופציונליות

```bash
# בודק קישורים
npx lychee --no-progress --accept 200,999 README.md

# לינטר רשימת awesome  
npx awesome-lint
```

---

## מדיניות אוצרות

| **אנחנו כוללים** | **אנחנו לא כוללים** |
|-------------------|---------------------|
| פרויקטי קוד פתוח בלבד | פלטפורמות SaaS סגורות |
| היקף עולמי (עם תיוג שיפוט) | כלים פנימיים/פרטיים |
| כלים מוכנים לשימוש מסחרי | מאגרים ניסיוניים נטושים |
| מאגרי נתונים/מדדים איכותיים | נתונים איכות נמוכה או כפולים |
| קהילות פעילות ומכובדות | קהילות לא פעילות או מזיקות |

**איכות קודמת:** אנו מעדיפים פרויקטים מתוחזקים היטב עם תיעוד טוב ושימוש בעולם האמיתי על פני כיסוי מקיף.

---

## רישיון

<div align="center">

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

**CC0 1.0 Universal** – ללא זכויות שמורות. 

*אתם מוזמנים להעתיק, לערבב ולבנות על הרשימה הזו.*

`על ידי תרומה, אתם מסכימים לרשות את התרומה שלכם תחת CC0.`

</div>

---

<div align="center">

### **קרדיטים**

**נוצר על ידי [Chen Friedman](https://github.com/chenfriedman)**  
**מופעל על ידי [Legal Tech Systems](https://legaltech.systems)**

---

**תנו כוכב למאגר אם זה עזר לכם!**

[![GitHub Stars](https://img.shields.io/github/stars/lawcal-ai/awesome-legal-ai?style=for-the-badge&logo=github)](https://github.com/lawcal-ai/awesome-legal-ai/stargazers)

**נוצר באהבה עבור קהילת הטכנולוגיה המשפטית**

</div>
