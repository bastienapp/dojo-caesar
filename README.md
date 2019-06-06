## Chiffrement par décalage

En cryptographie, le chiffrement par décalage, aussi connu comme code de César, est une méthode de chiffrement très simple utilisée par Jules César dans ses correspondances secrètes (ce qui explique le nom « chiffre de César »).

Le texte chiffré s'obtient en remplaçant chaque lettre du texte clair original par une lettre à distance fixe, toujours du même côté, dans l'ordre de l'alphabet. Pour les dernières lettres (dans le cas d'un décalage à droite), on reprend au début.

Par exemple avec un décalage de 3 vers la droite, A est remplacé par D, B devient E, et ainsi jusqu'à W qui devient Z, puis X devient A etc.

Ex:
```
    sentence:   rotation:   result:
    "abcd"      1           "bcde"
    "tacos"     3           "wdfrv"
    "zebre"     2           "bgdtg"
```

Rappel des commande junit :

```
javac -cp .:junit-4.12.jar CaesarTest.java
java -cp .:junit-4.12.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore CaesarTest
```
