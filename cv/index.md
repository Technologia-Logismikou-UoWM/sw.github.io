## Ατομικό βιογραφικό που ανήκει στο webring της ομάδας σας

* Σε αυτήν την εργασία θα δημιουργήσετε μια ιστοσελίδα για το βιογραφικό σας σε διαφορετικές μορφές αρχείων οι οποίες θα είναι προσβάσιμες με την υπηρεσία [Github Pages](https://pages.github.com/) ή [Netlify](https://www.netlify.com) σε ένα νέο αποθετηρίο στον λογαριασμό σας. Το βιογραφικό σας θα πρέπει να δημιουργείται αυτόματα από αρχείο δεδομένων μορφής [YAML](https://learnxinyminutes.com/docs/yaml/) με τα στοιχεία σας, σε μορφή ιστοσελίδας και σε μορφή PDF. Το βιογραφικό μπορεί να είναι σε όποιο στυλ βιογραφικού θέλετε, συνήθως βολεύει να διαλέξετε ένα έτοιμο στυλ και να κάνετε αλλαγές.

* Όπως με όλα τα παραδοτέα θα πρεπει να στείλετε την ατομική σας πρόοδο με έναν σύνδεσμο προς το (αρχικό) βιογραφικό σας μέχρι την Κυριακή. Ο σύνδεσμος (netlify, GitHub pages) θα παραμείνει ίδιος, ενώ παράλληλα εσείς μπορείτε να ενημερώνετε τα στοιχεία-στυλ του βιογραφικού σας τις επόμενες εβδομάδες.

Ο στόχος είναι από το ίδιο αρχείο δεδομένων να παράγεται: 

1. Παραδοτέο Α: μια ιστοσελίδα βιογραφικού με χρήση του συστήματος [Jekyll](https://jekyllrb.com/). Η ιστοσελίδα βιογραφικού θα πρέπει να ανήκει στο webring της [ομάδας σας](https://courses-ionio.github.io/help/team/). Αυτό σημαίνει ότι εκτός από τη προετοιμασία της σελίδας του βιογραφικού, θα πρέπει να την προσθέσετε και στο σχετικό webring. Συνήθως αυτό γίνεται με ένα αίτημα ενσωμάτωσης και με επεξεργασία της σελίδας σας ώστε να περιέχει τον κώδικα που ορίζει το αντίστοιχο webring. Όπως το στυλ του βιογραφικού, έτσι και η επιλογή του webring είναι δικιά σας ευθύνη σε συνεργασία με την ομάδα σας. Ενδεικτικό λογισμικό για webring: [1 χρειάζεται ενημέρωση η έκδοση npm](https://github.com/maxboeck/webring), [2](https://github.com/XXIIVV/webring).  Ένα webring δεν είναι απλά λίστα, είναι **κυρίως** η κοινή πλοήγηση που εμφανίζεται στις σελίδες των μελών. Η κοινή πλοήγηση μπορεί να είναι απλά ένας σύνδεσμος προς το κεντρικό, ή καλύτερα να υπάρχουν επιλογές (προηγούμενο, επόμενο, τυχαίο). 

2. Παραδοτέο Β: Ενα αρχείο PDF για εκτύπωση σε σελίδα Α4 το οποίο παράγεται με τα εργαλεία pandoc και [latex](https://www.latex-project.org/) τοπικά στον υπολογιστή σας ([παράδειγμα χωρίς jekyll](https://github.com/plain-plain-text/simple-cv)), καθώς και αυτόματη τοποθέτηση [παράδειγμα1]([https://www.gshakhn.com/2016/06/30/on-using-continuous-deployment-for-a-resume.html](https://www.kevinlaw.info/blog/2016-02-28-continuous-delivery-resume/) του στην ιστοσελίδα του βιογραφικού με Continuous Integration [0](https://circleci.com/) [1](https://github.com/PHPirates/travis-ci-latex-pdf), [2](https://github.com/prewriter/LaTeX-Travis-Pages), ή με Github Action, ή με [Netlify CI](https://www.netlify.com/products/build/), κάθε φορά που υπάρχει αλλαγή στο αρχείο δεδομένων YAML. Ο σκοπός αυτού του παραδοτέου είναι κυρίως η εξάσκηση στις διαδικασίες λογισμικού, όπου τα ίδια πηγαία αρχεία κώδικα χρησιμοποιούνται για διαφορετικά αποτελέσματα, π.χ, διαφορετικές πλατφόρμες, τεκμηρίωση, κτλ.

Για την βαθμολόγηση αρκεί να βάλετε στην αναφορά-παραδοτέο ένα λινκ προς την νέα ιστοσελίδα και το αποθετήριο με το βιογραφικό σας, ώστε να αξιολογηθεί ο βαθμός ολοκλήρωσης στα ζητούμενα. **Δεν είναι απαραίτητο να γίνει όλη η εργασία με γραμμή εντολών, αλλά αυτό εκτιμάται θετικά για την άριστη βαθμολόγηση.** Για την άριστη βαθμολόγηση:
Α) θα αξιολογηθούν οι αλλαγές που έγιναν στην μορφοποίηση-στυλ, δλδ, ο βαθμός θα είναι 0.5 αν απλά γίνει συμπλήρωση βιογραφικού.
Β) η δημιουργία να γίνεται μόνο με την γραμμή εντολών (pandoc+latex) και όχι με κάποια γραφική ή δικτυακή εφαρμογή (για την τεκμηρίωση θα πρέπει να βάλετε στην τελική αναφορά μια [εγγραφή του τερματικού](https://asciinema.org/) στο οποίο να φαίνεται η ροη εργασίας από το αρχικό αρχείο δεδομένων, μέχρι το τελικό αποτέλεσμα), το κεντρικό αρχείο δεδομένων να έχει τυποποιημένη οργάνωση της πληροφορίας ώστε να είναι χρήσιμο και σε άλλους, και θα πρέπει η οργάνωση-μορφοποίηση της ιστοσελίδας να ταιριάζει όσο γίνεται περισσότερο με αυτήν του αρχείου προς εκτύπωση.

## Σχετικά μορφότυπα και ροές εργασίας για την κατασκευή βιογραφικών

[0](https://github.com/mrzool/cv-boilerplate), [1](https://github.com/sharu725/online-cv), [2](https://github.com/sproogen/modern-resume-theme), [3](https://github.com/ellekasai/resumecards), [4](https://github.com/plain-plain-text/simple-cv), [5](https://github.com/jglovier/resume-template), [6](https://github.com/blmoore/md-cv), [7](https://github.com/elipapa/markdown-cv), [8](https://jsonresume.org/), [9](https://github.com/bamos/cv), [10](https://github.com/Stavrospanakakis/jekyll-cv), [11](https://github.com/hydecorp/hydejack)

---
* Σε μια πρώτη ανάγνωση, η εργασία αυτή σας βοηθάει να δημιουργήσετε ένα βιογραφικό σε μια δική σας περιοχή πέρα από τις εμπορικές και κυρίως να δημιουργήσετε ομάδες με κοινά ενδιαφέροντα μέσω του webring. Αυτά, αν και είναι πολύ σημαντικά, είναι απλά πλευρικά οφέλη αυτής της εργασίας. Ο βασικός στόχος της εργασίας είναι μια φιλική εισαγωγή στην τεχνολογία λογισμικού μέσα από την κατασκευή μιας ιστοσελίδας. Η εργασία μπορεί να ολοκληρωθεί και χωρίς γνώσεις προγραμματισμού, αλλά θα έχει προσφέρει μια αρχική έκθεση στα συστήματα ελέγχου εκδόσεων πηγαίου κώδικα (VCS), καθώς και στα συστήμα συνεχούς ολοκλήρωσης (CI-CD).

* Επίσης, η εργασία αυτή προσφέρει με όσο γίνεται πιο εισαγωγικό και εύκολο (καθώς δεν περιέχει submodules) τρόπο γνώσεις και δεξιότητες που είναι απαραίτητες για τις άλλες εργασίες του μαθήματος. Για παράδειγμα, η επεξεργασία απλών αρχείων δεδομένων στο γκιτχαμπ είναι απαραίτητη για την αποστολή του 1ου εύκολου παραδοτέου στην εργασία ανάπτυξης. Ακόμη, το σύστημα της ιστοσελίδας στα περισσότερα από τα παραπάνω υποδείγματα βιογραφικού βασίζεται στην βιβλιοθήκη jekyll την οποία χρησιμοποιούμε σε κάποιες εργασίες ανάπτυξης καθώς και στην ιστοσελίδα του βιβλίου. Τέλος, αν και η άσκηση πραγματοποιείται κυρίως σε ένα δικό σας αποθετήριο, απαιτεί και ένα αίτημα ενσωμάτωσης προς το webring της ομάδας, οπότε με αυτόν τον τρόπο έ

* Επίσης, η εργασία αυτή προσφέρει με όσο γίνεται πιο εισαγωγικό και εύκολο (καθώς δεν περιέχει submodules) τρόπο γνώσεις και δεξιότητες που είναι απαραίτητες για τις άλλες εργασίες του μαθήματος. Για παράδειγμα, η επεξεργασία απλών αρχείων δεδομένων στο γκιτχαμπ είναι απαραίτητη για την αποστολή του 1ου εύκολου παραδοτέου στην εργασία ανάπτυξης. Ακόμη, το σύστημα της ιστοσελίδας στα περισσότερα από τα παραπάνω υποδείγματα βιογραφικού βασίζεται στην βιβλιοθήκη jekyll την οποία χρησιμοποιούμε σε κάποιες εργασίες ανάπτυξης καθώς και στην ιστοσελίδα του βιβλίου. Τέλος, αν και η άσκηση πραγματοποιείται κυρίως σε ένα δικό σας αποθετήριο, απαιτεί και ένα απλό αίτημα ενσωμάτωσης προς το webring της ομάδας, οπότε με αυτόν τον τρόπο γίνεται και μια πρώτη εκπαίδευση σε αυτήν την δεξιότητα που είναι αναγκαία για τα επόμενα παραδοτέα.