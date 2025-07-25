# 🌠 NASA Meteorite Landings Project

This project analyzes real-world meteorite landing data collected by NASA, using powerful Python libraries such as **pandas**, **matplotlib**, **seaborn**, and **folium**. The goal is to extract insights and visualize patterns in meteorite mass, year of fall, class types, and global landing locations.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `meteorite_landings.ipynb` | Jupyter Notebook containing the full project code and visualizations |
| `meteorite_landings.csv` | Dataset from NASA’s open data portal |
| `README.md` | This readme file explaining the project structure |

---

## 📊 Key Features

- ✅ **Data Cleaning**  
  - Drops null values in key columns
  - Filters records between years 860 and 2025  
  - Converts year column to integer format

- 📈 **Visual Analysis**  
  - Line plot of meteorite landings per year  
  - Histogram of meteorite masses (filtered to below 50kg)  
  - Bar chart of top 10 most common meteorite classes

- 🌍 **Interactive Map**  
  - Plots 500 random global landing sites on a Folium world map  
  - Red markers for large meteorites (> 50kg), blue for smaller

---

## 📷 Visual Previews

### Meteorite Landings Over Time  
![Landings Per Year](landings_per_year.png)

### Mass Distribution  
![Mass Distribution](mass_distribution.png)

### Top Meteorite Classes  
![Top Classes](top_classes.png)

### Global Landing Map  
![Map](map.png)
> An interactive Folium map displays meteorite landings across the globe.  
> (Live map in the notebook)

---

## 🧪 Technologies Used

- Python 3
- Jupyter Notebook
- `pandas`, `matplotlib`, `seaborn`
- `folium` (for interactive maps)

---

## 📌 Dataset Source

This dataset is publicly available at NASA’s Open Data Portal:  
🔗 [Meteorite Landings Dataset](https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh)

---

## ✅ How to Run This Project

1. Clone the repository or download the files
2. Open `meteorite_landings.ipynb` in Jupyter Notebook
3. Ensure `meteorite_landings.csv` is in the same directory
4. Run all cells to generate the plots and map

---

> 🎓 This project was developed as part of a data analysis capstone project using public datasets from NASA.
