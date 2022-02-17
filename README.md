# Vorhersage_Immobilienpreise
Basierend auf neun Features soll der mittlere Immobilienpreis eines Bezirks vorhergesagt werden (Regression)
Features: Längen- & Breitengrad; mittleres Alter; Anzahl von Räumen & Schlafzimmern; Population; Haushalte; mittleres Einkommen; Oceannähe; mittlerer Preis (Label)
1) Testdatensatz trennen
2) Daten visualisieren, nach Korrelationen suchen, kategorische/ numerische Features, fehlende Werte, ...
3) Label-Werte, welche zu häufig vorkommen, entfernen
4) Feature-Engineering: Aussagekräftigere Merkmale erstellen
5) Kategorische & numerische Merkmale getrennt behandeln & in richtige Form bringen (numerisch -> 0-1)
6) Pipelines verwenden, um die Testdaten in ihrer normalen Form vorhersagen zu können
7) Mehrere Modelle testen (LinReg, SVM, RandomForestReg., GradientBoostingReg., NN), inkl. Hyperparametertuning
8) Vielversprechendste Modelle mit den besten Parametern erstellen & zur Pipeline hinzufügen
9) Beste Modelle testen (RandomForestReg, GradientboostingReg., Ensemble aus beiden, NN) 
