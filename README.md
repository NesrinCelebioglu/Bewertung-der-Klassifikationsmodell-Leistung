# Bewertung des Klassifikationsmodells

Dieses Projekt zeigt die Bewertung eines Klassifikationsmodells anhand von Confusion Matrix und Leistungsmetriken.

## Inhalt

1. **Daten**  
   - Wahre Werte (`y_wahr`)  
   - Vorhersagewahrscheinlichkeiten (`y_vorhersage_proba`)  

2. **Modellvorhersage**  
   - Schwellenwert für Klassifizierung: 0.5  
   - Umwandlung der Wahrscheinlichkeiten in Klassenvorhersagen (0 = Kein Betrug, 1 = Betrug)  

3. **Confusionsmatrix**  
   - Berechnung der Confusionsmatrix mit `sklearn.metrics.confusion_matrix`  
   - True Positives (TP), False Negatives (FN), False Positives (FP), True Negatives (TN)  

4. **Leistungsmetriken**  
   - Genauigkeit (Accuracy)  
   - Erinnerung (Recall)  
   - Präzision (Precision)  
   - F1 Score  

5. **Visualisierung**  
   - Confusionsmatrix als Heatmap mit Matplotlib  

6. **Beispiel mit großen Datenwerten**  
   - Manuelle Confusionsmatrix-Werte:  
     - TP = 5, FN = 5, FP = 90, TN = 900  
   - Berechnung der Metriken für diese Werte  
