# 🦖 PaleoVision Analytics
### Datenanalyse | Machine Learning | Power BI | Expeditionsplanung 2027

**IHK-Abschlussprojekt · Data Analytics**

Ein datengetriebenes Analyseprojekt, das historische Dinosaurier- und Fossilfunddaten mit Machine Learning und wirtschaftlicher Expeditionsplanung verbindet.

---

## 🎯 Projektziel

Welche Länder bieten interessante Voraussetzungen für zukünftige Fossilexpeditionen – und wie lässt sich ein begrenztes Budget sinnvoll einsetzen?

Um diese Frage zu beantworten, habe ich historische Funddaten analysiert, mit Python aufbereitet und anschließend ein interaktives Power-BI-Dashboard entwickelt.

Mein Ziel war es, wissenschaftliche Erkenntnisse und wirtschaftliche Entscheidungen in einer übersichtlichen Analyseumgebung zusammenzuführen.

## 🛠️ Technologien

| Technologie | Einsatz |
|---|---|
| Python | Datenprüfung und Datenbereinigung |
| Pandas | Datenaufbereitung und Qualitätskontrolle |
| Scikit-learn | Machine Learning mit Random Forest |
| Power BI | Dashboard und Datenvisualisierung |
| Power Query | Datenintegration und Transformation |
| DAX | Kennzahlen und dynamische Berechnungen |

## 📊 Datengrundlage

Für mein Projekt habe ich drei zentrale Datensätze verwendet:

| Datensatz | Umfang |
|---|---:|
| Dinosaurierdaten | 3.043 Einträge |
| Historische Fundstellen | 17.679 Einträge |
| Expeditionsbudget | 93 Einträge |

Die Daten enthalten unter anderem Informationen zu Dinosauriern, taxonomischen Rängen, Erdzeitaltern, geografischen Fundorten und Expeditionskosten.

## 🧹 Datenqualität und Aufbereitung

Die Datenprüfung und Bereinigung habe ich mit Python durchgeführt.

Zu den wichtigsten Herausforderungen gehörten:

- Fehlende Werte und unvollständige Datensätze
- Unterschiedliche Schreibweisen und Kategorien
- Unterschiedliche taxonomische Ränge
- Fundstellen ohne eindeutige Dinosaurierzuordnung
- Prüfung geografischer und wissenschaftlicher Angaben

Die bereinigten Daten bilden die Grundlage für mein Power-BI-Datenmodell.

## 🤖 Machine Learning – Random Forest

Mit einem Random-Forest-Klassifikator habe ich untersucht, welche Merkmale historischer Fossilfunde auf eine hohe Erhaltungsqualität hinweisen.

### Modellbewertung

| Kennzahl | Ergebnis |
|---|---:|
| Accuracy | 76,41 % |
| Precision | 56,21 % |
| Recall | 75,85 % |
| F1-Score | 64,57 % |
| Fehlerrate | 23,59 % |

Die Ergebnisse zeigen, dass mein Modell viele hochwertige Fossilfunde erkennt, gleichzeitig aber noch Verbesserungspotenzial bei der Zuverlässigkeit positiver Vorhersagen besteht.

**Wichtig:** Das Modell bewertet die Erhaltungsqualität anhand historischer Daten. Es garantiert keine zukünftigen Fossilfunde.



## 📊 Einblicke in mein Power-BI-Dashboard

![Dashboardseite 1](Dashboard_Screenshots/001.png)

![Dashboardseite 2](Dashboard_Screenshots/002.png)

![Dashboardseite 3](Dashboard_Screenshots/003.png)

![Dashboardseite 4](Dashboard_Screenshots/004.png)

![Dashboardseite 5](Dashboard_Screenshots/005.png)

![Dashboardseite 6](Dashboard_Screenshots/006.png)

![Dashboardseite 7](Dashboard_Screenshots/007.png)



## 📈 Power-BI-Dashboard

Mein Dashboard verbindet verschiedene Analysebereiche:

**Historische Funddaten**

Geografische Verteilung, Dinosauriergruppen, Erdzeitalter und wissenschaftliche Fundinformationen.

**Machine Learning und Fundqualität**

Analyse der modellbasierten Qualitätsbewertungen und Vergleich der Länder.

**Wirtschaftliche Bewertung**

Gegenüberstellung des geschätzten Fundpotenzials und der geplanten Expeditionskosten.

**Budget-Simulator 2027**

Interaktive Szenarien zur Auswahl und finanziellen Bewertung zukünftiger Expeditionen.

### Dashboard-Einblicke

Hier werden Screenshots der einzelnen Dashboardseiten eingebunden.

Die vollständige Power-BI-Datei ist aufgrund ihrer Dateigröße nicht im Repository enthalten. Die Screenshots dienen als visuelle Projektdokumentation.

## 🌍 Wissenschaftliche und wirtschaftliche Bewertung

Ein zentraler Bestandteil meines Projekts ist die Trennung zweier Bewertungen.

**ML-Score:** Bewertet die geschätzte Erhaltungsqualität historischer Fossilfunde.

**Wirtschaftlicher Score:** Berücksichtigt zusätzlich die Expeditionskosten und unterstützt die Priorisierung von Ländern.

Ein Land mit einer hohen modellbasierten Fundqualität muss nicht automatisch die wirtschaftlich beste Wahl sein.

Diese Unterscheidung ermöglicht eine differenziertere Expeditionsplanung.

## 💡 Erkenntnisse

- Historische Fundhäufigkeit und wirtschaftliche Attraktivität sind nicht gleichzusetzen.
- Datenqualität ist entscheidend für aussagekräftige Analysen und Modellbewertungen.
- Machine Learning kann Muster sichtbar machen, ersetzt aber keine wissenschaftliche Prüfung.
- Ein interaktiver Budget-Simulator macht finanzielle Auswirkungen unterschiedlicher Entscheidungen nachvollziehbar.

## 🚀 Fazit

Mit PaleoVision Analytics habe ich einen vollständigen Datenanalyseprozess umgesetzt – von der Datenprüfung und Bereinigung über Machine Learning bis hin zur interaktiven Visualisierung und Entscheidungsunterstützung.

Das Projekt zeigt, wie sich komplexe historische Daten in verständliche Analysen und konkrete Handlungsmöglichkeiten übersetzen lassen.

---

**Projektstatus:** IHK-Abschlussprüfung erfolgreich bestanden · Oktober 2026

**Schwerpunkte:** Data Analytics · Business Intelligence · Machine Learning · Data Visualization
