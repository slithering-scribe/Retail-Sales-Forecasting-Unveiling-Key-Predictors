# Retail Sales Forecasting / Prognose für Einzelhandelsumsätze

---

## About Me / Über mich

**English:**  
Hi, I’m [@slithering-scribe](https://github.com/slithering-scribe)  
I’m interested in data analysis, machine learning, and uncovering hidden insights in retail sales data.  
I’m currently learning advanced machine learning techniques and feature engineering to enhance predictive models.  
I’m looking to collaborate on projects related to data science, predictive analytics, and initiatives focused on optimizing retail sales strategies.  
**How to reach me:** [tamara.kachalla@outlook.com](mailto:tamara.kachalla@outlook.com)  
**Pronouns:** He/Him  
**Fun Fact:** One shared car can replace between 5 and 8 privately owned cars, contributing significantly to a sustainable future.

**Deutsch:**  
Hallo, ich bin [@slithering-scribe](https://github.com/slithering-scribe)  
Ich interessiere mich für Datenanalyse, Machine Learning und das Aufdecken verborgener Erkenntnisse in Einzelhandelsumsätzen.  
Derzeit lerne ich fortgeschrittene Machine-Learning-Techniken und Feature Engineering, um prädiktive Modelle zu optimieren.  
Ich suche Kooperationen in Projekten rund um Data Science, prädiktive Analytik und Initiativen zur Optimierung von Vertriebsstrategien im Einzelhandel.  
**Kontakt:** [tamara.kachalla@outlook.com](mailto:tamara.kachalla@outlook.com)  
**Pronomen:** He/Him  
**Fun Fact:** Ein gemeinsam genutztes Auto kann zwischen 5 und 8 privat genutzte Autos ersetzen und so maßgeblich zu einer nachhaltigen Zukunft beitragen.

---

## Project Overview / Projektübersicht

**English:**  
Welcome to the Retail Sales Forecasting project! This project leverages advanced machine learning models to analyze and predict retail sales. By identifying key predictors and understanding underlying patterns and trends, the project seeks to optimize sales strategies and improve decision-making processes—all while adhering to EU data standards.

**Deutsch:**  
Willkommen beim Projekt „Prognose für Einzelhandelsumsätze“! Dieses Projekt nutzt fortschrittliche Machine-Learning-Modelle, um Einzelhandelsumsätze zu analysieren und vorherzusagen. Durch die Identifikation wichtiger Einflussfaktoren sowie das Verständnis zugrunde liegender Muster und Trends soll die Optimierung von Vertriebsstrategien und eine verbesserte Entscheidungsfindung erreicht werden – und das unter Einhaltung der EU-Datenstandards.

---

## Key Features / Hauptfunktionen

- **Data Analysis / Datenanalyse:**  
  Perform exploratory data analysis (EDA) to uncover insights and patterns.  
  Durchführung einer explorativen Datenanalyse (EDA), um Erkenntnisse und Muster zu entdecken.

- **Feature Engineering / Merkmal-Engineering:**  
  Create new features that capture additional information and improve model performance.  
  Entwicklung neuer Merkmale zur Erfassung zusätzlicher Informationen und Verbesserung der Modellleistung.

- **Model Building / Modellaufbau:**  
  Implement various machine learning models including Linear Regression, Gradient Boosting, Neural Networks, and XGBoost.  
  Implementierung verschiedener Machine-Learning-Modelle wie Lineare Regression, Gradient Boosting, Neuronale Netze und XGBoost.

- **Model Evaluation / Modellevaluierung:**  
  Evaluate models using metrics such as MSE and R² Score to select the best-performing model.  
  Bewertung der Modelle anhand von Metriken wie MSE und R², um das leistungsstärkste Modell auszuwählen.

- **Ensemble Methods / Ensemble-Methoden:**  
  Combine multiple models to further enhance prediction accuracy.  
  Kombination mehrerer Modelle, um die Vorhersagegenauigkeit weiter zu verbessern.

---

## Project Structure / Projektstruktur

```
retail-sales-forecasting/
├── data/                 # Dataset and preprocessing scripts / Datensätze und Vorverarbeitungsskripte
├── notebooks/            # Jupyter notebooks for analysis and modeling / Jupyter Notebooks für Analyse und Modellierung
├── models/               # Trained models and related scripts / Gespeicherte Modelle und zugehörige Skripte
├── reports/              # Detailed reports on findings and model performance / Detaillierte Berichte zu Erkenntnissen und Modellleistung
├── visualizations/       # Visualizations and charts / Visualisierungen und Diagramme
├── requirements.txt      # Required Python packages / Erforderliche Python-Pakete
└── README.md             # Project documentation / Projektdokumentation
```

---

## How to Use / Anwendung

1. **Clone the Repository / Repository klonen:**

   ```bash
   git clone https://github.com/yourusername/retail-sales-forecasting.git
   cd retail-sales-forecasting
   ```

2. **Install Dependencies / Abhängigkeiten installieren:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks / Notebooks starten:**

   Open the Jupyter notebooks and follow the step-by-step instructions for data analysis, model building, and evaluation.  
   Öffnen Sie die Jupyter Notebooks und folgen Sie den Schritt-für-Schritt-Anweisungen zur Datenanalyse, zum Modellaufbau und zur Evaluation.

---

## Model Results / Modellergebnisse

### **First Result: Gradient Boosting Model / Erstes Ergebnis: Gradient Boosting Modell**

- **Best Parameters / Beste Parameter:**  
  - Learning Rate: 0.05  
    Lernrate: 0,05  
  - Max Depth: 5  
    Maximale Tiefe: 5  
  - Number of Estimators: 100  
    Anzahl der Schätzer: 100

- **Model Performance / Modellleistung:**  
  - Best Score: -1,232,526.95  
    Bester Score: -1.232.526,95  
  - Test MSE: 1,082,054.53  
    Test-MSE: 1.082.054,53  
  - Test R² Score: 0.602  
    Test-R²: 0,602

- **Key Takeaways / Zentrale Erkenntnisse:**  
  - The optimized Gradient Boosting model achieved significant improvements in prediction accuracy.  
    Das optimierte Gradient Boosting Modell erreichte eine signifikante Verbesserung der Vorhersagegenauigkeit.
  - Next steps include fine-tuning the neural network and exploring ensemble methods to further enhance performance.  
    Nächste Schritte umfassen die Feinabstimmung des neuronalen Netzes und die Untersuchung von Ensemble-Methoden zur weiteren Leistungssteigerung.
  - **Rationale for Ensemble Methods / Begründung für Ensemble-Methoden:**  
    Combining the strengths of multiple models may lead to a more robust and accurate forecasting system.  
    Die Kombination der Stärken mehrerer Modelle kann zu einem robusterem und genaueren Vorhersagesystem führen.

---

### **Second Result: XGBoost Model / Zweites Ergebnis: XGBoost Modell**

- **Model Performance / Modellleistung:**  
  - Train MSE: 1,022,614.78  
    Trainings-MSE: 1.022.614,78  
  - Test MSE: 1,076,559.26  
    Test-MSE: 1.076.559,26  
  - Train R² Score: 0.654  
    Trainings-R²: 0,654  
  - Test R² Score: 0.604  
    Test-R²: 0,604

- **Comparison of Models / Vergleich der Modelle:**
  - **Linear Regression / Lineare Regression:**  
    - Test MSE: 1,709,388.28  
      Test-MSE: 1.709.388,28  
    - Test R² Score: 0.371  
      Test-R²: 0,371
  - **Gradient Boosting / Gradient Boosting:**  
    - Test MSE: 1,070,082.16  
      Test-MSE: 1.070.082,16  
    - Test R² Score: 0.606  
      Test-R²: 0,606
  - **Neural Network / Neuronales Netz:**  
    - Test MSE: 1,688,351.88  
      Test-MSE: 1.688.351,88
  - **Ensemble Model / Ensemble-Modell:**  
    - Test MSE: 1,279,857.33  
      Test-MSE: 1.279.857,33  
    - Test R² Score: 0.529  
      Test-R²: 0,529
  - **XGBoost:**  
    - Test MSE: 1,076,559.26  
      Test-MSE: 1.076.559,26  
    - Test R² Score: 0.604  
      Test-R²: 0,604

- **Key Insights / Zentrale Erkenntnisse:**  
  - **Top Performers / Beste Modelle:**  
    Both Gradient Boosting and XGBoost models demonstrate superior performance with lower MSE and higher R² scores.  
    Sowohl das Gradient Boosting als auch das XGBoost Modell zeigen überlegene Leistungen mit niedrigeren MSE-Werten und höheren R²-Scores.
  - **Ensemble Approach / Ensemble-Ansatz:**  
    While the ensemble model offers improvements, it does not outperform the top individual models.  
    Obwohl das Ensemble-Modell Verbesserungen bietet, übertrifft es nicht die besten Einzelmodelle.
  - **Feature Importance / Wichtige Merkmale:**  
    Key features driving predictions include Item_MRP, Item_Visibility, Outlet_Age, Outlet_Establishment_Year, and Item_Weight.  
    Zu den Schlüsselfaktoren zählen Item_MRP, Item_Visibility, Outlet_Age, Outlet_Establishment_Year und Item_Weight.

- **Next Steps / Nächste Schritte:**  
  - **Hyperparameter Tuning:** Further refine the XGBoost and Gradient Boosting models.  
    Weitere Feinabstimmung der XGBoost- und Gradient Boosting-Modelle.
  - **Feature Engineering:** Explore creating additional features or applying transformations.  
    Zusätzliche Merkmale entwickeln oder Transformationen anwenden.
  - **Business Insights:** Translate findings into actionable recommendations for optimizing retail strategies.  
    Erkenntnisse in umsetzbare Empfehlungen zur Optimierung von Einzelhandelsstrategien umwandeln.

---

## Contributions / Mitwirken

**English:**  
Contributions are welcome! If you have suggestions, improvements, or bug reports, please open an issue or submit a pull request. Let’s work together to make data-driven retail strategies more effective.

**Deutsch:**  
Beiträge sind willkommen! Wenn Sie Vorschläge, Verbesserungen oder Fehlerberichte haben, eröffnen Sie bitte ein Issue oder senden Sie einen Pull Request. Lassen Sie uns gemeinsam daran arbeiten, datengestützte Einzelhandelsstrategien effektiver zu gestalten.

---

## License / Lizenz

This project is licensed under the MIT License.  
Dieses Projekt ist unter der MIT-Lizenz lizenziert.

---

## Final Note / Abschließende Hinweise

Happy forecasting! 🚀📊  
Viel Erfolg bei der Prognose!
