<div dir='rtl' lang='he'>

# תרומה לפרוייקטי קוד פתוח

*למה כדאי לתרום לפרוייקט קוד פתוח?*

1. במהלך הלימודים, אתם פותרים מטלות שבהן אתם כותבים קוד חדש. אבל בעבודה, כנראה תצטרכו להשתלב במערכת-תוכנה קיימת, ומורכבת הרבה יותר. תצטרכו לקרוא ולהבין קוד קיים, לבדוק ולהריץ אותו, לשנות ולהרחיב אותו. תרומה למערכת קוד-פתוח מאפשרת לכם לפתח את הכישורים החיוניים הללו.
2. מערכות קוד-פתוח מנוהלות על-ידי מתכנתים ותיקים ומנוסים. תרומה למערכות כאלו מאפשרת לכם ליצור קשרים עם מתכנתים אלה וללמוד מהניסיון שלהם.
3. הקוד שתכתבו לא "יישב בבוידם" אלא ישמש בפועל מתכנתים ומשתמשים רבים ברחבי העולם.
4. השם שלכם יירשם ברשימת התורמים למערכת; זו תרומה משמעותית לקורות-החיים שלכם.

*מה תצטרכו לעשות?*

 * להוריד קוד של תוכנת קוד-פתוח כלשהי, ולבנות אותו על המחשב שלכם. יש כמה תוכנות לבחירה – ראו בהמשך.
 * להצטרף לקהילת המפתחים ולברר איזה שיפורים ותוספות הם מוכנים להכניס למערכת.
 * לממש את ההרחבה, להגיש pull request, ולהיות בקשר רציף עם המפתחים עד שההרחבה שלכם נכנסת לקוד הראשי.

הנה כמה דוגמאות למערכות ושיפורים שאפשר להכניס בהן – אתם מוזמנים להציע רעיונות דומים נוספים:

 * מערכת INGInious – מערכת קוד פתוח לבדיקה אוטומטית של תרגילי תיכנות. הרחבה  אפשרית: לאפשר למתרגלים להעלות מטלות דרך גיטהאב, לאפשר לסטודנטים להגיש מטלות דרך גיטהאב, וכן להעלות למערכת את המטלות בקורסי התיכנות במחלקה (שנה א + ב) (https://docs.inginious.org/)
 * ספריית `networkx`  - רשתות וגרפים בפייתון (https://networkx.github.io/documentation/stable/developer/index.html). הרחבה אפשרית:  הוספת אלגוריתמים שונים בגרפים ורשתות.
 * ספריית `cvxpy`  - אופטימיזציה בפייתון. הרחבה אפשרית:  הוספת אלגוריתמים שונים לאופטימיזציה.
  * גאוגברה (https://dev.geogebra.org/trac)  מערכת גרפית לחישובים אלגבריים וגיאומטריים. הרחבה אפשרית: הוספת אלגוריתמים שונים בגיאומטריה חישובית. הרחבה טובה יותר: תרגום המערכת לשפת פייתון.
 * כנסת פתוחה (https://github.com/hasadna/Open-Knesset ) – מערכת לשיתוף הציבור בפעילות הכנסת. הרחבה אפשרית: ממשק שיאפשר לאנשי-ציבור לקבל משוב מהבוחרים על הצעות חוק.
 * בניית מערכת לשאלות ותשובות בסגנון stackexchange.com, אבל בעברית. יש למצוא מערכת קיימת בקוד פתוח, ולהוסיף לה תמיכה בעברית.
 * [פרוייקטים מ"הסדנא לידע ציבורי"](https://www.hasadna.org.il/%D7%94%D7%AA%D7%A0%D7%93%D7%91%D7%95%D7%AA/).
 * טק-סטודיו ( https://github.com/texstudio-org/texstudio ) - תוכנה לעריכת מאמרים מדעיים. הרחבה אפשרית: מערכת לבדיקת נכונות של משוואות מתימטיות. 
 * ויקיפדיה: הוספת עזרי-למידה שונים, למשל "מד התקדמות" לפי קטגוריה, שיעזור לקורא לדעת איזה אחוז מהנושאים בקטגוריה הוא כבר למד, ומה עדיין נשאר לו ללמוד.
 * טקסטיה ( https://github.com/erelsgl/textia ) משחק ישן שכתבתי ללימוד תנ"ך. הרחבות אפשריות: לכתוב הכל מחדש, עם ממשק יפה ומעוצב ואפשרות לריבוי שחקנים.
 * Visual Studio Code ( https://github.com/microsoft/vscode )  - הוספת תמיכה לכתיבת טקסטים בעברית (מימין לשמאל).
 * גיאומטריה חישובית בפייתון ( https://github.com/pygae/galgebra  או https://wolfv.medium.com/introducing-scikit-geometry-ae1dccaad5fd או https://www.toptal.com/python/computational-geometry-in-python-from-theory-to-implementation  ). הרחבות אפשריות: מימוש ממשק גרפי ואלגוריתמים גיאומטריים מעניינים.

הפרוייקט מיועד לסטודנטים ש-
 * אוהבים לתכנת ולתקן באגים;
 * יודעים לתקשר היטב באנגלית, מסוגלים להשתתף בדיונים בקהילת המפתחים;
 * מתמידים – לא מתייאשים גם כשהקוד לא מתקבל בפעם הראשונה.

</div>