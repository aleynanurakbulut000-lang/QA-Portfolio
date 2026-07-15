# QA-Portfolio
Software testing practice projects

# Sauce Demo - Login Testing

## Ziel
Manuelles Testen der Login-Funktion der Website saucedemo.com.

## Testszenarien

| Test ID | Schritte | Erwartetes Ergebnis | Tatsächliches Ergebnis | Status |
|---------|----------|----------------------|--------------------------|--------|
| TC001 | Richtigen Benutzernamen/Passwort eingeben (standard_user / secret_sauce) | Login erfolgreich | Login erfolgreich | Bestanden |
| TC002 | Falsches Passwort eingeben | Fehlermeldung erscheint | Fehlermeldung erschien | Bestanden |
| TC003 | Felder leer lassen | Warnmeldung erscheint | Warnmeldung erschien | Bestanden |
| TC004 | Mit locked_out_user einloggen | Sperr-Fehler erscheint | Sperr-Fehler erschien | Bestanden |
| TC005 | Groß-/Kleinschreibung testen (Standard_User) | Login sollte fehlschlagen | ... | ... |

## Screenshots

### TC001 - Erfolgreicher Login



## Gefundene Defekte
Keine Defekte gefunden.

## Verwendete Tools
- Manuelles Testen (Browser)
- GitHub (Dokumentation)

## Erkenntnisse
Kurze Notiz darüber, was du aus diesem Test gelernt hast (z.B. Unterschied zwischen positiven und negativen Testfällen, Bedeutung von Edge Cases usw.)
