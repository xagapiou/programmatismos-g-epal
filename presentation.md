lass: cover-page, center, middle, inverse

ΠΡΟΓΡΑΜΜΑΤΙΣΜΟΣ
===========

## Γ' ΕΠΑΛ

### Τομέας Πληροφορικής

---
name: contents

## Περιεχόμενα

.contents[

]

---
layout: true

## Κεφάλαιο 3 - Βασικά στοιχεία γλώσσας προγραμματισμού

---

>Το **Ολοκληρωμένο Περιβάλλον Ανάπτυξης Προγραμμάτων** IDLE (Integrated 
DeveLopment Environment) της Python, είναι ένα Ελεύθερο Λογισμικό/ Λογισμικό Ανοικτού Κώδικα (ΕΛ/ΛΑΚ)

---
layout: true

## 3.1.1 Τύποι δεδομένων

---

>Οι τύποι δεδομένων προσδιορίζουν τον **τρόπο παράστασης** των δεδομένων εσωτερικά στον υπολογιστή, καθώς και το **είδος της επεξεργασίας** τους από αυτόν.

--- 

Οι χαρακτηριστικοί τύποι δεδομένων στην Python είναι:

- ο αριθμητικός.
    Οι αριθμοί στην Python είναι κυρίως τριών τύπων:
   - - ακέραιοι (Integer)
   - - αριθμοί κινητής υποδιαστολής (floating point)
   - - μιγαδικοί αριθμοί (complex numbers), τύπος που δε θα μας απασχολήσει στη συνέχεια.
- ο λογικός (boolean): δέχεται μόνο δύο τιμές, την τιμή True (Αληθής) και την τιμή False (Ψευδής)

>Ο 19, αποτελεί παράδειγμα ακέραιου.
>Οι 256.14 και 28.2E-5, όπου το σύμβολο E δηλώνει δύναμη του 10, είναι παραδείγματα αριθμών κινητής υποδιαστολής (ή floats για συντομία). Σε αυτή την περίπτωση, το 28.2E-5 σημαίνει 28.2 * 10-5. Παρατηρούμε ότι το δεκαδικό τμήμα διαχωρίζεται με το χαρακτήρα τελεία “.” και όχι το κόμμα “,”.

.footnote[
[Python types (documentation)](https://python.readthedocs.io/en/v2.7.2/library/stdtypes.html#numeric-types-int-float-long-complex)
]
---

- οι συμβολοσειρές ή αλφαριθμητικά (strings): μια ακολουθία από χαρακτήρες. Μια συμβολοσειρά 
μπορεί να αποτελείται από περισσότερες από μία λέξεις. Μπορούμε να ορίσουμε μια συμβολοσειρά με μονά 
εισαγωγικά ή με διπλά, αλλά όχι ανάμικτα.

  -[Θέματα 2017 - Α1 Σωστό/Λάθος](https://apps1.minedu.gov.gr/themata/them_progyp_epal_c_hmer_170613.pdf)
  
  -[Θέματα 2024 - Α2 Αντιστοίχιση](https://apps1.minedu.gov.gr/themata/2024_06_them_sc_epal_240611.pdf)

.footnote[
[Python strings (documentation)](https://python.readthedocs.io/en/v2.7.2/library/stdtypes.html#sequence-types-str-unicode-list-tuple-bytearray-buffer-xrange)
]

---

### Άσκηση 1
> Για να ελέγξουμε τον τύπο δεδομένων χρησιμοποιούμε την συνάρτηση type ().
```python
type(1)
type(3.14)
a = True
type(False)
type(‘Αρετή’)
```
-Τι θα εμφανίσει η κάθε γραμμή; Γιατί;
```python
# Παράδειγμα 1 - Ex01_first_prog.py
# -----------------------------
greeting = 'ΚΑΛΗΜΕΡΑ ΣΕ ΟΛΗ ΤΗΝ ΕΛΛΑΔΑ'
print greeting
```

-Τι σημαίνει η κάθε γραμμή;

-Τι θα εμφανίσει;

---

### Άσκηση 2
> Να αντιστοιχίσετε την στήλη Α με την στήλη Β
> 
| Στήλη Α (Τιμή) | Στήλη Β (Τύπος δεδομένων)|
-----------------|---------------------------
|1. -27 | Α. int (ακέραια) 
|2. 35.7 |Β. float (κινητής υποδιαστολής)
|3. ‘False’ | Γ. string (συμβολοσειρά) 
|4. True | Δ. bool (λογική)
|5. “432.12” 
|6. ‘μεταβλητή’ 
|7. 12 / 2 
|8. 20 % 3 





[themata_2024]: https://apps1.minedu.gov.gr/themata/2024_06_them_sc_epal_240611.pdf
[themata_2023]: https://apps1.minedu.gov.gr/themata/202306_programming_epal_230610.pdf
[themata_2022]: https://apps1.minedu.gov.gr/themata/them_prog_epal_220611.pdf
[themata_2021]: https://apps1.minedu.gov.gr/themata/06_PROGRAMMATISMOS_YPOLOGISTWN_2021.pdf
[themata_2020]: https://apps1.minedu.gov.gr/themata/them_ProgHY_epal_200627.pdf
[themata_2019]: https://apps1.minedu.gov.gr/themata/them_progyp_epal_c_hmer_190611.pdf
[themata_2018]: https://apps1.minedu.gov.gr/themata/them_progyp_epal_c_hmer_180620.pdf
[themata_2017]: https://apps1.minedu.gov.gr/themata/them_progyp_epal_c_hmer_170613.pdf
