Doelstelling
Wire Solutions kent een aanzienlijk aantal incidenten waarbij de hoofdafdeling ontbreekt. Met behulp van eenvoudige tekstclassificatie (TF-IDF + Logistic Regression) is onderzocht of deze ontbrekende afdelingen alsnog betrouwbaar voorspelbaar zijn.
De onderzoeksvraag luidde:
"In hoeverre kan een machine-learningmodel op basis van incidentbeschrijvingen voorspellen bij welke afdeling een incident hoort?"
Gebruikte methode
Resultaten (samengevat)
* Accuracy: ±40%
* F1-score: laag (±0.22) door overlappende tekstpatronen
* De meeste afdelingen zijn tekstueel nauwelijks onderscheidend
* Hogere drempels vergroten betrouwbaarheid, maar:
o Bij 0.60 blijft <3.1% van de voorspellingen over
o Bij 0.80 blijft <0.36% over
Belangrijkste conclusie
Het model kan onvoldoende onderscheid maken tussen afdelingen op basis van de beschikbare tekst. De voorspellingen zijn daardoor niet bruikbaar voor het verrijken van de dataset.

