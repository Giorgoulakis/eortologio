# Εορτολόγιο - Modern Web App 📱

Το **Εορτολόγιο** είναι μια σύγχρονη web εφαρμογή που μετατράπηκε από Windows Sidebar Gadget σε Progressive Web App (PWA) με εμφάνιση iPhone mobile εφαρμογής.

## ✨ Χαρακτηριστικά

- 📅 **Ελληνικό Ορθόδοξο Ημερολόγιο**
- 🎉 **Πλήρες Εορτολόγιο** με σταθερές και κινητές γιορτές
- ☀️ **Ανατολή & Δύση Ηλίου** με ακριβείς αστρονομικούς υπολογισμούς
- 🌙 **Φάσεις Σελήνης** (Πανσέληνος, Νέα Σελήνη, ηλικία σελήνης)
- 🌍 **Προσαρμόσιμη Τοποθεσία** (Γεωγραφικό πλάτος & μήκος)
- 🌐 **Διγλωσσία** (Ελληνικά / English)
- 📱 **PWA Support** - Εγκατάσταση σαν native εφαρμογή
- 💾 **Offline Mode** - Λειτουργεί χωρίς internet
- 👆 **Swipe Gestures** - Σύρετε αριστερά/δεξιά για πλοήγηση
- 🎨 **Modern UI/UX** - iPhone-style εμφάνιση

## 🚀 Εγκατάσταση & Χρήση

### Τοπική Εκτέλεση

1. Ανοίξτε το φάκελο σε έναν web server (π.χ. Live Server στο VS Code)
2. Ανοίξτε το `index.html` στον browser σας
3. Για PWA λειτουργικότητα χρειάζεται HTTPS ή localhost

### Εγκατάσταση στο iPhone/Android

1. Ανοίξτε την εφαρμογή στο Safari (iOS) ή Chrome (Android)
2. Πατήστε το κουμπί "Share" / "Κοινοποίηση"
3. Επιλέξτε "Add to Home Screen" / "Προσθήκη στην Αρχική Οθόνη"
4. Η εφαρμογή θα εγκατασταθεί σαν native app!

## 🎮 Οδηγίες Χρήσης

### Πλοήγηση
- **Προηγ.** - Προηγούμενη ημέρα
- **Σήμερα** - Επιστροφή στην τρέχουσα ημέρα
- **Επόμ.** - Επόμενη ημέρα
- **Swipe** - Σύρετε αριστερά για επόμενη, δεξιά για προηγούμενη

### Ρυθμίσεις
1. Πατήστε το εικονίδιο ⚙️ στην επάνω δεξιά γωνία
2. Επιλέξτε γλώσσα
3. Ορίστε τις γεωγραφικές συντεταγμένες της περιοχής σας
4. Οι ρυθμίσεις αποθηκεύονται αυτόματα

### Εμφάνιση Πλήρους Εορτολογίου
- Πατήστε την κάρτα "Εορτάζουν Σήμερα" για να δείτε την πλήρη λίστα ονομάτων

## 🔧 Τεχνικές Λεπτομέρειες

### Αρχεία
- `index.html` - Κύρια σελίδα της εφαρμογής
- `app.js` - JavaScript κώδικας (λογική εφαρμογής)
- `manifest.json` - PWA manifest
- `sw.js` - Service Worker για offline λειτουργία

### Τεχνολογίες
- **HTML5** με semantic markup
- **CSS3** με modern features (flexbox, animations, gradients)
- **Vanilla JavaScript** (ES6+)
- **PWA APIs** (Service Worker, Web Manifest)
- **LocalStorage** για αποθήκευση ρυθμίσεων

### Υπολογισμοί
- **Πάσχα**: Γκαουσιανός αλγόριθμος για Ορθόδοξο Πάσχα
- **Ανατολή/Δύση**: Αστρονομικοί υπολογισμοί με Ιουλιανή ημερομηνία
- **Σελήνη**: Υπολογισμός φάσης με βάση σύνοδο (29.53 ημέρες)

## 📋 Προεπιλεγμένες Ρυθμίσεις

- **Γλώσσα**: Ελληνικά
- **Γεωγραφικό Πλάτος**: 37.58° (Αθήνα)
- **Γεωγραφικό Μήκος**: 23.43° (Αθήνα)

## 🌟 Νέες Λειτουργίες (vs Original)

✅ **Responsive Design** - Λειτουργεί σε όλες τις συσκευές  
✅ **Touch Gestures** - Swipe για πλοήγηση  
✅ **Modern UI** - Gradient backgrounds, animations, shadows  
✅ **PWA Support** - Offline mode, installable  
✅ **Better UX** - Smooth animations, haptic feedback  
✅ **Auto-reset** - Αυτόματη επιστροφή στο σήμερα  
✅ **Settings Persistence** - Αποθήκευση ρυθμίσεων  

## 📝 Σημειώσεις

- Η εφαρμογή περιλαμβάνει ένα δείγμα του εορτολογίου
- Για πλήρη δεδομένα, προσθέστε όλα τα entries από το `MyCode.js`
- Οι αστρονομικοί υπολογισμοί είναι απλοποιημένοι αλλά ακριβείς
- Το auto-reset ενεργοποιείται μετά από 5 δευτερόλεπτα αδράνειας

## 👥 Credits

**Original Authors:**
- Giorgoulakis Giannis (giorgoulakis@gmail.com) - Code
- Arnaoutoglou George (arnaoutoglou@gmail.com) - Design

**Converted to Modern Web App:** 2025

## 📱 Browser Support

- ✅ iOS Safari 12+
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Edge 80+
- ✅ Samsung Internet

## 📄 License

Original copyright © 2010  
Converted and modernized with respect to original work.

---

**Καλή Χρήση! 🎉**
