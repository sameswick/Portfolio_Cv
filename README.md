#  Data Science & Machine Learning Portfolio

##  O mnie

Cześć 🙂  

To repozytorium zawiera moje projekty z obszaru **Data Science i Machine Learning**, oparte na realnych problemach biznesowych takich jak:

- analiza klientów i churn
- credit scoring i ryzyko kredytowe
- prognozowanie sprzedaży i przychodu

Każdy projekt został wykonany end-to-end:  
od **EDA → preprocessing → modelowanie → interpretacja biznesowa**.

---

##  Cel portfolio

Celem tego portfolio jest pokazanie umiejętności pracy z danymi w praktyce:

- analiza i eksploracja danych (EDA)
- inżynieria cech (feature engineering)
- budowa modeli ML (klasyfikacja i regresja)
- obsługa niezbalansowanych danych
- optymalizacja modeli (Optuna)
- interpretacja wyników w kontekście biznesowym

---

## Projekty

---

#  Bank Credit Scoring – Predykcja niewypłacalności

##  Cel projektu
Predykcja ryzyka niewypłacalności klientów banku (`SeriousDlqin2yrs`) w horyzoncie 2 lat.

---

##  Kluczowe elementy

###  EDA
- analiza wieku → młodzi klienci = wyższe ryzyko
- historia opóźnień → najsilniejszy predictor defaultu
- Debt Ratio → silny wskaźnik zadłużenia
- analiza segmentów klientów (wiek + dochód)

---

###  Modelowanie
- LightGBM, XGBoost, Random Forest
- BorderlineSMOTE (imbalanced data)
- Optuna (tuning hiperparametrów)
- pipeline preprocessing + encoding

---

###  Wyniki
- ROC-AUC ~0.85
- Recall: 57%
- Accuracy: 89%

---

###  Wnioski biznesowe
- historia spłat = kluczowy czynnik ryzyka
- wiek silnie koreluje ze stabilnością finansową
- model skutecznie identyfikuje klientów wysokiego ryzyka

---

# Bank Churn Analysis & Prediction

##  Cel projektu
Identyfikacja klientów zagrożonych odejściem z banku oraz budowa modelu predykcyjnego churnu.

---

##  Kluczowe elementy

###  EDA
- analiza wieku i płci klientów
- wpływ liczby produktów na churn
- aktywność klienta vs odejścia
- analiza salda konta i segmentów klientów

---

###  Modelowanie
- XGBoost jako główny model
- BorderlineSMOTE (klasa niezbalansowana)
- Optuna (hyperparameter tuning)
- Cross-validation

---

###  Wyniki
- Recall: 0.77
- Precision: 0.48
- F1-score: 0.59
- Accuracy: 0.79

---

###  Wnioski biznesowe
- klienci 40–60 lat = najwyższe ryzyko churn
- nieaktywność = silny predyktor odejścia
- segment wysokiego salda = największy potencjał utraty przychodu

---

#  Makeup Sales Analysis & Revenue Prediction

##  Cel projektu
Analiza sprzedaży produktów kosmetycznych oraz predykcja dziennego przychodu.

---

##  Kluczowe elementy

###  EDA
- top 5 marek i produktów
- analiza kanałów sprzedaży (online vs offline)
- trendy sprzedaży w czasie
- analiza regionalna (brand vs country)
- sezonowość i zmienność sprzedaży

---

###  Modelowanie
- Random Forest Regressor
- One-Hot Encoding
- scaling danych
- Optuna (tuning)

---

###  Wyniki
- MAE: ~666 USD
- R²: 0.37

---

###  Wnioski biznesowe
- sprzedaż silnie zależna od marki i kanału
- kanał online dominuje w revenue
- model pozwala przewidywać przychód z użyteczną dokładnością biznesową

---

##  Stack technologiczny

- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost / LightGBM / Random Forest
- imbalanced-learn (SMOTE)
- Optuna (Bayesian optimization)
- Matplotlib, Seaborn

---

##  Kluczowe umiejętności

- analiza danych (EDA)
- feature engineering
- modele klasyfikacyjne i regresyjne
- praca z niezbalansowanymi danymi
- tuning hiperparametrów
- interpretacja wyników ML
- myślenie biznesowe (business-oriented ML)

---

##  Co to portfolio pokazuje

To repozytorium pokazuje umiejętność:

- pracy z realnymi danymi biznesowymi
- budowy modeli ML end-to-end
- interpretacji wyników w kontekście biznesowym
- rozwiązywania problemów (churn, credit risk, revenue forecasting)

---

##  Podsumowanie

Każdy projekt odpowiada na realne pytanie biznesowe:

- Kto nie spłaci kredytu?
- Kto odejdzie z banku?
- Jak przewidzieć przychód sprzedaży?



