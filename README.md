# exercise-sql-chinook-joins-and-crud
Ett övningssamling för att öva på joins och CRUD. Chinnok sample database är den som används i detta exempel.

Självklart, här är frågorna utan lösningarna:

---

### Frågor för att öva på `JOIN`s (8 frågor)

1. Hämta alla album tillsammans med deras artistnamn.

2. Hämta alla artister och deras albumtitlar. Om en artist inte har några album, visa `NULL` för albumtiteln.

3. Hämta spårens namn, deras albumtitel och artistnamn.

4. Hämta alla kunder och deras fakturor. Om en kund inte har någon faktura, visa `NULL` för fakturabeloppet.

5. Lista alla genrer och antalet spår som tillhör varje genre.

6. Hämta alla spår från albumet med titeln "Let There Be Rock" och visa spårens namn och albumets titel.

7. Lista alla fakturor och visa kundens namn och fakturabelopp, sorterat efter fakturabelopp i fallande ordning.

8. Hämta alla spår som tillhör genren "Rock" och visa spårens namn, albumets titel och artistens namn.

---

### Frågor för att öva på `INSERT` (2 frågor)

9. Lägg till en ny kund i `Customers`-tabellen med namn "Jane Doe" från Kanada och e-postadressen `janedoe@example.com`.

10. Lägg till ett nytt album i `Albums`-tabellen med titeln "Greatest Hits" och koppla det till en artist med `ArtistId = 1`.

---

### Frågor för att öva på `UPDATE` (3 frågor)

11. Uppdatera e-postadressen för kunden med `CustomerId = 5` till `newemail@example.com`.

12. Uppdatera albumtiteln för albumet med `AlbumId = 10` till "Updated Album Title".

13. Ändra landet till "United States" för alla kunder som för närvarande har landet "USA".

---

### Frågor för att öva på `DELETE` (2 frågor)

14. Ta bort kunden med `CustomerId = 5` från `Customers`-tabellen.

15. Ta bort alla spår som tillhör albumet med `AlbumId = 10`.

---

Dessa frågor ger praktisk övning i att använda `JOIN`-operationer samt att skapa, uppdatera och ta bort data i **Chinook Sample Database**. Lycka till med övningarna!
