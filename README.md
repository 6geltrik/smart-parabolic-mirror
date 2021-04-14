
## Έξυπνο Παραβολικό Κάτοπτρο

<img src = Photos/IMG_20210326_160604.jpg width = 1000>

Χρησιμοποιώντας καθημερινά υλικά και γνώσεις μαθηματικών, φυσικής,πληροφορικής και άλλες επιστήμες για να φτιάξουμε ένα παραβολικό κάτοπτρο που θα μπορεί να χρησιμοποιεί τον ήλιο με την μέγιστη δυνατή απόδοση ώστε να ζεστάνουμε νερό και να παράγουμε ηλεκτρική ενέργεια.

Υλικά:

1. ARDUINO UNO

2. CNC SHIELD FOR ARDUINO UNO

3. STEPPER MOTOR DRIVER - DRV8825 (X2)

4. STEPPER MOTOR - 42BYGHW804 (X2)

5. PHOTORESISTOR LDR (X4)

6. ΜΠΑΤΑΡΊΑ ΜΟΛΎΒΔΟΥ 12V

7. ΠΛΑΚΈΤΑ ΔΙΆΤΡΗΤΗ

8. ΦΩΤΟΒΟΛΤΑΪΚΉ ΚΥΨΈΛΗ 2W (X3)

9. VOLTAGE REGULATOR L78S12CV - 12V 2A

10. DIODE RECTIFIER 45V 15A

11. ΛΑΜΑΡΙΝΑ ΑΛΟΥΜΙΝΙΟΥ

12. ΧΑΛΚΙΝΟ ΣΩΛΗΝΑ

13. ΚΑΔΡΟΝΑΚΙΑ

14. ΜΟΡΙΟΣΑΝΙΔΑ

15. ΚΑΛΩΔΙΑ

16. ΞΥΛΟΒΙΔΕΣ

17. ΙΜΑΝΤΑ ΓΙΑ ΤΑ ΜΟΤΕΡ

18.DIODE RECTIFIER 45V 15A (TO220)

19.VOLTAGE REGULATOR L78S12CV - 12V 2A

20.VOLTAGE REGULATOR L7809CV - 9V 1.5A

21.ΜΠΑΤΑΡΊΑ ΜΟΛΎΒΔΟΥ 12V 1.3AH

22.ΠΛΑΚΈΤΑ ΔΙΆΤΡΗΤΗ 30X70MM - ΔΙΠΛΉΣ ΌΨΗΣ

23.ΦΩΤΟΒΟΛΤΑΪΚΉ ΚΥΨΈΛΗ 2W 136X110MM

24.ΨΎΚΤΡΑ ΤO-220 ΜΕΣΑΊΑ 25MM

25.ΚΌΛΑ ΣΙΛΙΚΌΝΗΣ

Λογισμικό
Κατασκευή - Λειτουργία
1ο στάδιο: Κατασκευή Παραβολικού Κατόπτρου
Αρχικά σχεδιάσαμε την παραβολή χρησιμοποιώντας GeoGebra σε Α4 και κόψαμε το ξύλο στο σχήμα της παραβολής.

Έπειτα συνδέσαμε τον άξονα για στήριξη και βιδώσαμε την ανακλαστική επιφάνεια στα ξύλα.

Στην συνέχεια κατασκευάζουμε τους δύο άξονες περιστροφής και την τροχαλία περιστροφής και τα συνδέουμε όλα στην βάση.

Μετά συνδέσαμε τα βηματικά μοτέρ για να μπορεί το κάτοπτρο να περιστρέφετε.

<img src = Photos/62.jpg width = 500>

Συνδέσαμε τους αισθητήρες φωτός στο Arduino.

<img src = Photos/59.jpg width = 500>

Τέλος προγραμματίζουμε το Arduino ώστε να δέχεται τα σήματα των αισθητήρων και να κινεί αναλόγως το κάτοπτρο.

Το πραγραμμα ειναι εδω: https://github.com/6geltrik/smart-parabolic-mirror/blob/master/Program

2ο στάδιο: 
Παραγωγή ρεύματος και αυτονομίας

<img src = Photos/26.jpg width = 500>

Αρχικά κολλήσαμε 2 φωτοβολταϊκά πάνελ σε σειρά πάνω στο πλαίσιο του κατόπτρου ώστε να έχουμε συνολικά περισσότερα των 12V. Μετά κατασκευάσαμε την πλακέτα ηλεκτρονικών εξαρτημάτων για φόρτιση της μπαταρίας και την τροφοδοσία του arduino.

<img src = Photos/IMG_20210314_115410.jpg width = 500>
