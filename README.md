# Grouping-Images
Grouping Images with transfer learning and VGG16 model

Οδηγίες Εγκατάστασης:

- Εγκατάσταση Anaconda
- Εγκατάσταση Jupyter (Συνήθως είναι ήδη εγκατεστημένο με Anaconda)
- Εγκατάσταση Microsoft Visual C++ Redistributable (για Visual Studio 2015, 2017, 2019)
- Δημιουργία Virtual Environment 
    Από την εφαρμογή Anaconda ή από Anaconda Prompt 
    με την εντολή "conda -n (name) pip python=3.7" στην θέση name 
    βάζουμε το όνομα που θέλουμε να έχει το Virtual Environment.
- Εγκατάσταση Πακέτων (Keras και Tensorflow) 
    Από την εφαρμογή Anaconda επιλέγουμε πρώτα "Environments" μετά το 
    όνομα του virtual environment που χρησιμοποιούμε και ψάχνουμε τα πακέτα 
    που θέλουμε να εγκαταστήσουμε (Keras και Tensorflow).
    Άλλος τρόπος είναι από Anaconda Prompt με τις εντολές, πρώτα 
    "conda activate (name)" με "(name)" το όνομα του virtual environment.
    Μετά βάζουμε τις εντολές "pip install --upgrade tensorflow" και "pip install keras".
    
Οδηγίες Χρήσης:
    
Στο πρόγραμμα υπάρχουν 4 βασικά κουμπιά:
- Grouping Images: Είναι το αρχικό μενού
- Image for Sorting: Είναι για να τοποθετηθούν οι εικόνες για να ομαδοποιηθούν.
- Models: Βρίσκονται όλα τα διαθέσιμα μοντέλα και το κουμπι "Train new model" για την δημιουργία νέου μοντέλου.
          Επιλέγοντας κάποιο από τα μοντέλα εμφανίζει πληροφορίες για αυτά και 2 κουμπια, 
          (retrain για επανεκπαίδευση του μοντέλου και delete για διαγραφή) 
- Sorting: Σε αυτό το σημείο εμφανίζονται τα διαθέσιμα μοντέλα στα οποία ο χρήστης μπορεί να επιλέξει
           για να ομαδοποιήσει με το μοντέλο τις εικόνες που έχει στο Image for Sorting.
