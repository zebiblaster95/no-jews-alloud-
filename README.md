# no-jews-alloud-
dit is niet voor joden als ik zie dat je jood bent verkracht ik je 



-----------------------------
>>>>>>>>>>>>>>>>>>>        https://discord.gg/Wf7AXVXGHM    <<<<<<<<<<<<<<<<<<<<<<<<<<<<<



discord link ^^^^^^^

-----------------------------



hier onder staan de sql query's 


1. Query 1: Laat door middel van een query alle velden van tabel processen zien.
Antwoord: SELEsCT * from processen;

2. Query 2: Laat door middel van een query de velden Name en CPU van tabel processen zien.
Antwoord: SELECT Name, CPU FROM processen;

3. Query 3: Laat door middel van een query de velden Name en CPU zien uit tabel processen waarbij CPU een hogere waarde heeft dan 100.
Antwoord: SELECT Name, CPU FROM processen WHERE CPU > 100;

4. Query 4: Laat door middel van een query de velden Name uit tabel processen waar geen procesnamen in staan die in de tabel Whitelist te vinden zijn.
Antwoord: SELECT Name FROM processen
WHERE Name NOT IN (SELECT Name FROM Whitelist);

5. Query 5: Doe een SQL-insert van procesnaam Goodproces in tabel Whitelist.
Antwoord: INSERT INTO Whitelist (Name) VALUES ('Goodproces');

6. Query 6: Laat via een query de velden Name en CPU zien waarbij CPU meer is dan het gemiddelde CPU-verbruik van alle processen ( waarbij het gemiddelde CPU-verbruik tijdens de query berekend moet worden).
Antwoord: SELECT Name, CPU FROM processen
WHERE CPU > (SELECT AVG(CPU) FROM processen);
------------------------------
