#Exercise 1 in advanced cpp course

First we set the number of players and the number of cards for each one by the user input.

Then the program recieves the players name, and randomly draws cards. Also it draws a random start card, and then the game starts.

In example:

![](https://user-images.githubusercontent.com/33619352/58573803-2a91d500-8247-11e9-8d45-9fe533da0a05.png)


דוגמא:
מהלך המשחק:
התוכנית תעבור על השחקנים לפי הסדר )אין חשיבות מי השחקן הראשון(, בהגיע תורו של כל שחקן על התוכנית להציג שורה כזו:
כעת ישנן שלוש אפשרויות:
1 .המשתמש בחר בחירה חוקית )אותו צבע, או אותה צורה( – במקרה כזה הקלף הנוכחי מוחלף לקלף הנבחר ומתקדם התור )בהתאם
לקלף שנבחר, ראה להלן(
2 .המשתמש בחר בחירה לא חוקית של קלף – תופיע שורת שגיאה באופן הבא, והתוכנית תחכה לקלט אחר:
3 .המשתמש בחר 0 ,או כל מספר מחוץ לטווח – השחקן הנוכחי מקבל קלף חדש מהקופה, והתור מתקדם בכל מקרה ב-1.
התקדמות התור באפשרות 1 נעשית בהתאם לחוקי המשחק:
 עבור קלף + - אין התקדמות תור
 עבור קלף מחליף כיוון – שינוי כיוון המשחק, התקדמות ב -1
 עבור קלף עצור – התקדמות ב-2( דילוג על השחק הבא(
 עבור כל קלף אחר – התקדמות ב-1
המנצח הוא השחקן שסיים את הקלפים ראשון. לאחר מכן מודפס: בהתאם לשם השחקן והתכנית מסתיימת

