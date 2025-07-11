# Multilevel-Monte-Carlo-Simuations

Αυτό το αποθετήριο περιλαμβάνει την εργασία μας πάνω στην **πολυεπίπεδη μέθοδο Monte Carlo (Multilevel Monte Carlo - MLMC)**, με έμφαση στην αποτίμηση χρηματοοικονομικών παραγώγων. Η εργασία εκπονήθηκε στο πλαίσιο του μαθήματος στη Σχολή Εφαρμοσμένων Μαθηματικών και Φυσικών Επιστημών (ΣΕΜΦΕ) του Ε.Μ.Π.

## 📘 Περιγραφή

Η μέθοδος Multilevel Monte Carlo, όπως εισήχθη από τον Mike Giles το 2008, αποτελεί μια εξελιγμένη τεχνική προσομοίωσης που συνδυάζει πολλά επίπεδα ακρίβειας, μειώνοντας σημαντικά το υπολογιστικό κόστος σε σχέση με τις κλασικές μεθόδους Monte Carlo.

## 📚 Περιεχόμενα

- 📖 **Θεωρητικό Υπόβαθρο**:
  - Ευρωπαϊκά Δικαιώματα (Call/Put)
  - Μοντέλο και Εξίσωση Black-Scholes
  - Μέθοδος Monte Carlo και Αντιθετικές Μεταβλητές
  - Μέθοδος MLMC (2 και πολλαπλά επίπεδα)
  - Ανάλυση Πολυπλοκότητας και Ρυθμοί Σύγκλισης

- 💻 **Υλοποιήσεις**:
  - Κώδικες σε **Python** και **MATLAB** για:
    - Τυπική Monte Carlo Προσομοίωση
    - Antithetic Variates
    - MLMC υπολογιστές (estimators)
  - Εκτίμηση παραμέτρων **α**, **β**, **γ**
  - Έλεγχοι σύγκλισης και σύγκριση κόστους

## 🧪 Παράδειγμα Εφαρμογής

Η μέθοδος εφαρμόζεται στην αποτίμηση **ευρωπαϊκού δικαιώματος πώλησης (Put Option)** με τα παρακάτω χαρακτηριστικά:

- Τιμή μετοχής: `S = 4`
- Τιμή εξάσκησης: `E = 5`
- Μεταβλητότητα: `σ = 0.3`
- Επιτόκιο χωρίς ρίσκο: `r = 0.04`
- Λήξη: `T = 1 έτος`

Γίνεται σύγκριση μεταξύ της ακριβούς λύσης Black-Scholes και των μεθόδων Monte Carlo και MLMC.


## 👨‍🔬 Συντελεστές

- **Αζάς Λεωνίδας** (ge20117)  
- **Ζώρζος Αχιλλέας** (ge20026)

**Επιβλέπων Καθηγητής**: κ. Σωτήρης Σαμπάνης – Εθνικό Μετσόβιο Πολυτεχνείο (Ε.Μ.Π.)


