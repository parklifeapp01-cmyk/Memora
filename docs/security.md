# Security Overview — Memora

_Last updated: 2026_

🇬🇷 [Ελληνικά](#el) | 🇬🇧 [English](#en)

---

## <a id="el"></a>🇬🇷 Ελληνικά

Το **Memora** έχει σχεδιαστεί με επίκεντρο την ασφάλεια και την ιδιωτικότητα.  
Οι αναμνήσεις που φιλοξενούνται στην πλατφόρμα είναι προσωπικές και συχνά ιδιαίτερα ευαίσθητες· η προστασία τους αποτελεί βασική ευθύνη της υπηρεσίας.

Η παρούσα σελίδα περιγράφει, σε υψηλό επίπεδο, τα τεχνικά και οργανωτικά μέτρα ασφάλειας που εφαρμόζονται.

---

### 1. Security by Design
Η ασφάλεια ενσωματώνεται:
- από τον αρχικό σχεδιασμό της πλατφόρμας
- σε όλα τα στάδια ανάπτυξης
- σε κάθε νέα λειτουργία

Το Memora ακολουθεί τις αρχές **privacy by design** και **privacy by default**.

---

### 2. Προστασία δεδομένων

#### Κρυπτογράφηση
- Όλα τα δεδομένα μεταφέρονται μέσω ασφαλών συνδέσεων (HTTPS / TLS)
- Η πρόσβαση σε αποθηκευμένα δεδομένα περιορίζεται αυστηρά

#### Διαχωρισμός δεδομένων
- Τα δεδομένα είναι λογικά απομονωμένα ανά χρήστη
- Δεν υφίσταται κοινή πρόσβαση μεταξύ λογαριασμών

---

### 3. Έλεγχος πρόσβασης
- Πρόσβαση σε δεδομένα παρέχεται μόνο κατόπιν εντολής του χρήστη
- Υποστηρίζονται ρόλοι και επίπεδα πρόσβασης
- Εφαρμόζεται η αρχή **least privilege**

Το προσωπικό του Memora δεν έχει πρόσβαση στο περιεχόμενο χρηστών, εκτός εάν απαιτείται για λόγους υποστήριξης και μόνο κατόπιν εξουσιοδότησης.

---

### 4. Υποδομή & φιλοξενία
- Η πλατφόρμα λειτουργεί σε σύγχρονες cloud υποδομές
- Τα περιβάλλοντα παραγωγής είναι απομονωμένα
- Εφαρμόζονται μηχανισμοί διαθεσιμότητας και ανθεκτικότητας

Δεν φιλοξενούμε δεδομένα σε μη ελεγχόμενα ή τοπικά συστήματα.

---

### 5. Monitoring & καταγραφή
- Καταγράφονται συμβάντα ασφάλειας και λειτουργίας
- Παρακολουθούνται ανωμαλίες και μη εξουσιοδοτημένες προσπάθειες πρόσβασης
- Τα logs περιορίζονται στο απολύτως απαραίτητο

---

### 6. Διαχείριση περιστατικών ασφάλειας
Σε περίπτωση περιστατικού ασφάλειας:
1. Ενεργοποιείται διαδικασία αξιολόγησης
2. Περιορίζεται άμεσα η έκταση του περιστατικού
3. Ενημερώνονται οι επηρεαζόμενοι χρήστες, όπου απαιτείται
4. Λαμβάνονται διορθωτικά και προληπτικά μέτρα

Η διαδικασία ευθυγραμμίζεται με τις απαιτήσεις του GDPR.

---

### 7. Υπο-επεξεργαστές
Το Memora χρησιμοποιεί τρίτους παρόχους (sub-processors) αποκλειστικά για τεχνικές λειτουργίες, όπως φιλοξενία και αποθήκευση δεδομένων.

Όλοι οι πάροχοι:
- δεσμεύονται συμβατικά για την προστασία δεδομένων
- συμμορφώνονται με τον GDPR ή ισοδύναμα πλαίσια
- υπόκεινται σε αξιολόγηση ασφάλειας

---

### 8. Συμμόρφωση
Το Memora συμμορφώνεται με:
- τον Γενικό Κανονισμό Προστασίας Δεδομένων (GDPR)
- τις αρχές ασφάλειας πληροφοριών και ιδιωτικότητας

Σχετικά έγγραφα:
- Privacy Policy
- Terms of Service
- Data Processing Addendum (DPA)
- Sub-processors list

---

### 9. Ευθύνη χρήστη
Η ασφάλεια αποτελεί κοινή ευθύνη.  
Οι χρήστες οφείλουν:
- να προστατεύουν τα στοιχεία πρόσβασης
- να χρησιμοποιούν ασφαλείς συσκευές
- να διαχειρίζονται προσεκτικά τα δικαιώματα πρόσβασης που παραχωρούν

---

### 10. Συνεχής βελτίωση
Η ασφάλεια είναι δυναμική διαδικασία.  
Οι πρακτικές και τα μέτρα αναθεωρούνται και βελτιώνονται συνεχώς.

---

### 11. Επικοινωνία
Για θέματα ασφάλειας ή αναφορά περιστατικών:  
📧 skotsigiannis@gmail.com

---

## <a id="en"></a>🇬🇧 English

**Memora** is designed with security and privacy at its core.  
The memories hosted on the platform are personal and often highly sensitive; protecting them is a fundamental responsibility of the service.

This page provides a high-level overview of the technical and organizational security measures applied.

---

### 1. Security by Design
Security is embedded:
- from the initial design of the platform
- throughout all development stages
- in every new feature

Memora follows the principles of **privacy by design** and **privacy by default**.

---

### 2. Data protection

#### Encryption
- All data is transmitted via secure connections (HTTPS / TLS)
- Access to stored data is strictly restricted

#### Data separation
- Data is logically isolated per user
- No shared access exists between accounts

---

### 3. Access control
- Access to data is provided only upon user instruction
- Roles and access levels are supported
- The **least privilege** principle is applied

Memora personnel do not access user content unless required for support purposes and only with proper authorization.

---

### 4. Infrastructure & hosting
- The platform operates on modern cloud infrastructure
- Production environments are isolated
- Availability and resilience mechanisms are implemented

Data is not hosted on unmanaged or local systems.

---

### 5. Monitoring & logging
- Security and operational events are logged
- Anomalies and unauthorized access attempts are monitored
- Logs are limited to what is strictly necessary

---

### 6. Security incident management
In the event of a security incident:
1. An assessment process is initiated
2. The scope of the incident is immediately contained
3. Affected users are informed where required
4. Corrective and preventive measures are taken

The process aligns with GDPR requirements.

---

### 7. Sub-processors
Memora uses third-party providers (sub-processors) solely for technical functions such as hosting and data storage.

All providers:
- are contractually bound to protect data
- comply with the GDPR or equivalent frameworks
- are subject to security assessment

---

### 8. Compliance
Memora complies with:
- the General Data Protection Regulation (GDPR)
- information security and privacy principles

Related documents:
- Privacy Policy
- Terms of Service
- Data Processing Addendum (DPA)
- Sub-processors list

---

### 9. User responsibility
Security is a shared responsibility.  
Users are expected to:
- protect their access credentials
- use secure devices
- carefully manage access rights they grant

---

### 10. Continuous improvement
Security is a dynamic process.  
Practices and measures are continuously reviewed and improved.

---

### 11. Contact
For security-related matters or incident reporting:  
📧 skotsigiannis@gmail.com

---

**Memora — Μνήμη, με μέλλον.**
**Memora — Memory, with a future.**
