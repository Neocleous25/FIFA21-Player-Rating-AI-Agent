🎮 FIFA21 Player Rating Predictor + AI Agent 🎮

Χρησιμοποιήθηκε το DataSet **players_21.csv** από το FIFA21. Περιέχει χαρακτηριστικά παικτών όπως:

- Ηλικία (age)
- Ύψος (height_cm)
- Βάρος (weight_kg)
- Εθνικότητα (nationality)
- Σύλλογος (club_name)
- Rating (overall)

## 📊 Machine Learning Project (`Machine Learning.ipynb`)

- Επιλέχθηκαν χαρακτηριστικά: `age`, `height_cm`, `weight_kg`, `nationality`, `club_name`
- Το target `overall` μετατράπηκε σε κατηγορία: **Low**, **Average**, **Top**
- Κωδικοποίηση κατηγορικών (Label Encoding)
- Χωρισμός training/test set
- Εκπαίδευση με Random Forest Classifier (`class_weight="balanced"`)
- Τελικό Accuracy: **92.2%**

## 🤖 AI Agent Project (`AI Agent Project.ipynb`)

- Γεννά agent με τυχαία χαρακτηριστικά παικτών
- Προβλέπει κατηγορία rating
- Εμφανίζει αποτελέσματα με 🌐 emoji
- Περιλαμβάνει what-if ανάλυση (π.χ. "τι θα γινόταν αν ήταν 190cm ψηλός")
- Παράγει mini feedback σε φυσική γλώσσα:
  - 💡 Ηλικία: Παίκτης με εμπειρία ή αναπτυξιακό δυναμικό
  - 📏 Σωματικά: Πλεονεκτήματα (π.χ. για aerial duels) ή ανάγκη ενδυνάμωσης
  - 📊 Απόδοση: Ανάλυση βάσει πρόβλεψης (Top, Average, Low)

## 🔮 Πώς να το τρέξετε

1. Ανοίξτε τα αρχεία `Machine Learning.ipynb` και `AI Agent Project.ipynb` στο Google Colab
2. Βεβαιωθείτε ότι έχετε ανεβάσει το dataset `players_21.csv` στο Google Drive
3. Τρέξτε όλα τα κελιά (Run all)

## 📽  Demo Video

[Δές το βίντεο εδώ](https://youtu.be/oAxMoMxfkj4)
