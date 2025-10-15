# 🚀 Quick Start Guide - Εορτολόγιο Web App

## Άμεση Εκκίνηση (3 βήματα)

### 1️⃣ Άνοιγμα με Live Server (Συνιστάται)

**VS Code:**
1. Εγκαταστήστε το extension "Live Server"
2. Right-click στο `index.html` → "Open with Live Server"
3. Η εφαρμογή ανοίγει αυτόματα στο `http://localhost:5500`

**Ή χρησιμοποιήστε:**
```bash
# Python
python -m http.server 8000

# Node.js
npx http-server

# PHP
php -S localhost:8000
```

### 2️⃣ Άνοιγμα Απευθείας σε Browser

Απλά ανοίξτε το `index.html` με double-click ή:
```
File → Open → index.html
```

⚠️ **Προσοχή:** Χωρίς web server, το PWA (offline mode) δεν θα λειτουργήσει.

### 3️⃣ Test & Demo Pages

```bash
test.html   # Τεστ λειτουργικότητας
demo.html   # Οδηγίες και πληροφορίες
index.html  # Κύρια εφαρμογή
```

---

## 📱 Εγκατάσταση σε Mobile

### iPhone (Safari)
1. Ανοίξτε την εφαρμογή στο Safari
2. Πατήστε το Share button (□↑)
3. Scroll → "Add to Home Screen"
4. Πατήστε "Add"
5. Το app εμφανίζεται στην αρχική οθόνη!

### Android (Chrome)
1. Ανοίξτε την εφαρμογή στο Chrome
2. Πατήστε Menu (⋮)
3. Επιλέξτε "Install App" ή "Add to Home screen"
4. Πατήστε "Install"
5. Το app εμφανίζεται στο app drawer!

---

## ⚙️ Βασικές Ρυθμίσεις

### Αλλαγή Γεωγραφικής Θέσης

1. Πατήστε το ⚙️ (πάνω δεξιά)
2. Εισάγετε τις συντεταγμένες σας:
   - **Αθήνα:** 37.58, 23.43
   - **Θεσσαλονίκη:** 40.64, 22.93
   - **Πάτρα:** 38.25, 21.73
   - **Ηράκλειο:** 35.33, 25.13

3. Πατήστε "Αποθήκευση"

💡 **Tip:** Βρείτε τις συντεταγμένες σας στο Google Maps:
- Κάντε δεξί κλικ στο χάρτη
- Επιλέξτε τις συντεταγμένες που εμφανίζονται

### Αλλαγή Γλώσσας

Στις ρυθμίσεις (⚙️):
- **Ελληνικά:** Πλήρες εορτολόγιο
- **English:** Χωρίς εορτολόγιο

---

## 🎮 Χρήση

### Desktop
- **Πλοήγηση:** Κουμπιά Προηγ. / Σήμερα / Επόμ.
- **Εορτολόγιο:** Κλικ στην κάρτα "Εορτάζουν"
- **Ρυθμίσεις:** Κλικ στο ⚙️

### Mobile
- **Swipe Right:** Προηγούμενη ημέρα
- **Swipe Left:** Επόμενη ημέρα
- **Tap "Εορτάζουν":** Πλήρη λίστα ονομάτων
- **Auto-reset:** Επιστροφή στο σήμερα μετά από 5 δευτ.

---

## 🔧 Troubleshooting

### "Service Worker failed to register"
- Χρησιμοποιήστε HTTPS ή localhost
- Ανοίξτε με web server, όχι file://

### "No namedays showing"
- Ελέγξτε ότι το `app.js` φορτώθηκε σωστά
- Δείτε το Console για errors (F12)

### "Sunrise/Sunset shows --:--"
- Ελέγξτε τις συντεταγμένες στις ρυθμίσεις
- Βεβαιωθείτε ότι είναι σε σωστή μορφή (π.χ. 37.58)

### "App doesn't work offline"
- Ανοίξτε με HTTPS ή localhost
- Φορτώστε την εφαρμογή μια φορά online πρώτα
- Ελέγξτε αν το Service Worker εγκαταστάθηκε (DevTools → Application → Service Workers)

---

## 📂 Δομή Αρχείων

```
eortologio/
├── index.html          # Κύρια εφαρμογή ⭐
├── app.js             # JavaScript λογική
├── manifest.json      # PWA configuration
├── sw.js              # Service Worker
├── demo.html          # Demo & οδηγίες
├── test.html          # Test suite
├── README.md          # Πλήρης τεκμηρίωση
├── QUICKSTART.md      # Αυτό το αρχείο
└── ICONS-README.md    # Οδηγίες για icons
```

---

## 🎯 Next Steps

1. ✅ Ανοίξτε το `test.html` για να ελέγξετε τη λειτουργικότητα
2. ✅ Δοκιμάστε την εφαρμογή στο mobile σας
3. ✅ Προσαρμόστε τις ρυθμίσεις για την περιοχή σας
4. 📖 Διαβάστε το `README.md` για περισσότερα

---

## 💡 Tips

- **Auto-reset:** Η εφαρμογή επιστρέφει αυτόματα στην τρέχουσα ημέρα μετά από 5 δευτερόλεπτα αδράνειας
- **Swipe Gestures:** Δουλεύουν μόνο σε touch devices
- **Offline:** Μετά την πρώτη φόρτωση, λειτουργεί χωρίς internet
- **Settings:** Αποθηκεύονται αυτόματα στο localStorage

---

## 📞 Support

Για ερωτήσεις ή προβλήματα:
1. Ελέγξτε το `README.md` για FAQ
2. Τρέξτε το `test.html` για διάγνωση
3. Δείτε το Console (F12) για errors

---

**Καλή Χρήση! 🎉**

*Converted from Windows Sidebar Gadget to Modern Web App*
