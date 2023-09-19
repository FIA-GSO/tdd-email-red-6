# Email Validierung 
 Einer Ihrer Kollegen hat eine Python-Funktion `is_valid_email(email:str)` zur Überprüfung von Email-Adressen geschrieben. Die Funktion nutzt Regular Expressions (kurz RegEx), um Muster in String zu finden. RegEx sind ein mächtiges Werkzeug, können aber nur schwer gewartet werden sie werden schnell zu [code-smells "stinkendem Code"](https://luzkan.github.io/smells/complicated-regex-expression).

 Immerhin hat Ihr Kollege daran gedacht, einige Testfälle zu definieren, um die Fähigkeiten seiner Funktion zu überprüfen.


## Ziele :dart:
**Primär:**
- Die Begriffe Code-Smell und Refactoring sind verinnerlicht. Für Code-Smells können mindestens drei Beispiele genannt werden, der Zusammenhang zwischen Unit-Tests und Refactoring kann erläutert werden.
- Die Funktion soll "möglichst viele" [gültige und ungültige Email-Adressen](https://www.tumblr.com/codefool/15288874550/list-of-valid-and-invalid-email-addresses) korrekt erkennen.

**Sekundär:**
- Es soll eine weitere Funktion `is_valid_password` entstehen, die überprüft, ob ein übergebenes Passwort den [Anforderungen des BSI](https://www.bsi.bund.de/DE/Themen/Verbraucherinnen-und-Verbraucher/Informationen-und-Empfehlungen/Cyber-Sicherheitsempfehlungen/Accountschutz/Sichere-Passwoerter-erstellen/sichere-passwoerter-erstellen_node.html) entspricht.

## Aufgabenstellung
**Wiederholen** Sie die folgenden Phasen von Test-Driven-Developement so lange, bis die Ziele möglichst erreicht sind.
 1. Betreiben Sie Refactoring! Überarbeiten Sie die Funktion `is_valid_email(email:str)` so, dass die Funktionalität erhalten bleibt, aber der Code ~~besser~~ ~~lesbarer~~ frei von Code-Smells ist.
 2. Definieren Sie die Testfälle in `test_email_validation.py` um eine weitere gültige oder ungültige E-Mail-Adresse.
 3. Implementieren Sie eine Erweiterung der Funktion `is_valid_email(email:str)` so, dass der neue Testfall erfolgreich ist.

## Nützliche Links
- [Parametrisierte Tests mit Pytest](https://docs.pytest.org/en/7.3.x/how-to/parametrize.html#pytest-mark-parametrize)
- [Docstrings in Python](https://www.programiz.com/python-programming/docstrings)
- Sollten Sie sich in Ihrer Freizeit für Emails interessieren, empfehle ich dieses [Video zum Thema ](https://www.youtube.com/watch?v=mrGfahzt-4Q)

