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
| TC005 | Groß-/Kleinschreibung testen (Standard_User) | Login sollte fehlschlagen |Login fehlschlagen | Bestanden |

## Screenshots

### TC001 - Erfolgreicher Login
<img width="1852" height="964" alt="image" src="https://github.com/user-attachments/assets/a1b08dfe-b7e5-42cd-bc7b-ab05e8cad6cd" />

### TC002 - Fehlermeldung Erschien
<img width="1852" height="964" alt="tc002-fehlermeldung-erscheint" src="https://github.com/user-attachments/assets/ee6c5582-4a6f-40cf-b4a7-d6d3b0937cb1" />

### TC003 - Warnmeldung Erschien
<img width="1892" height="1008" alt="tc003-warnmeldung-erscheint" src="https://github.com/user-attachments/assets/911e247c-6d2d-40f0-b35a-04409675e311" />

### TC004 - Sperr-Fehler Erschien
<img width="1905" height="979" alt="tc004-sperr-fehler-ershient" src="https://github.com/user-attachments/assets/c0f14acf-510a-4f38-a9e6-3a71fc7487c5" />

### TC005 - Login Fehlschlagen
<img width="1892" height="910" alt="tc005-login-feglschlagen" src="https://github.com/user-attachments/assets/e8585092-5766-4a41-aa31-27bdee54e665" />

## Gefundene Defekte
Keine Defekte gefunden.

## Verwendete Tools
- Manuelles Testen (Browser)
- GitHub (Dokumentation)

## Erkenntnisse
Kurze Notiz darüber, was du aus diesem Test gelernt hast (z.B. Unterschied zwischen positiven und negativen Testfällen, Bedeutung von Edge Cases usw.)
