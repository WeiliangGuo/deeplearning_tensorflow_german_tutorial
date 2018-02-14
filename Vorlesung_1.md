### Grundlegende Konzepte
* Was ist maschinelles Lernen?
    * Einschränkungen der expliziten Programmierung
      * Spamfilter: viele Regeln
      * Selbstfahrendes Kraftfahrzeug: zu viele Regeln
    * Maschinelles Lernen: "Studienrichtung, die Computern die Lernfähigkeit gibt, ohne explizit programmiert zu werden" Arthur Samuel (1959)
      
* Was ist Lernen?
  * Überwachtes Lernen: Lernen mit gelabelten Beispielen - Trainingsset
    * Ein Beispiel-Trainingsset für vier visuelle Kategorien:
      ![alt text](https://github.com/WeiliangGuo/deeplearning_tensorflow_german_tutorial/blob/master/pics/4-V-Kategorien.jpg)
      http://cs231n.github.io/classification/
    * Überwachtes Lernen ist die üblichste Problemart beim maschinellen Lernen.
      * Bild-Labeling: Lernen von getaggten Bildern
      * E-Mail-Spam-Filter: Lernen von gelabelte (Spam oder Ham)E-Mails
      * Vorhersage des Prüfungsergebnisses: Lernen aus dem vorherigen Prüfungsergebnis und der Zeit, die Sie damit verbracht haben.
    * Arten des überwachten Lernens:
      * Vorhersage der Punktzahl für die Abschlussprüfung, die auf der aufgewendeten Zeit basiert.
        * Regression
        
        ![alt text](https://github.com/WeiliangGuo/deeplearning_tensorflow_german_tutorial/blob/master/pics/Examensnote.jpg)
        
      * Bestanden/Nicht bestanden basierend auf der aufgewendeten Zeit.
        * Binäre Klassifikation
        
        ![alt text](https://github.com/WeiliangGuo/deeplearning_tensorflow_german_tutorial/blob/master/pics/Bestanden%2CNIcht-bestanden.jpg)
    * Auf der aufgewendeten Zeit basierende Briefgrad (A, B, C, C, E und F)   
      * Multi-Label-Klassifizierung
      
        ![alt text](https://github.com/WeiliangGuo/deeplearning_tensorflow_german_tutorial/blob/master/pics/Stunden%2CGrad.jpg)
  * Unüberwachtes Lernen: ungelabelte Daten
    * Google News Gruppierung
    * Wort-Clustering
    
* Was ist Regression?
*  Was ist Klassifizierung?
