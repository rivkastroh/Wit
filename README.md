wit – Version Control System Using Click

A simple version control system called wit, similar to Git.
The system allows users to manage file versions, add files for tracking, make commits, and view version history.
All commands are executed via a Command Line Interface (CLI) using the Click library.
This project is implemented using Object-Oriented Programming (OOP) principles.

Commands:

wit init
The wit init command creates a new directory named .wit in the current directory, if it does not already exist.
If the .wit directory already exists, an appropriate error message is displayed.

wit add
The wit add command adds selected files to version tracking.
This means the files will be included in the next commit.

wit commit -m "message"
The wit commit -m "message" command creates a new version in the repository and saves the tracked files with a commit message explaining the changes made.

wit log
The wit log command displays the version history of the system, including the commit hash, date, and commit message for each saved version.

wit status
The wit status command checks whether there are uncommitted changes in the repository (for example, files that were modified but not yet committed).
If such changes exist, an appropriate message is displayed.

wit checkout <commit_id>
The wit checkout <commit_id> command allows the user to revert to a previous version by specifying a commit ID.
After executing this command, the file contents are updated to the selected version.

---

שם הפרויקט: wit - מערכת בקרת גרסה באמצעות קליק
מערכת בקרת גרסאות פשוטה בשם wit, בדומה ל-Git. המערכת מאפשרת למשתמשים לנהל גרסאות קבצים, להוסיף קבצים למעקב, לבצע שינויים ולצפות בהיסטוריית הגרסאות. כל הפקודות באמצעות ממשק שורת פקודה (CLI) באמצעות ספריית קליק.
פרויקט זה מיושם באמצעות עקרונות תכנות מונחה עצמים (OOP).


הפקודות:
1. wit init
הפקודה wit init תיצור תיקיה חדשה בשם .wit בספרייה הנוכחית, אם תיקיה כזו עדיין לא קיימת. אם תיקיית .wit כבר קיימת, תוצג הודעת שגיאה מתאימה.
2. wit add
הפקודה wit add <file> תוסיף קבצים נבחרים למעקב בגרסה. המשמעות היא שהקבצים ייכללו ב-commit הבא.
3. wit commit -m "הודעה"
הפקודה wit commit -m "message" תיצור גרסה חדשה במאגר ותשמור את הקבצים במעקב עם הודעת commit שמסבירה את השינויים שבוצעו.
4. wit log
הפקודה wit log תציג את היסטוריית הגרסאות של המערכת, כולל הודעת commit hash, תאריך והודעת commit עבור כל גרסה שנשמרה.
5. wit status
הפקודה wit status תבדוק אם יש שינויים לא מחויבים במאגר (למשל, קבצים ששונו אך עדיין לא מחויבים). אם קיימים שינויים כאלה, תוצג הודעה מתאימה.
6. wit checkout <commit_id>
הפקודה wit checkout <commit_id> תאפשר למשתמש לחזור לגרסה קודמת על ידי ציון מזהה commit. לאחר ביצוע פקודה זו, תוכן הקבצים יעודכן לגרסה שנבחרה.


