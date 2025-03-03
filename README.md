# 🎮 Video Game Sales Analysis  

## 📌 Project Overview  
This project analyzes **video game sales data** across different regions and consoles to uncover industry trends, regional preferences, and best-selling titles.  

The dataset includes:  
- **64,016 video game titles** from **1971 to 2024**  
- Sales data from **North America, Japan, Europe, Africa, and other regions**  
- Information on **genres, consoles, publishers, and critic scores**  

The goal of this analysis is to answer key questions about sales trends, console specialization, and regional popularity differences.  

---

## 📂 Dataset Description  
The dataset contains multiple attributes related to video game sales and metadata.  

### 🎮 Game Information  
Includes details such as:  
- **Title** – Name of the video game  
- **Genre** – Action, RPG, Sports, etc.  
- **Console** – Platform the game was released on (e.g., PS4, Xbox, Switch)  
- **Publisher & Developer** – Game creators  

### 🌎 Sales Data  
Region-specific sales figures (in millions of units):  
- **NA Sales** – North America  
- **JP Sales** – Japan  
- **PAL Sales** – Europe & Australia  
- **Other Sales** – Rest of the world  
- **Total Sales** – Sum of all regions  

### 📆 Release & Update Information  
- **Release Date** – When the game was launched  
- **Last Update** – Last recorded data update  

---

## 🛠 Data Preprocessing  
### ✅ Handling Missing Values  
- **Critic Score:** Dropped due to excessive missing values.  
- **Sales Columns:** Missing values were replaced with `0`, assuming no sales in that region.  
- **Release Date & Last Update:** Missing values were filled with each other's data when applicable.  

### 🔗 Data Aggregation  
- Summed total sales across different **consoles** for each game title.  
- Separated **regional sales** to identify popularity differences.  

---

## 📊 Exploratory Data Analysis (EDA)  
Conducted detailed **EDA & visualizations** to answer key industry questions:  
- ✅ **Which titles sold the most worldwide?**  
- ✅ **Which year had the highest sales? Has the industry grown over time?**  
- ✅ **Do any consoles specialize in particular genres?**  
- ✅ **What titles are popular in one region but flop in another?**  

### 📈 Key Insights  
- **Sales peaked in 2008** and began declining in **2011**.  
- Some consoles showed **strong genre preferences** (e.g., PlayStation → RPGs, Nintendo → Platformers).  
- Certain games performed **exceptionally well in one region** but struggled in others, which was measured using **sales variance and difference analysis**.  

---

## 🚀 Conclusion & Key Takeaways  
This project provided insights into **gaming trends, regional market preferences, and console specialization**.  

### 🔹 Key Skills Demonstrated  
- Data Cleaning & Preprocessing 🛠  
- Exploratory Data Analysis 📊  
- Data Visualization 📉  
- Sales Trend Analysis 🎮  

---

## 📌 Next Steps  
Future improvements could include:  
- Incorporating **player reviews** and **user ratings** for deeper insights.  
- Analyzing the **impact of marketing campaigns** on sales performance.  
- Predicting future **video game sales** using machine learning models.  

---

## 📬 Contact  
💡 Want to collaborate or discuss insights? Feel free to reach out! 🚀  
