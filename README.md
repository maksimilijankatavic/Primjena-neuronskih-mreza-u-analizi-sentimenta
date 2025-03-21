# Primjena neuronskih mreža u analizi sentimenta

Ovaj projekt istražuje primjenu neuronskih mreža u analizi sentimenta koristeći različite pristupe, uključujući leksičke metode i napredne modele dubokog učenja.

## Sadržaj projekta

Projekt sadrži:
- **Jupyter Notebook** s implementacijom modela za analizu sentimenta.
- **Seminarski rad (PDF)** koji opisuje teorijsku podlogu i rezultate.

## Korištene metode

1. **Leksički pristup**: Korištenje VADER (Valence Aware Dictionary and sEntiment Reasoner) modela za analizu sentimenta.
2. **Neuronske mreže**: Implementacija RoBERTa i DistilBERT modela iz Hugging Face biblioteke.

## Kako koristiti

1. **Preuzmite repozitorij**:

   ```bash
   git clone https://github.com/maksimilijankatavic/Primjena-neuronskih-mreza-u-analizi-sentimenta.git
   ```
2. **Otvorite Google Colab, učitajte `Primjena_neuronskih_mreža_u_analizi_sentimenta.ipynb`, zatim promijenite sljedeći kod kako bi odgovarao lokaciji datoteke s podacima na vašem Google Driveu:**

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   
   %cd "/content/drive/MyDrive/Primjena neuronskih mreža u analizi sentimenta"
   ```
3. **Pokrenite sve ćelije.**

## Rezultati

Rezultati pokazuju da su modeli dubokog učenja, posebice RoBERTa, precizniji u analizi sentimenta u usporedbi s leksičkim metodama poput VADER-a.

## Napomena
Ovaj projekt razvijen je kao dio kolegija Uvod u umjetnu inteligenciju (3. godina) na Prirodoslovno-matematičkom fakultetu Sveučilišta u Splitu.
