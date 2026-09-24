Wilkommen zu meinem ersten eigenen Portfolioprojekt! Dieses Projekt dient dazu meine erworbenen Data / Business Analysis Fähigkeiten zu vertiefen und zu demonstrieren.

## Inhaltsverzeichnis
- [Projektüberblick](#projektüberblick)
- [Projektübersicht](#projektüberblick)
- [Projektstruktur](#projektstruktur)
- [Voraussetzungen](#voraussetzungen)
- [Verwendete Technologien und Bibliotheken](#verwendete-technologien-und-bibliotheken)
- [Explorative Datenanalyse (EDA)](#explorative-datenanalyse-eda)
- [Ausführlicher Projektbericht mit allen Power BI Visuals](#Ausführlicher-Projektbericht-mit-allen-Power-BI-Visuals)
- [Wichtigste Erkenntnisse aus dem Projekt für mich selbst](#Wichtigste-Erkenntnisse-aus-dem-Projekt-für-mich-selbst)

## Projektüberblick
**Analyse des UCI Online-Retail II Datensatzes**
https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data

> Ich analysiere hier einen Datensatz über 1 Millionen Transaktionen über 2 Jahre eines britischen Online-Händlers. Dieses Projekt beinhaltet die Datenbeschaffung, Datenvorverarbeitung, explorative Datenanalyse und Modellierung.

## 📊 Projektübersicht

**Problemstellung:** 
Der Datensatz besteht aus sehr vielen Zeilen, hat jedoch nur wenig Spalten (8), wovon nur 2 numerisch sind. Aus der fülle an Informationen sollen Erkenntnisse gewonnen werden, wo sich der Händler entwicklungstechnisch befindet und wie die Kundenlandschaft aussieht

**Ziel:** 
Überblick erschaffen, wie sich das Unternehmen in den 2 Jahren positioniert hat. Wieviel Umsatz, wieviel Verkäufe,  wieviele Kunden gab es zu welchem Zeitraum. Eine RFM - Analyse (Recency (Zeitpunkt des letzten Kaufs), Frequency (Kaufhäufigkeit), Monetary Value (Umsatz)) duchführen. Jeden Kunden anhand dieser drei Variablen Punkte zuordnen, um sie in unterschiedliche Gruppen zu segmentieren. Aus den Erkenntnissen lassen sich Strategien überlegen, ob (potenziell) wichtige Kunden (noch) stärker an uns zu binden. 


**Methoden:** 
Zuerst habe ich mir einen groben Überblick der Daten mit Python verschafft. Danach habe ich die Daten untersucht und bereinigt. Für die Visualisierung habe ich die bereinigten Daten bei Power BI importiert und dort meine letztendliche Präsentation vorbereitet.

## Projektstruktur
Die Projektstruktur ist wie folgt organisiert:

```
UCI-Online-Retail-II/
├── images/
├── data/
├── .gitignore
├── .python-version
├── 2026-09-24-online_retail_analyse.ipynb
├── pyproject.toml
├── README.md
├── report.md
└── uv.lock
```
- **`images/`**: Ordner für die Visuals/Charts
- **`data/`**: Ordner für die heruntergeladenen Datensätze.
- **`.gitignore`**: Definiert, welche Dateien von der Versionskontrolle ausgeschlossen werden.
- **`.python-version`**: Spezifiziert die Python-Version (>=3.14).
- **`2026-09-24-online_retail_analyse.ipynb`**: Notebook zu meiner ersten Analyse
- **`pyproject.toml`**: Projektkonfigurationsdatei mit Abhängigkeiten.
- **`README.md`**: Diese Dokumentation.
- **`report.md`**: Power BI Visuals, sowie eine kurze Textpräsentation.
- **`uv.lock`**: Lock-Datei für den Paketmanager uv.



## Voraussetzungen
- **Python:** Stellen Sie sicher, dass Sie Python Version 3.13 oder höher installiert haben.
- **uv:** Installieren Sie uv gemäß den Anweisungen auf der offiziellen GitHub-Seite: [uv on GitHub](https://github.com/astral-sh/uv)


## Verwendete Technologien und Bibliotheken

- **Python 3.14.6**: Programmiersprache.
- **uv**: Paketmanager für Python.
- **Jupyter Notebook**: Interaktive Entwicklungsumgebung.
- **Pandas**: Datenanalyse und -manipulation.
- **NumPy**: Numerische Berechnungen.
- **Matplotlib & Seaborn**: Datenvisualisierung.
- **Statsmodels**: Statistische Modellierung.

## Explorative Datenanalyse (EDA)
Öffnen Sie das Notebook **`2026-09-24-online_retail_analyse.ipynb.ipynb`** in VS Code oder Jupyter und führen Sie es aus, um eine Analyse des Datensatzes durchzuführen bzw nachzuvollziehen.

## Ausführlicher Projektbericht mit allen Power BI Visuals
Öffnen Sie die **`report.md`**, um zu meiner Online-Präsentation zu gelangen.

## Wichtigste Erkenntnisse aus dem Projekt für mich selbst
Es lohnt sich von Anfang an strukturiert zu arbeiten und sauber zu dokumentieren. Ich habe das bis zum Ende geschoben und habe dadurch wahrscheinlich ineffizienter gearbeitet.