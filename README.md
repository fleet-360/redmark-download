# RedMark — הורדה והתקנה

ערוץ ההפצה של RedMark, תוסף Revit פנימי. קוד המקור נמצא במאגר פרטי (fleet-360/RedMark); המאגר הזה מחזיק רק את דף ההתקנה ואת הגרסאות.

- `index.html`: דף הוראות ההתקנה, מוגש ב-GitHub Pages מהתיקייה הראשית, בלי שלב בנייה. הוא `noindex` — לא תוסף ציבורי, הקישור נשלח למי שצריך אותו.
- הגרסאות הן GitHub Releases. כפתור ההורדה מצביע תמיד על האחרונה:
  `releases/latest/download/ProAlgorithm-RedMark-Setup.exe`
- התוסף המותקן קורא את `releases/latest/download/latest.json` בכל פתיחה של Revit ומתעדכן לבד.

## פרסום גרסה

לא מעלים קבצים לכאן ידנית. כל push ל-main במאגר המקור מפרסם גרסה (`.github/workflows/deploy.yml` שם), והתוסף בודק כל zip מול ה-SHA-256 שב-`latest.json`.

מספר הגרסה וגודל הקובץ בדף נקראים בזמן טעינה מה-GitHub API, כך שאין צורך לערוך את `index.html` בכל גרסה. הטקסט שכתוב בקובץ הוא רק גיבוי למקרה שה-API לא זמין.
