Το πρόγραμμα μεταγλωτίζεται μέσω της MANIFEST.MF που βρίσκεται μέσα στο αρχείο BREACH.jar. Για να εκτελεστεί, λοιπόν, το πρόγραμμα ακολουθείστε τα εξής βήματα: 
1) Κατεβάζετε το εκτελέσιμο αρχείο BREACH.jar,
2) Ανοίγετε το Command Prompt των Windows,
3) cd pathforBREACH.jar (ουσιαστικά κάνετε copy-paste το path στο οποίο βρίσκετε το BREACH.jar), και
4) java -jar BREACH.jar

Οδηγίες χρήσης προγράμματος:
Ως στρατηγός των Αχαιών προσπαθώντας να εισβάλεις στα τείχη της Τροίας και να την κατακτήσεις βρίσκεσαι αντιμέτωπος με πέντε εμπόδια. Για την αντιμετώπιση των εμποδίων αυτών, 
καλείσαι να διαλέξεις ανάμεσα σε διάφορα εργαλεία και στρατούς που έχεις στην διάθεσή σου. Κάθε εργαλείο και στρατός μπορεί να χρησιμοποιηθεί μόνο μια φορά οπότε διάλεξε σοφά!
Τα εργαλεία και τον στρατό που χρησιμοποιούνται από τους Τρώες είναι κρυφά από εσένα και διαλέγονται τυχαία. Εσύ προκειμένου να διαλέξεις την σωστή στρατηγική για να νικήσεις
το εμπόδιο, γνωρίζεις μόνο την πιθανότητα επιλογής της κάθε μίας άμυνας. Στην περίπτωση που χάσεις μία μάχη πρέπει να ξεκινήσεις την εισβολή από την αρχή, δηλαδή από το πρώτο
εμπόδιο.

Τα περιεχόμενα του αποθετηρίου έχουν χωριστεί σε 5 branches: main, Choose, Attack, Defense, Output.Στο attack branch υπάρχουν όλες οι κλάσεις που σχετίζονται με την επίθεση. 
Στο defense branch υπάρχουν όλες οι κλάσεις που σχετίζονται με την παραγωγή πιθανοτήτων για το όπλο που θα χρησιμοποιηθεί στην άμυνα. Το choose branch περιλαμβάνει τις κλάσεις 
οι οποίες ζητάνε από τον παίκτη να διαλέξει τον αρχηγό και τον τύπο εμποδίου. Το output branch περιέχει μόνο την κλάση Output με βάση το όπλο που έχει παραχθεί στην άμυνα και το 
όπλο που έχει επιλέξει ο παίκτης, βγάζει το αποτέλεσμα νίκης ή ήττας. Τέλος, στην main υπάρχουν οι κλάσεις που σχετίζονται με την εκτέλεση του κώδικα. Η playBreach είναι εκείνη 
που περιέχει την main, η Breach εκείνη που συντονίζει τις άλλες κλάσεις ώστε να εκτελεστεί το προγραμμα και η Intro είναι αυτή που περιέχει βασικα στοιχεία, όπως την αναφορά στο
ιστορικό πλαίσιο και τις οδηγίες του παιχνιδιού.
