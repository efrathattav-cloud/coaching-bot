# Coaching Bot: בוט לאתר האימון

בוט צ'אט קטן לאתר של אפרת-יערה חטב. הוא עונה על שאלות של נשים שמתעניינות בליווי ואוסף פרטים לשיחת היכרות. בנוסף, הוא יודע לעצור ולהפנות לגורם מקצועי כשהשיחה יוצאת מתחום האימון.

הפרויקט נבנה כתרגיל לשיעור "Agentic Engineering": תכנון מוצר AI מקצה לקצה **לפני** כתיבת קוד.

## איפה כל חלק מהשיעור

| חלק | קבצים |
|-----|-------|
| **1. Design** (מה, למי, כמה, כמה מהר) | [spec.md](spec.md), [architecture.md](architecture.md) |
| **2. Place** (איפה כל חלק רץ, מגבלות, סודות) | [architecture.md](architecture.md) (בסעיפים Hosting, Limits, Secrets), [.env.example](.env.example) |
| **3. Manage** (לוח, משימות, כללי עבודה) | [practice.md](practice.md), [CLAUDE.md](CLAUDE.md), לוח ה-GitHub Project, Issues ו-Pull Requests |
| **4. Test / Eval** (מה מוכיח שהכל עובד) | [prompts/system-prompt.md](prompts/system-prompt.md), [tests/checklist.md](tests/checklist.md), [evals/cases.md](evals/cases.md), [evals/results.md](evals/results.md) |

## איך העבודה התנהלה

- כל משימה נפתחה כ-**Issue** והופיעה בלוח של **GitHub Projects** (To do, In progress, Done).
- כל משימה קיבלה **ענף משלה** (למשל `3-system-prompt`) ונכנסה ל-`main` דרך **Pull Request**.
- `main` הוא תמיד הגרסה המאושרת.

## איך לנסות את הבוט

1. פותחים שיחה חדשה ב-[Claude.ai](https://claude.ai).
2. מדביקים את התוכן של [prompts/system-prompt.md](prompts/system-prompt.md) כהודעה הראשונה.
3. שואלים את השאלות מ-[evals/cases.md](evals/cases.md) ורושמים את התוצאות ב-[evals/results.md](evals/results.md).
