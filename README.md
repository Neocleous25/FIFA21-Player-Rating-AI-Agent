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
- Το target `overall` μετατράπηκε σε κατηγορία: **Low** , **Top**
- Κωδικοποίηση κατηγορικών (Label Encoding)
- Χωρισμός training/test set
- Εκπαίδευση με Random Forest Classifier (`class_weight="balanced"`)
- Τελικό Accuracy: **89,6%**

## 🤖 AI Agent Project (`AI Agent Project.ipynb`)

- Παίρνει input από τον χρήστη
- Προβλέπει κατηγορία rating
- Εμφανίζει αποτελέσματα με 🌐 emoji
- Παράγει mini feedback σε φυσική γλώσσα:
  - 💡 Ηλικία: Παίκτης με εμπειρία ή αναπτυξιακό δυναμικό
  - 📏 Σωματικά: Πλεονεκτήματα (π.χ. για aerial duels) ή ανάγκη ενδυνάμωσης
  - 📊 Απόδοση: Ανάλυση βάσει πρόβλεψης (Low , Top)

## 🔮 Πώς να το τρέξετε

1. Ανοίγετε τα αρχεία Machine Learning.ipynb και AI Agent Project.ipynb στο Google Colab
2. Για το Machine Learning notebook:
   - Βεβαιωθείτε ότι έχετε ανεβάσει το dataset players_21.csv στο Google Drive
   - Η σύνδεση με το αρχείο γίνεται απευθείας από το Drive
3. Για το AI Agent notebook:
   - Εξάγετε (export) το εκπαιδευμένο μοντέλο από το ML notebook ως model.pkl
   - Στη συνέχεια, ανεβάζετε το model.pkl στο AI Agent notebook για να γίνει η πρόβλεψη
4. Τρέχετε τα κελιά (Run) και το σύστημα λειτουργεί αυτόματα.

## 📽  Demo Video

[Δές το βίντεο εδώ](https://youtu.be/7OeAJuN8Y8I)
