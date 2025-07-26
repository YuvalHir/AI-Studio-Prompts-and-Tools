<div dir="rtl">

# 🇮🇱 Google AI Studio - ערכת כלים ותיקוני עברית אולטימטיבית (v3.2) 🇮🇱

[![גרסה](https://img.shields.io/badge/גרסה-3.2-blue.svg)](https://greasyfork.org/he/scripts/542486)
[![רישיון](https://img.shields.io/badge/רישיון-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![התקנה](https://img.shields.io/badge/התקן_מ-Greasy_Fork-brightgreen.svg)](https://update.greasyfork.org/scripts/542486/Google%20AI%20Studio%20-%20%D7%99%D7%99%D7%A9%D7%95%D7%A8%20%D7%A2%D7%91%D7%A8%D7%99%D7%AA%20%D7%90%D7%95%D7%9C%D7%98%D7%99%D7%9E%D7%98%D7%99%D7%91%D7%99.user.js)

סקריפט זה משדרג לחלוטין את חוויית השימוש ב-**Google AI Studio** עבור דוברי עברית וכל שפה הנכתבת מימין לשמאל (RTL). הוא לא רק מתקן את בעיות היישור המוכרות, אלא מוסיף כלי פרודוקטיביות חזקים ישירות לממשק המשתמש.

נמאס לכם מטקסט שבור, נוסחאות מתמטיות הפוכות ותפריטים לא נוחים? הסקריפט הזה הוא הפתרון המלא, הכולל תפריט הנחיות דינמי, ניהול חכם של "הוראות מערכת" ועוד.

---

### ✨ תכונות מרכזיות

#### 🎨 **תיקוני תצוגה ויישור חכמים**
*   **יישור מלא לימין:** כל הממשק, כולל תיבת הקלט הראשית, תשובות המודל ורשימות, מיושר לימין באופן מלא.
*   **שימור טקסט LTR:** הסקריפט מזהה אוטומטית פסקאות ובלוקים של קוד או טקסט באנגלית ומשאיר אותם מיושרים לשמאל, לקריאות מקסימלית.
*   **תיקון נוסחאות מתמטיות (`KaTeX`):** נוסחאות מתמטיות תמיד מוצגות נכון משמאל לימין, גם בתוך משפט בעברית.
*   **הזרקה אוטומטית של הנחיית MathJax:** (ניתן לכיבוי) הסקריפט יוסיף אוטומטית להוראות המערכת הנחיה לבקש מהמודל להשתמש בתחביר MathJax ($$...$$ ו-$...$) כדי להבטיח תצוגה תקינה של נוסחאות.

#### 🚀 **כלי פרודוקטיביות**
*   **תפריט "הנחיות מהירות":** תפריט חדש שנוסף בחלונית ההגדרות, המאפשר לטעון הנחיות מוכנות מראש ישירות לתוך "הוראות המערכת" בלחיצת כפתור.
*   **הנחיות דינמיות מ-GitHub:** רשימת ההנחיות נטענת באופן דינמי מקובץ `prompts.json` בפרויקט ה-GitHub הזה, כך שתמיד תקבלו את ההנחיות המעודכנות ביותר.
*   **מערכת הזרקה חכמה:** הסקריפט מזהה הנחיות קודמות שהוא הזריק ו**מחליף** אותן במקום להוסיף הנחיה על גבי הנחיה. סוף סוף לא צריך לנקות את "הוראות המערכת" כל פעם מחדש!
*   **הודעות ומשוב:** קבלו התראות ויזואליות (Toasts) כאשר הנחיה נטענת או מוזרקת בהצלחה.

#### ⚙️ **שליטה והתאמה אישית**
*   **כפתור שליטה בסרגל הכלים:** כפתור "Hebrew Mode" פשוט ונוח נוסף לסרגל הכלים העליון, המאפשר להפעיל ולכבות את כל תכונות היישור של הסקריפט בלחיצה אחת. הבחירה שלכם נשמרת.
*   **תפריט "אפשרויות סקריפט":** לחצו על כפתור ה-`Tune` (כוונון) כדי לפתוח חלונית אפשרויות, בה ניתן להפעיל או לכבות את ההזרקה האוטומטית של הנחיית MathJax.

---

### 🚀 הוראות התקנה

1.  **התקינו מנהל סקריפטים:** ודאו שהתוסף [**Tampermonkey**](https://www.tampermonkey.net/) (או תוסף דומה כמו Greasemonkey / Violentmonkey) מותקן בדפדפן שלכם (כרום, פיירפוקס, אדג').
2.  **התקינו את הסקריפט:** לחצו על הכפתור הירוק למעלה **"התקן מ-Greasy Fork"** או [לחצו כאן](https://update.greasyfork.org/scripts/542486/Google%20AI%20Studio%20-%20%D7%99%D7%99%D7%A9%D7%95%D7%A8%20%D7%A2%D7%91%D7%A8%D7%99%D7%AA%20%D7%90%D7%95%D7%9C%D7%98%D7%99%D7%9E%D7%98%D7%99%D7%91%D7%99.user.js).
3.  **אשרו את ההתקנה:** ייפתח חלון חדש של Tampermonkey. לחצו על הכפתור **"Install"**.
4.  **זהו!** רעננו את העמוד של [AI Studio](https://aistudio.google.com/) ותתחילו ליהנות מחוויה משודרגת ונוחה בעברית.

---

### 🤝 תרומה

יש לכם רעיון להנחיה שימושית? אתם מוזמנים לערוך את קובץ ה-`prompts.json` ולשלוח Pull Request.

</div>

---

<div dir="ltr">

# 🇮🇱 Google AI Studio - Ultimate RTL & Hebrew Enhancement Suite (v3.2) 🇮🇱

[![Version](https://img.shields.io/badge/version-3.2-blue.svg)](https://greasyfork.org/en/scripts/542486)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Install](https://img.shields.io/badge/Install_From-Greasy_Fork-brightgreen.svg)](https://update.greasyfork.org/scripts/542486/Google%20AI%20Studio%20-%20%D7%99%D7%99%D7%A9%D7%95%D7%A8%20%D7%A2%D7%91%D7%A8%D7%99%D7%AA%20%D7%90%D7%95%D7%9C%D7%98%D7%99%D7%9E%D7%98%D7%99%D7%91%D7%99.user.js)

This script completely overhauls the **Google AI Studio** experience for Hebrew and other Right-to-Left (RTL) language speakers. It doesn't just fix the common alignment issues; it adds powerful productivity tools directly into the UI.

Tired of broken text, reversed math formulas, and clunky menus? This script is the all-in-one solution, featuring a dynamic prompt menu, intelligent system instruction management, and much more.

---

### ✨ Key Features

#### 🎨 **Smart Display & Alignment Fixes**
*   **Full RTL Alignment:** The entire interface, including the main input, model responses, and lists, is fully right-aligned.
*   **LTR Text Preservation:** The script automatically detects paragraphs, code blocks, or English text and keeps them left-aligned for maximum readability.
*   **Mathematical Formula Fix (`KaTeX`):** Math formulas are always rendered correctly from left-to-right, even within a Hebrew sentence.
*   **Automatic MathJax Prompt Injection:** (Configurable) The script will automatically add a directive to the system instructions, asking the model to use MathJax syntax (`$$...$$` and `$..$`) to ensure proper rendering of equations.

#### 🚀 **Productivity Tools**
*   **"Fast Prompts" Menu:** A new menu in the settings panel allows you to load preset prompts directly into the "System Instructions" with a single click.
*   **Dynamic Prompts from GitHub:** The prompt list is loaded dynamically from the `prompts.json` file in this GitHub repository, ensuring you always have the most up-to-date prompts.
*   **Intelligent Injection System:** The script detects previously injected prompts and **replaces** them instead of stacking new ones. No more manually cleaning up your system instructions!
*   **Notifications & Feedback:** Get visual toast notifications when a prompt is successfully loaded or injected.

#### ⚙️ **Control & Customization**
*   **Header Toggle Switch:** A simple "Hebrew Mode" toggle is added to the top header, allowing you to enable or disable all alignment features with one click. Your choice is saved automatically.
*   **"Script Options" Panel:** Click the `Tune` icon to open an options panel, where you can enable or disable the automatic MathJax prompt injection.

---

### 🚀 How to Install

1.  **Install a Userscript Manager:** Make sure you have an extension like [**Tampermonkey**](https://www.tampermonkey.net/) (or a similar one like Greasemonkey / Violentmonkey) installed in your browser (Chrome, Firefox, Edge).
2.  **Install the Script:** Click the green "Install From Greasy Fork" badge above, or [click here](https://update.greasyfork.org/scripts/542486/Google%20AI%20Studio%20-%20%D7%99%D7%99%D7%A9%D7%95%D7%A8%20%D7%A2%D7%91%D7%A8%D7%99%D7%AA%20%D7%90%D7%95%D7%9C%D7%98%D7%99%D7%9E%D7%98%D7%99%D7%91%D7%99.user.js).
3.  **Confirm Installation:** A new Tampermonkey tab will open. Click the **"Install"** button.
4.  **All Set!** Just refresh the [AI Studio](https://aistudio.google.com/) page and enjoy a vastly improved and more comfortable Hebrew experience.

---

### 🤝 Contributing

Have an idea for a useful prompt? Feel free to edit the `prompts.json` file and submit a Pull Request.

</div>
