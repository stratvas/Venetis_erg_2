## README (Ελληνική Έκδοση)

# Ευρετηριοποίηση Συμβολοσειρών και Μηχανή Αναζήτησης με AVL Tree

### Περιγραφή

Το έργο υλοποιεί ένα αποδοτικό σύστημα ευρετηριοποίησης συμβολοσειρών και αναζήτησης σε C++, χρησιμοποιώντας ένα αυτοεξισορροπούμενο δυαδικό δέντρο αναζήτησης AVL. Αναπτύχθηκε στο πλαίσιο του μαθήματος Δομές Δεδομένων και υποστηρίζει εισαγωγή, διαγραφή και αναζήτηση συμβολοσειρών, καθώς και αναζητήσεις προθεμάτων με χρήση χαρακτήρων wildcard.

Η υλοποίηση διατηρεί την ισορροπία του δέντρου μέσω συντελεστών ισορροπίας και αυτόματων περιστροφών, χωρίς αποθήκευση του ύψους των κόμβων, εξασφαλίζοντας αποδοτική εκτέλεση των βασικών λειτουργιών.

### Βασικές Λειτουργίες

- Αυτοεξισορροπούμενο AVL Tree με περιστροφές LL, RR, LR και RL.
- Δυναμική εισαγωγή και διαγραφή συμβολοσειρών.
- Βελτιστοποιημένη σύγκριση συμβολοσειρών με τεχνική skip-match.
- Αναζήτηση προθεμάτων με υποστήριξη wildcard (`*`).
- Αποτελεσματική διαχείριση δυναμικής μνήμης και αποφυγή memory leaks.
- Ανάλυση χρονικής πολυπλοκότητας με τη σημειογραφία Big-O.

### Τεχνολογίες

C++, AVL Trees, Δυαδικά Δέντρα Αναζήτησης, Αναδρομή, Δείκτες, Δυναμική Διαχείριση Μνήμης, Ανάλυση Αλγορίθμων.

### Μέλη Ομάδας

- Έλενα Παλαιοκώστα: Υλοποίηση AVL Tree, λογική εξισορρόπησης, περιστροφές και διαχείριση μνήμης.
- Ευστράτιος Βασιλέλλης: Σύγκριση συμβολοσειρών, βελτιστοποιημένη αναζήτηση, αναζητήσεις προθεμάτων με wildcard και ανάλυση απόδοσης.

Τμήμα Πληροφορικής — Πανεπιστήμιο Πειραιώς

## README (English Version)

# AVL Tree String Indexer & Search Engine

### Description

This project implements an efficient string indexing and search engine in C++ using a self-balancing AVL Tree. Developed as part of the Data Structures course, it supports string insertion, deletion, optimized searching, and prefix queries with wildcard support.

The implementation maintains tree balance through balance factors and automatic rotations, without storing node heights, ensuring efficient search and update operations.

### Key Features

- Self-balancing AVL Tree with automatic LL, RR, LR, and RL rotations.
- Dynamic insertion and deletion of string keys.
- Optimized string comparison using skip-match search.
- Prefix searching with wildcard support (`*`).
- Efficient memory management and prevention of memory leaks.
- Performance analysis using Big-O notation.

### Technologies

C++, AVL Trees, Binary Search Trees, Recursion, Pointers, Dynamic Memory Management, Algorithm Analysis.

### Team Members

- Elena Paleocosta: AVL Tree implementation, balancing logic, rotations, and memory management.
- Efstratios Vasilellis: String comparison, optimized searching, wildcard prefix queries, and performance analysis.

Department of Informatics — University of Piraeus
