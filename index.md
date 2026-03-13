# מדיניות פרטיות — דיבורון

**עדכון אחרון: 7 במרץ 2026**

## מבוא

מדיניות פרטיות זו מתארת כיצד אפליקציית דיבורון ("האפליקציה", "אנחנו") מטפלת במידע בעת השימוש בה על ידכם או על ידי ילדכם. דיבורון היא משחק זיהוי דיבור המיועד לילדים בגילאי 2–4. אנו מחויבים להגנה על פרטיותם של ילדים ומשפחותיהם.

בהורדה, התקנה או שימוש באפליקציה, אתם מסכימים לתנאי מדיניות פרטיות זו. אם אינכם מסכימים, אנא אל תשתמשו באפליקציה.

## מידע שאנו אוספים

### מידע שנמסר על ידי הורים או אפוטרופוסים

בעת יצירת פרופיל ילד/ה באפליקציה, ההורה או האפוטרופוס מוסר את המידע הבא:

- **שם פרטי של הילד/ה** — משמש להתאמה אישית של משוב קולי ותצוגה באפליקציה.
- **מין הילד/ה (בן/בת)** — משמש להתאמת דקדוק עברי במשוב הקולי (לשון זכר/נקבה).
- **בחירת אווטאר** — אמוג'י שנבחר לייצוג הפרופיל.

### מידע שנוצר במהלך המשחק

האפליקציה מתעדת באופן אוטומטי את הנתונים הבאים במהלך המשחק:

- **ציוני משחק** — דירוג כוכבים (1–5) לכל מילה, מספר ניסיונות וציונים מיטביים.
- **סטטיסטיקות קטגוריות** — אילו קטגוריות ומילים שוחקו, ובאיזו שפה.
- **חותמות זמן** — מועד יצירת הפרופיל ומועד המשחק האחרון של כל מילה.

### מידע שאנו לא אוספים

- אנו **לא** אוספים כתובות דוא"ל, מספרי טלפון, כתובות מגורים או כל פרט יצירת קשר אישי אחר.
- אנו **לא** אוספים תמונות, סרטונים או הקלטות שמע.
- אנו **לא** אוספים נתוני מיקום.
- אנו **לא** אוספים מזהי מכשיר, מזהי פרסום או היסטוריית גלישה.
- אנו **לא** משתמשים בעוגיות (cookies) או טכנולוגיות מעקב דומות.

## אחסון המידע

**כל המידע מאוחסן באופן מקומי על המכשיר בלבד.** האפליקציה משתמשת במסד נתונים מקומי (Android Room) ובהעדפות מקומיות (SharedPreferences) לאחסון פרופילי ילדים, ציוני משחק והגדרות. שום מידע אינו מועלה לשרת, שירות ענן או מסד נתונים חיצוני כלשהו המופעל על ידנו.

מידע המאוחסן על המכשיר:

| מידע | אמצעי אחסון | מטרה |
|------|-------------|------|
| שם הילד/ה, מין, אווטאר | מסד נתונים מקומי (Room) | התאמה אישית של הפרופיל |
| ציוני משחק וסטטיסטיקות | מסד נתונים מקומי (Room) | מעקב אחר התקדמות |
| העדפת שפה | העדפות מקומיות (SharedPreferences) | הגדרת שפת האפליקציה |
| הגדרות שמע | העדפות מקומיות (SharedPreferences) | העדפות השתקה |

המשתמשים יכולים למחוק פרופילים בודדים ואת כל המידע המשויך אליהם, או לאפס סטטיסטיקות בכל עת דרך ממשק האפליקציה.

## הרשאות

האפליקציה דורשת את ההרשאות הבאות:

### מיקרופון (RECORD_AUDIO)

- **מטרה:** המיקרופון משמש אך ורק לזיהוי דיבור בזמן אמת במהלך המשחק. הילד/ה אומר/ת מילה, והאפליקציה משתמשת בשירות זיהוי הדיבור המובנה של אנדרואיד כדי לזהות מה נאמר.
- **השמע אינו מוקלט או נשמר.** קלט המיקרופון מעובד בזמן אמת על ידי שירות זיהוי הדיבור של המכשיר ואינו נשמר על המכשיר או מועבר לשרתים שלנו.
- **בקרת הורים:** כפתור השתקה זמין במהלך המשחק, המאפשר להורים להשבית זמנית את קלט המיקרופון.

### אינטרנט (INTERNET)

- **מטרה:** גישה לאינטרנט נדרשת מכיוון ששירות זיהוי הדיבור של אנדרואיד (המסופק בדרך כלל על ידי Google) שולח נתוני שמע לשרתים מרוחקים לעיבוד ומחזיר את הטקסט המזוהה. האפליקציה עצמה אינה מבצעת בקשות רשת לשרתים שלנו או לשירותי צד שלישי אחרים.
- **ללא אינטרנט, אין משחק:** האפליקציה מציגה הודעה ברורה כאשר אין חיבור לאינטרנט, מכיוון שזיהוי הדיבור אינו יכול לפעול ללא חיבור.

