# Auth_Authz_Failures

## Teil 1

### Beschreibung
In meinem Datensatz geht es um Authentifizierung und Authorizationsversuche. Zu jedem Versuch stehen viele Informationen wie z.B. der Benutzername, Gerät, Betriebssystem, Anzahl Versuche, Authentifizierungsart, Errorcode, Grund für den Fehlschlag und so weiter. Alle Felder sind verständlich beschriftet ausser session_duration. Dort ist nicht ganz klar, welche Zeiteinheit verwendet wird. Ich nehme aber auf Grund der hohen Zahlen an, dass es sich um Milisekunden handelt.

### Datenschutzrichtlinien
Ich habe die Spalten zu den Benutzernamen und IP-Adressen gelöscht, da man sonst auf genaue Personen schliessen könnte. Man hätte sie auch anonymisieren können, aber da diese Spalten für die Anderen Spalten nicht relevant sind, war es einfacher und weniger Zeitaufwändig, sie ganz zu löschen. Ansonsten entsprechen alle Daten den Datenschutzrichtlinien.
