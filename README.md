                                                                              🌍 IBJJF 2024 MAP 🥇

Interactive map with results from IBJJF 2024
Výstupem kódu je jednoduchá interaktovní mapa ve fotmátu html s počtem medaily v dospělých kategoriích z IBJJF (International Brazilian Jiu-Jitsu Federation) roku 2024 rozdělenych dle země zavodníků.

▶️ Spuštění v Google Colab

Klikni pro spuštění:  
[![Otevřít v Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kamilkucej/ibjjf2024map/blob/main/ibjjf2024map.ipynb)

*Nutno upravit bloky kody dle poznámek v kódu

### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###
# 🗺️ IBJJF 2024 MAP

Interaktivní vizualizace turnajů IBJJF (International Brazilian Jiu-Jitsu Federation) po celém světě v roce 2024. Pomocí knihoven **Dash**, **Plotly** a **Folium** zobrazuje mapa místa konání, datumy a další informace o jednotlivých turnajích.

## 📌 Obsah repozitáře

| Název souboru       | Popis                                               |
|---------------------|------------------------------------------------------|
| `ibjjf2024map.ipynb`| Hlavní Jupyter notebook s kódem a vizualizacemi     |
| `ibjjf_events.csv`  | Dataset s informacemi o turnajích (stažený z Kaggle)|
| `mapa.png`          | Náhled výstupu z interaktivní mapy                  |
| `README.md`         | Tento popisný soubor                                 |

## 🚀 Spuštění v Google Colab

Chceš si projekt vyzkoušet bez instalace? Otevři ho v Google Colabu:  
[![Otevřít v Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kamilkucej/ibjjf2024map/blob/main/ibjjf2024map.ipynb)

## 🧠 Hlavní funkce

- 🌍 Interaktivní mapa všech IBJJF turnajů v roce 2024  
- 📍 Zobrazení lokace, názvu, data a odkazu na web turnaje  
- 📊 Statistické vizualizace podle měsíců, kontinentů nebo zemí  
- 🔍 Možnost filtrování dle typu turnaje nebo regionu  
- 📦 Vizuální přehled pro sportovce, organizátory i fanoušky  

## 📊 Použitá data

- Dataset: [IBJJF 2024 Events – Kaggle](https://www.kaggle.com/) *(doplnit přesný odkaz na dataset, pokud je veřejný)*  
- Data byla ručně zkontrolována a předzpracována pro potřeby vizualizace  
- CSV obsahuje: název turnaje, datum a místo konání, kontinent, stát, město, URL turnaje, typ turnaje  

## ⚙️ Použité technologie a knihovny

- 🐍 Python 3.x  
- 📊 `pandas`, `plotly.express`  
- 🌍 `folium` – pro mapové vrstvy a interaktivní prvky  
- 📱 `dash` – pro vytvoření jednoduchého interaktivního webového dashboardu  
- 🖼️ `base64` – pro vkládání obrázků do mapy  

## 🧰 Jak projekt spustit lokálně

Naklonuj tento repozitář:  
# git clone https://github.com/kamilkucej/ibjjf2024map.git  
# cd ibjjf2024map  

Nainstaluj potřebné knihovny:  
# pip install pandas dash plotly folium  

Spusť notebook v Jupyteru nebo Google Colabu.

## 📈 Možná rozšíření

- Přidat časovou osu s možností posuvu v čase  
- Filtrace podle úrovně turnaje (Open, Nationals, Worlds...)  
- Export mapy jako interaktivní HTML  
- Přidání více jazykových mutací  
- Přímé napojení na IBJJF API (pokud existuje)  

## 🧑‍💻 Autor

**Kamil Kučej**  
GitHub: [@kamilkucej](https://github.com/kamilkucej)

## 💬 Kontakt

Máš dotaz, návrh nebo nápad?  
Napiš mi přes GitHub Issues nebo mě kontaktuj přes [LinkedIn](https://www.linkedin.com/) *(doplnit případně konkrétní odkaz)*

## 📄 Licence

Tento projekt je publikován pod licencí MIT.  
Volně použitelný pro osobní i vzdělávací účely.