## שירותי צד שלישי

### זיהוי דיבור של Google

האפליקציה משתמשת ב-API המובנה של אנדרואיד לזיהוי דיבור (`SpeechRecognizer`), המופעל ברוב המכשירים על ידי שירות זיהוי הדיבור של Google. כאשר המיקרופון פעיל במהלך המשחק, נתוני שמע עשויים להיות מועברים לשרתי Google לעיבוד. מידע זה מטופל בהתאם ל[מדיניות הפרטיות של Google](https://policies.google.com/privacy).

### המרת טקסט לדיבור של Google

האפליקציה משתמשת ב-API המובנה של אנדרואיד להמרת טקסט לדיבור (`TextToSpeech`) כדי לספק משוב קולי. בהתאם להגדרות המכשיר, חלק מקולות ההמרה עשויים לדרוש גישה לרשת. זה מטופל על ידי מנוע ה-TTS של המכשיר, בכפוף למדיניות הפרטיות של ספק המנוע.

### ללא שירותי צד שלישי נוספים

האפליקציה **אינה** כוללת או משתמשת ב:

- שירותי אנליטיקה (כגון Google Analytics, Firebase Analytics)
- רשתות פרסום או SDKs של מודעות
- שירותי דיווח קריסות
- SDKs של רשתות חברתיות
- כל שירות איסוף מידע אחר של צד שלישי

## פרטיות ילדים (תאימות ל-COPPA ו-GDPR)

דיבורון מיועדת לשימוש על ידי ילדים בגילאי 2–4 בפיקוח הורים. אנו מתייחסים לפרטיות ילדים ברצינות:

- **שום מידע אישי אינו יוצא מהמכשיר** דרך האפליקציה עצמה. העברת המידע החיצונית היחידה מתרחשת דרך שירות זיהוי הדיבור של אנדרואיד (ראו לעיל).
- **לא מתבצע מעקב התנהגותי או יצירת פרופילים.**
- **לא מוצגת פרסומת ממוקדת.** האפליקציה אינה מכילה פרסומות מכל סוג שהוא.
- **אין רכישות בתוך האפליקציה.**
- **מעורבות הורים** מעודדת. יצירת פרופיל, מחיקת פרופיל ואיפוס סטטיסטיקות מוגנים באמצעות תרגילי חשבון פשוטים כדי להבטיח שהורה או אפוטרופוס מבצעים פעולות אלו.
- **מזעור מידע:** אנו אוספים רק את המידע המינימלי הנדרש לפעולת האפליקציה (שם פרטי להתאמה אישית ומין למשוב עברי תקין דקדוקית).

## שמירת מידע ומחיקתו

- כל המידע נשאר על המכשיר כל עוד האפליקציה מותקנת.
- הורים יכולים **למחוק פרופילי ילדים בודדים** (כולל כל נתוני המשחק המשויכים) בכל עת דרך מסך ניהול המשתמשים באפליקציה.
- הורים יכולים **לאפס סטטיסטיקות משחק** לכל פרופיל בכל עת.
- **הסרת התקנת האפליקציה** מוחקת לצמיתות את כל המידע המאוחסן מקומית.

## שיתוף מידע

אנו **לא** משתפים, מוכרים, משכירים או סוחרים במידע כלשהו של משתמשים עם צדדים שלישיים. מכיוון שכל המידע מאוחסן מקומית על המכשיר, אין לנו גישה אליו.

## אבטחה

כל המידע מאוחסן באזור האחסון הפרטי של האפליקציה על המכשיר, המוגן על ידי מנגנון ה-sandboxing של אנדרואיד. אף אפליקציה אחרת אינה יכולה לגשת למידע זה בתנאי פעולה רגילים.

## שינויים במדיניות פרטיות זו

אנו עשויים לעדכן מדיניות פרטיות זו מעת לעת. כל שינוי ישתקף בעדכון תאריך "עדכון אחרון" בראש מסמך זה. אנו ממליצים לעיין במדיניות פרטיות זו מעת לעת.

## יצירת קשר

אם יש לכם שאלות או חששות בנוגע למדיניות פרטיות זו או לנוהגי המידע של האפליקציה, אנא פנו אלינו:

**דוא"ל:** oren5611@gmail.com

---

*מדיניות פרטיות זו חלה על אפליקציית דיבורון, שם חבילה `com.kidsspeechgame`, הזמינה ב-Google Play.*

---

# Privacy Policy for Diburon (דיבורון)

**Last updated: March 7, 2026**

## Introduction

This Privacy Policy describes how the Diburon (דיבורון) mobile application ("the App", "we", "us", or "our") handles information when you or your child use the App. Diburon is a speech recognition game designed for children aged 2–4. We are committed to protecting the privacy of children and their families.

By downloading, installing, or using the App, you agree to the terms of this Privacy Policy. If you do not agree, please do not use the App.

## Information We Collect

### Information Provided by Parents or Guardians

When creating a child profile in the App, a parent or guardian provides the following information:

- **Child's first name** — used to personalize voice feedback and display within the App.
- **Child's gender (boy/girl)** — used to adjust Hebrew grammar in spoken feedback (masculine/feminine forms).
- **Avatar selection** — an emoji chosen to represent the child's profile.

### Information Generated Through Gameplay

The App automatically records the following during gameplay:

- **Game scores** — star ratings (1–5) per word, number of attempts, and best scores.
- **Category statistics** — which categories and words have been played, in which language.
- **Timestamps** — when a profile was created and when a word was last played.

### Information We Do NOT Collect

- We do **not** collect email addresses, phone numbers, physical addresses, or any other personal contact information.
- We do **not** collect photos, videos, or persistent audio recordings.
- We do **not** collect precise or approximate location data.
- We do **not** collect device identifiers, advertising IDs, or browser/search history.
- We do **not** use cookies or similar tracking technologies.

## How Information Is Stored

**All data is stored locally on the device only.** The App uses an on-device database (Android Room) and local preferences (SharedPreferences) to store child profiles, game scores, and settings. No data is uploaded to any server, cloud service, or external database operated by us.

Data stored on the device includes:

| Data | Storage Method | Purpose |
|------|---------------|---------|
| Child's name, gender, avatar | Room Database (on device) | Profile personalization |
| Game scores and statistics | Room Database (on device) | Tracking progress |
| Language preference | SharedPreferences (on device) | App language setting |
| Sound settings | SharedPreferences (on device) | Mute/unmute preferences |

Users can delete individual profiles and their associated data, or reset statistics at any time through the App's interface.

## Permissions

The App requires the following Android permissions:

### Microphone (RECORD_AUDIO)

- **Purpose:** The microphone is used solely for real-time speech recognition during gameplay. The child speaks a word, and the App uses Android's built-in speech recognition service to determine what was said.
- **Audio is not recorded or stored.** The microphone input is processed in real time by the device's speech recognition service and is not saved to the device or transmitted to our servers.
- **Parental control:** A mute button is available during gameplay, allowing parents to temporarily disable microphone input.

### Internet (INTERNET)

- **Purpose:** Internet access is required because Android's speech recognition service (typically provided by Google) sends audio data to remote servers for processing and returns the recognized text. The App itself does not make any network requests to its own servers or any third-party services.
- **No internet, no gameplay:** The App displays a clear message when internet connectivity is unavailable, as speech recognition cannot function without it.

## Third-Party Services

### Google Speech Recognition

The App uses Android's built-in `SpeechRecognizer` API, which on most devices is powered by Google's speech recognition service. When the microphone is active during gameplay, audio data may be transmitted to Google's servers for processing. This data is handled according to [Google's Privacy Policy](https://policies.google.com/privacy).

### Google Text-to-Speech

The App uses Android's built-in `TextToSpeech` API to provide spoken feedback. Depending on device configuration, some text-to-speech voices may require network access. This is handled by the device's TTS engine, subject to the engine provider's privacy policy.

### No Other Third-Party Services

The App does **not** include or use:

- Analytics services (e.g., Google Analytics, Firebase Analytics)
- Advertising SDKs or ad networks
- Crash reporting services
- Social media SDKs
- Any other third-party data collection services

## Children's Privacy (COPPA and GDPR-K Compliance)

Diburon is designed for use by children aged 2–4 under parental supervision. We take children's privacy seriously:

- **No personal data leaves the device** through the App itself. The only external data transmission occurs through Android's speech recognition service (see above).
- **No behavioral tracking or profiling** is performed.
- **No targeted advertising** is displayed. The App contains no advertisements of any kind.
- **No in-app purchases** are offered.
- **Parental involvement** is encouraged. Profile creation, profile deletion, and statistics reset are protected by simple math challenges to ensure a parent or guardian is performing these actions.
- **Data minimization:** We collect only the minimum information necessary for the App to function (a first name for personalization and gender for grammatically correct Hebrew feedback).

## Data Retention and Deletion

- All data remains on the device for as long as the App is installed.
- Parents can **delete individual child profiles** (including all associated game data) at any time through the App's user management screen.
- Parents can **reset game statistics** for any profile at any time.
- **Uninstalling the App** permanently removes all locally stored data.

## Data Sharing

We do **not** share, sell, rent, or trade any user information with third parties. Since all data is stored locally on the device, we have no access to it.

## Security

All data is stored in the App's private storage area on the device, which is protected by Android's application sandboxing. No other apps can access this data under normal operating conditions.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last updated" date at the top of this document. We encourage you to review this Privacy Policy periodically.

## Contact Us

If you have any questions or concerns about this Privacy Policy or the App's data practices, please contact us at:

**Email:** oren5611@gmail.com

---

*This privacy policy applies to the Diburon (דיבורון) application, package name `com.kidsspeechgame`, available on Google Play.*
