## Grundlagen

### Installation

### MongoShell
starten über den Befehl **mongosh**

1. Alle Datenbanken anzeigen
   ```mongosh
   show dbs
   ```

2. Aktualle Datenbank anzeigen
   ```mongosh
   show dbs
   ```

3. Datenbank verwenden/anlegen
   wird erst angezeigt, wenn auch Daten darin gespeichert worden sind
   ```mongosh
   use tutorial
   ```

4. Datenbank löschen
   es werden alle Daten in der Datenbank gelöscht (Vorsicht: keine Sicherheitsabfrage);
   man sieht auch weiter den Datenbankprompt --> leere Datenbank
   ```mongosh
   db.dropDatabase('tutorial')
   ```

5. Neue Collection anlegen
   ```mongosh
  db.createCollection('products')
   ```

6. Alle Collections anzeigen


## Links
- [https://www.mongodb.com/](https://www.mongodb.com/)
- [https://www.youtube.com/watch?v=jpTNn4zkMKY](https://www.youtube.com/watch?v=jpTNn4zkMKY)
- [https://github.com/ProgrammierenM/mongodb-cheat-sheet](https://github.com/ProgrammierenM/mongodb-cheat-sheet)
- [https://www.youtube.com/watch?v=OyktS0ktXYw&list=PLEYpvDF6qy8ZTUjMcg4WOUYMxQZDpRnBt&index=2](https://www.youtube.com/watch?v=OyktS0ktXYw&list=PLEYpvDF6qy8ZTUjMcg4WOUYMxQZDpRnBt&index=2)
