<div dir="rtl" markdown="1">
# שאלות נפוצות

## מה זה QMK?

[QMK](https://github.com/qmk), קיצור עבור Quantum Mechanical Keyboard, הוא קבוצה של אנשים הבונים כלים עבור מקלדות מותאמות אישית. התחלנו עם  [קושחת QMK](https://github.com/qmk/qmk_firmware), פורק של [TMK](https://github.com/tmk/tmk_keyboard) אשר שונה באופן ניכר.

## מה ההבדלים העיקריים בין QMK ו-Keymap TMK?

TMK עוצב ומומש במקור ע״י [Jun Wako](https://github.com/tmk). QMK התחיל כפורק של [Jack Humbert](https://github.com/jackhumbert) של הפרוייקט של TMK עבור Planck. אחרי כמה זמן הפורק של ג׳ק השתנה מזה של TMK וב- 2015 ג׳ק החליט לשנות את שמו  של הפורק ל- QMK.

מנק׳ מבט טכנית, QMK נבנה על גבי TMK ע״י הוספת יכולות ופיצ׳רים חדשים. ראוי לציון ש- QMK הרחיב את מס׳ קודי המקלדת האפשריים ומשתמש בהם למימוש יכולות מתקדמות כמו `S()`, `LCTL()`, ו- `MO()`. ניתן לראות רשימה מלאה של קודי המקלדת האלה ב - [קודי מקלדת](keycodes.md).

מנק׳ מבט של הפרוייקט וניהול הקהילה, TMK מנהל את כל המקלדות הנתמכות בעצמו, עם מעט תמיכה מהקהילה. כל אחד יכול לעשות פורק מהפרוייקט עבור מקלדות אחרות. רק מס׳ מיפויי מקשים נמצאים בברירת המחדל כך שאנשים בד״כ לא משתפים מיפויי מקשים זה עם זה. QMK מעודד את השיתוף של המקלדות וקודי המקשים דרך רפוזיטורי בניהול מרכזי, אשר מקבל את כל בקשות ה- Pull Requests שעומדות בסטנדרט האיכות. רובם מנוהלות ע״י הקהילה, אבל הצוות של QMK עוזר כשנדרש.

לשתי הגישות יש יתרונות וחסרונות וקוד עובר בחופשיות בין TMK ל- QMK כשצריך.
</div>