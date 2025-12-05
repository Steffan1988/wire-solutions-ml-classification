# ML-Classificatie Analyse (Wire Solutions)

Deze repository bevat de Jupyter Notebook, dataset en ondersteunende code die zijn gebruikt voor de machine-learninganalyse (tekstclassificatie) binnen het data-onderzoek voor Wire Solutions.

## Doel van de analyse

In deze analyse is onderzocht of incidenten met een ontbrekende afdelingsregistratie automatisch kunnen worden aangevuld op basis van de incidentbeschrijving.  
Daarvoor is een klassiek ML-model toegepast met **TF-IDF vectorisatie** en **Logistic Regression**.

De resultaten worden gebruikt om:

- te bepalen of tekstbeschrijvingen voldoende onderscheidend zijn,  
- te beoordelen of ML geschikt is voor automatische categorisatie,  
- inzicht te geven in de beperkingen van ML bij inconsistente servicedeskdata.

## Inhoud van de notebook

De notebook bevat onder andere:

- Inladen en opschonen van tekstdata  
- Conversie van tekst naar numerieke kenmerken (TF-IDF)  
- Train-test-splitsing (80/20)  
- Logistic Regression-model voor afdelingsvoorspelling  
- Evaluatie met accuracy, precision, recall en F1-score  
- Confusion matrix en interpretatie  
- Drempelanalyse (thresholding) voor modelzekerheid  
- Output ter ondersteuning van de conclusies in het hoofdrapport  

**De code draait met:**

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

## Privacy & datagebruik

De dataset (incidentdata_ml.csv) bevat geen persoonsgegevens en is geanonimiseerd.
Alle analyses zijn uitsluitend gebruikt voor educatieve doeleinden binnen de leerlijn Data Science.

# Auteur

Steffan Boer – Bootcamp Data Engineer – 2025
