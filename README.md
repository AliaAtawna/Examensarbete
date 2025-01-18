# Examensarbete: Förutsägelse av fastighetspriser med maskininlärning

## 📋 Beskrivning
Detta repository innehåller kod och dokumentation för mitt examensarbete, där jag undersöker hur maskininlärning kan användas för att förutsäga fastighetspriser och identifiera betydande faktorer som påverkar fastighetsvärderingar. Projektet jämför tre maskininlärningsmodeller: **Linjär regression**, **Random Forest**, och **Support Vector Regression (SVR)**, och utvärderar deras prestanda med hjälp av olika mätetal.

---

## 🚀 Funktioner
- **Databehandling:** Log-transformering, kodning av kategoriska variabler och hantering av outliers.
- **Utforskande dataanalys (EDA):** Visualiseringar såsom histogram, korrelationsmatriser och scatterplots.
- **Maskininlärning:** Implementering och optimering av tre modeller.
- **Utvärdering:** Prestandamått som RMSE, MAE och R² används för modellutvärdering.
- **Insikter:** Variabelanalys med Random Forest för att identifiera viktiga faktorer som påverkar fastighetspriser.

---

## 📂 Filstruktur
Examensarbete/ ├── data/ # Dataset för analysen ├── notebooks/ # Jupyter Notebook-filer för analys och visualisering ├── src/ # Källkod för databehandling och modellimplementering ├── README.md # Dokumentation av projektet └── requirements.txt # Lista över beroenden för projektet

---

## ⚙️ Installation

### För att köra projektet lokalt:
1. Klona detta repository:
   ```bash
   git clone https://github.com/AliaAtawna/Examensarbete.git

2. Navigera till projektmappen:
cd Examensarbete

3. Installera beroenden:
pip install -r requirements.txt

4. Öppna en Jupyter Notebook eller kör Python-skriptet för att utföra analysen.

## 📊 Resultat och Slutsatser
SVR presterade bäst med den lägsta RMSE och MAE, vilket visar dess styrka att hantera icke-linjära samband.
Random Forest gav värdefulla insikter i variabelbetydelse, där faktorer som bostadsarea och antal badrum hade störst påverkan.
Projektet visar på potentialen för maskininlärning att förbättra fastighetsvärderingar och erbjuder praktiska tillämpningar för fastighetsägare, investerare och stadsplanerare.

## 🛠 Verktyg och Tekniker
Programmeringsspråk: Python
Bibliotek:
pandas, NumPy för datahantering
scikit-learn för maskininlärning
Matplotlib, Seaborn för visualisering
Utvecklingsmiljö: Jupyter Notebook och VS Code

## 📌 Licens
Detta projekt är licensierat under MIT License.

## 📫 Kontakt
Om du har frågor eller feedback, vänligen kontakta mig via GitHub.
