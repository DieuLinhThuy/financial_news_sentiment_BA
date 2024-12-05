Thema der Bachelorarbeit: Sentimentanalyse von „Der Aktionär“-Artikeln und nachgelagerte Korrelationsanalyse der Aktienperformance

Name: Thuy Dieu Linh, Nguyen

Matrikelnummer: 11147085

### `get_data.ipynb`
- Dieses Jupyter Notebook extrahiert Aktiennamen, Heftnummern und Seitenzahlen aus den Artikeln von „Der Aktionär“.
- Die Ergebnisse dienen als Grundlage für die manuelle Extraktion und werden in einer strukturierten Form gespeichert (z. B. `stock_data`).

### `sentiment_analysis.ipynb`
- Führt die Sentimentanalyse der extrahierten Artikel durch.
- Implementiert sowohl lexikonbasierte Ansätze (z. B. SentiWS und BPW-Lexikon) als auch maschinelle Modelle (German FinBERT) zur Stimmungsbewertung.
- Ermöglicht die Analyse und Klassifikation von Sentiments in Kategorien wie positiv, neutral und negativ.

### `correlation.ipynb`
- Fokussiert sich auf die Analyse der Korrelation zwischen den Sentiments der Artikel und der Aktienperformance.
- Nutzt statistische Methoden wie Rolling-Window-Verfahren und Detrended Cross-Correlation Analysis (DCCA), um Zusammenhänge und Trends zu identifizieren.
- Hinweis: Die in diesem Projekt erstellten Diagramme mit Plotly können nicht direkt auf GitHub als interaktive Grafiken angezeigt werden. Stattdessen sind sie als PNG-Dateien exportiert und sind im Ordner `visualisations` verfügbar

# Lizenz und Nutzung
Dieses Notebook verwendet die [Fathon-Bibliothek](https://github.com/stfbnc/fathon), die unter der GNU General Public License v3.0 (GPL-3.0) lizenziert ist. 

Der hier implementierte Teil zur Detrended Cross-Correlation Analysis (DCCA) unterliegt den Bedingungen der GPL v3.0. Weitere Informationen zur Fathon-Bibliothek sind hier zu finden: (https://github.com/stfbnc/fathon)
