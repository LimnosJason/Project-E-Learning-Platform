# ProjectEL
Η εργασία μας στο μάθημα της Ηλεκτρονικής μάθησης
# Οδηγίες χρήσης git
Αρχικά φτιάχνουμε ένα τοπικό αντίγραφο του repository στον υπολογιστή μας. Αυτό σε όρους git λέγεται clone και μέσα από το intelliJ το βρίσκουμε ως:<br>
&emsp;>**get from VCS**(κουμπάκι πάνω δεξιά όταν δεν υπάρχει ήδη ανοιχτό project)<br>
&emsp;>συνδεόμαστε με τον λογαριασμό μας του GitHub<br>
&emsp;>επιλέγουμε το project που μας ενδιαφέρει<br>
&emsp;>πατάμε **clone**<br><br>
Παρατηρούμε ανοίγει ένα project, το οποίο δεν έχει glassfish ακόμα, οπότε:<br>
&emsp;>πατάμε **edit configurations** και<br>
&emsp;>επιλέγουμε **glassfish 6.2.5**<br>
&emsp;>διαλέγουμε ως server domain->**domain1** και εάν βγάλει warning για debug settings πατάμε το **fix** και διαλέγουμε μια από τις επιλογές.<br><br>
Εκτελούμε τις αλλαγές που επιθυμούμε και για να ανέβουν στο git πατάμε από αριστερά το πλαϊνό κουμπί που λέει **commit**<br>
&emsp;>επιλέγουμε ποια από τα changes θέλουμε να γίνουν commit<br>
&emsp;>γράφουμε ένα μήνυμα πάνω στο τι αλλαγές κάνουμε commit<br>
&emsp;>πατάμε το κουμπί<br><br>
Μετά για να συγχρονιστεί το local με το remote(github):<br>
&emsp;>πατάμε την επιλογή από το menu που λέει git<br>
&emsp;>πατάμε **push** και διαλέγουμε τι θα κάνουμε push<br>
    
<br>
Για να κάνουμε **pull** πατάμε:<br>
&emsp;>**fetch** από την επιλογή git στο menu πάνω(μπορούμε επίσης να τις δούμε από το git κάτω δεξιά, όταν το ανοίγουμε το σύμβολο του fetch είναι μπλε αν υπάρχουν, το πατάμε κ εμφανίζονται)<br>
&emsp;>για να δούμε τις αλλαγές που έχουν γίνει από τους άλλους πατάμε κάτω δεξιά το git και μας εμφανίζονται <br>
&emsp;>από εκεί μπορούμε να συγκρίνουμε τις αλλαγές των συναδέλφων<br>
&emsp;>εάν εγκρίνουμε πατάμε pull από την επιλογή git στο menu πάνω<br><br>
## Πώς κάνω μια αλλαγή;
2 τρόποι 

# Εισαγωγή mariadb
Πάμε στο project μας, πατάμε:<br>
&emsp;>**file>project structure>libraries** και στο αριστερό τμήμα πατάμε το **'+'**<br>
&emsp;>διαλέγουμε **from maven** και γράφουμε στο πλαίσιο **org.mariadb.jdbc**<br>
&emsp;>από τις διαθέσιμες επιλογές παίρνουμε την **org.mariadb.jdbc:mariadb-java-client:2.7.0**<br>
Πατάμε **Apply** και κλείνουμε την καρτέλα.<br>
Ξανανοίγουμε τα **file>project structure** και αυτή τη φορά διαλέγουμε το **artifacts**<br>
Επιλέγουμε το projectname:**war exploded** και κοιτάμε αν δεξιά, κάτω από το **available elements** υπάρχει η mariadb, εάν δεν υπάρχει τελειώνει η διαδικασία, εάν υπάρχει, τότε πατάμε δεξί κλικ πάνω της και επιλέγουμε put into /WEB-INF


# Για μάθημα ηλεκτρονικής μάθησης
login/logout->στην ιδια μπαρα δεξια<br>
Επικοινωνία κάτω-κάτω<br>

<b>Μαθηματικά Ε Δημοτικού<br></b>
<b>------------------------------<br></b>
ΥΛΗ: 1.διαιρεση στους φυσικούς<br>
&emsp;2.πολλαπλάσισα και διαιρέτες<br>
&emsp;3.κριτήρια διαιρετότητας<br>
&emsp;4.πολλαπλασιασμός στους φυσικούς<br>
&emsp;5.πρόσθεση αφαίρεση<br>

Αρχική<br>
login<br>
&emsp;username<br>
&emsp;password<br>
new account:<br>
&emsp;όνομα<br>
&emsp;username<br>
&emsp;password<br>
&emsp;//email<br>
κεφαλαια(θεωρία-ασκησεις-ξεχωριστό κουιζ-σκετο σκρολ(ασκ/θεωρια μαζι, κουιζ κατω κατω με λινκ που παει σε αλλο ταμπ)<br>
στατιστικά(μεσο ορο(καλυτερος), ιστορικό σε καθε μαθημα, badges)<br>
ουλτιμειτ κουιζ<br>

# Pom.xml
Εάν μας εμφανίζεται πως δεν μπορούμε να κανουμε edit το project γιατί είναι read-only, πατάμε δεξί κλικ στο pom.xml και διαλέγουμε maven->reload project ή εάν μας εμφανιστεί κάτω δεξιά ειδοποίηση για load maven, πατάμε αυτήν την επιλογή.

# Glassfish
Εάν μας βγάλει πως η πόρτα του glassfish χρησιμοποιείται ήδη, τότε ανοίγουμε τερματικό, πάμε στο path που είναι αποθηκευμένο το bin του συγκεκριμένου glassfish και γράφουμε στο τερματικό το ακόλουθο:<br>
asadmin stop-domain
