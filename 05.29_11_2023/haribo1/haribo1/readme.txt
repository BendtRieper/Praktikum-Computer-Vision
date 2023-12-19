Die Bilder liegen diesmal ganz normal als png-Bilder in den beiden Ordnern vor und können wie üblich eingelesen werden. 

Es empfiehlt sich die Nutzung von glob.glob(), um die Pfade zu allen Bildern eines Ordners ohen großen Aufwand zu erhalten.

Aus den Bildnamen lässt sich das Label (baeren, konfekt, vampire) extrahieren (String-Methoden split oder find). Es ist sinnvoll, diese auf jeweils eine Zahl (0,1,2) abzubilden.

Insgesamt gibt es 13 Trainings- und 4 Validierungsbilder je Klasse.
