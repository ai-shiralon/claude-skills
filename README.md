# כל הסקילים של שיר אלון | AI Transformation

מרכז אחד לסקילים נבחרים ל-Claude Code מבית שיר אלון ו-AI Transformation - יצירת תוכן בעברית, פרסום ושיווק, ניהול עסק לעצמאים ווידאו. כל סקיל עם דף הסבר בעברית והתקנה בהדבקה אחת.

**האתר:** https://ai-shiralon.github.io/claude-skills/

## התקנה מהירה (טרמינל)

```bash
curl -fsSL https://ai-shiralon.github.io/claude-skills/install.sh | bash -s -- copywriting pdf
```

להתקנת **כל** הסקילים:

```bash
curl -fsSL https://ai-shiralon.github.io/claude-skills/install.sh | bash -s -- all
```

הסקריפט לא דורס סקיל קיים באותו שם.

## מבנה הריפו

- `src/` - קוד המקור של הסקילים (כל סקיל עם רישיון משלו)
- `content/` - תוכן דפי ההסבר בעברית, JSON אחד לכל סקיל
- `build/` - בניית האתר הסטטי: `python3 build/build.py`
- `catalog.json` - רשימת הסקילים, הקטגוריות, הקורס והמתנות

## קרדיטים ורישיונות

מנוע האתר מבוסס על [hiyabh/claude-skills](https://github.com/hiyabh/claude-skills) (MIT, ראו LICENSE).
לכל סקיל בתיקיית `src/` רישיון משלו בתיקיית הסקיל: סקילי המסמכים (pdf, docx, pptx, xlsx, skill-creator) של Anthropic ברישיון Apache 2.0, ושאר הסקילים ברישיון MIT של היוצרים שלהם.
