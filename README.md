# Analyse-Tool: Prüfungsarchiv (Statistische Auswertung)

Dieses Projekt analysiert ein Archiv aus 10 simulierten Prüfungen in einem Ausbildungsfach. Ziel ist es, **strukturelle Muster in Themen und Aufgabentypen** zu erkennen und diese für zukünftige Prüfungen auszuwerten.

Dabei werden alle Aufgaben aus strukturierten JSON-Dateien extrahiert, zusammengeführt und mithilfe von Diagrammen visualisiert.

---

## Background

Die Datengrundlage bilden 10 simulierte Prüfungen aus einem Prüfungsarchiv. Dabei wurde eine reale Originalprüfung systematisch in 10 Varianten überführt:

- Inhalte bleiben gleich, Aufgabenstellung variiert leicht (Abweichung ca. 20 %)
- Jede Variante simuliert typische Prüfungsformate

**Ziel:** Herausfinden, welche Themen und Aufgabentypen am häufigsten vorkommen – und daraus ableiten, was für die nächste Prüfung wahrscheinlich relevant ist.

---

## Projektstruktur

| Pfad                     | Beschreibung |
|--------------------------|--------------|
| `data/`                  | Enthält die JSON-Dateien der Prüfungsvarianten |
| `notebooks/`             | Analyse-Notebook (Jupyter) |
| `output/`                | Exportierte CSV-Dateien und ggf. Visualisierungen |
| `scripts/`               | Python-Helper für Vorverarbeitung oder Modelllogik |
| `requirements.txt`       | Paketliste für Python-Umgebung |
| `README.md`              | Diese Dokumentation |

---

## Anforderungen

```txt
pandas
matplotlib
seaborn
