# CLAUDE.md, האתר הראשי (daani613-rgb.github.io)
- **מה הריפו עושה:** ההאב הראשי (index.html) והדפים הקלאסיים שמתפרסמים אליו מהמנועים. ההאב קורא
  `preview/<ענף>/status.json`, ונופל ל-payload כשהוא חסר.
- **בדיקות:** אין תיקיית בדיקות. הבדיקה היא הסריקה בחי (research/analysis/glossary_scan.py,
  work/d3check/live_scan.sh).

### מה השתנה ב-22.10
- נדחף: ההאב קורא status.json (‏8fc774e).
- בענף, בלי דחיפה עדיין: התווית "לא עודכן 36+ שעות" (c-hub-stale-2026-10-22).

## סגירה, 22.10.2026 (פרק מתוארך; פקודת הסגירה v2)
- **בדיקות:** כל הבדיקות של כל הריפוז רצות מעותק archive של origin/main, עם רשת חסומה:
  `python3 ~/prediction-engines-work/research/analysis/tests_all_main.py <tag>`. ב-22.10, אחרי הדחיפות: 48 מתוך 48
  עוברות. בדיקה שמשווה ל-git HEAD מדלגת ("SKIP, לא נמדד") כשאין git (CLOSEOUT_TESTS_PREREGISTER.md).
- **מוגן, לקריאה בלבד:** פרמטרי Elo, מתמטיקת הדירוגים, CHAIN, ‏.gitignore, ‏totals/pitcher_adapter.py, מסנני
  השלבים, לוגיקת בחירת A+, כל cron, ‏isOffseason, ‏CALIB, ‏tennis_calibration.py ו-Platt, ‏tennis_stages.py,
  ‏build_predictions.py:58, ‏run_live.py, ‏baseball_daily.py ושערי הנעילה, ומנגנון היומנים הנעולים.
- **workflows:** ‏schedule ו-workflow_dispatch בלבד, ואין טריגר על push. אין ריצה ידנית בלי אישור.
- **ההחלטות שממתינות לשמואל:** ‏research/CLOSEOUT_DECISIONS_2026-10-22.md.
- **מצב הצי:** ‏research/STATE_v18_2026-10-22.md.
