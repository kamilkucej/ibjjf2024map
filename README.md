# 🌍 IBJJF 2024 MAP 🥇

Interactive map with results from IBJJF 2024
Výstupem kódu je jednoduchá interaktovní mapa ve fotmátu html s počtem medaily v dospělých kategoriích z IBJJF (International Brazilian Jiu-Jitsu Federation) roku 2024 rozdělenych dle země zavodníků.



## ▶️ Spuštění v Google Colab*

Klikni pro spuštění:  
[![Otevřít v Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kamilkucej/ibjjf2024map/blob/main/ibjjf2024map.ipynb)
                                    *Nutno upravit bloky kody dle poznámek v kódu


## 📖 Obsah repozitáře

| Název souboru             | Popis                                               |
|---------------------------------------|------------------------------------------------------|
| `ibjjf2024.ipynb`      | Hlavní Jupyter notebook s kódem pro analýzu dat z csv souboru a výstupem interaktivní mapy ve formátu html  |
| `results2024.csv`       | Dataset s informacemi o turnaji stažený z Kaggle viz. Použité data|
| `World-IBJJF-white.png`  | logo použité při vizualizaci                  |
| `ibjjf2024_map.html`     | Jednoduchá nteraktivní mapy, jenž je výstupem kodu |
| `README.md`               | Tento textový soubor s popisem                        |


## 📊 Použitá data

- Dataset: [World Jiu-Jitsu IBJJF Championship 2024 Results – Kaggle](https://www.kaggle.com/datasets/oliveiraricardotech/world-jiu-jitsu-ibjjf-championship-2024-results)
- Data byla ručně zkontrolována a předzpracována pro potřeby vizualizace
- Z důvodu vetší přesnosti byly země zavodníků dohledávany ručně

## ⚙️ Použité technologie a knihovny

- Python 3.11  
- `pandas`, `plotly.express` - základní knihovny pro manipulaci s daty a vizualizaci
- `dash` – pro vytvoření jednoduchého interaktivního webového dashboardu  
- `base64` – pro vkládání obrázků do mapy
- `folium` – pro mapové vrstvy a interaktivní prvky   

## 🧰 Jak projekt spustit lokálně

Naklonuj tento repozitář:  
git clone https://github.com/kamilkucej/ibjjf2024map.git  
cd ibjjf2024map  

Nainstaluj potřebné knihovny:  
pip install pandas dash plotly folium  

Spusť notebook v Jupyteru nebo Google Colabu. 

## 📄 Licence

Tento projekt je publikován pod licencí MIT.  
Volně použitelný pro osobní i vzdělávací účely.

## 🧑‍💻 Autor

**Kamil Kucej**  
GitHub: [@kamilkucej](https://github.com/kamilkucej)
