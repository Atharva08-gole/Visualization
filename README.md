# 📊 Netflix Data Visualization & Insights

This project performs **Exploratory Data Analysis (EDA)** and **visualization** on a Netflix dataset to understand trends in movies and TV shows, popular release countries, content ratings, and movie duration patterns.

All analysis is done inside a Jupyter Notebook:  
**`Netflix visualization.ipynb`**

## 📁 Project Structure
```
Netflix-Visualization/
│── Netflix visualization.ipynb
│── Netflix.csv
│── README.md
│── /images
      ├── type_comparison.png
      ├── top_countries.png
      ├── movie_duration.png
      ├── tv_rating_pie.png
      ├── release_year_scatter.png
```

## 🎯 Project Objectives
- Compare number of Movies vs TV Shows on Netflix  
- Identify top countries producing Netflix content  
- Analyze movie duration distribution  
- Visualize TV ratings spread  
- Observe relationship between release year and content volume  
- Generate useful insights for content patterns

## 📊 Visualizations

### **1️⃣ Movies vs TV Shows**
Movies dominate the dataset with nearly **double** the count of TV Shows.

### **2️⃣ Top 10 Countries by Content Release**
The United States is the most frequent producer of Netflix content, followed by **India**, **Japan**, and the **UK**.

### **3️⃣ Movie Duration Analysis**
Most Netflix movies fall in the **85–120 minute** range.  
Very few exceed 150+ minutes.

### **4️⃣ TV Show Ratings Distribution**
Common ratings include:
- **TV-MA**  
- **PG-13**  
- **R**  
- **TV-14**

### **5️⃣ Release Year vs Number of Shows**
Content releases significantly increased after **2000**, peaking around **2020**.

## 🛠️ Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Netflix-Visualization.git
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the notebook:
   ```bash
   jupyter notebook "Netflix visualization.ipynb"
   ```

## 📈 Key Insights Summary
- 📌 Movies are more common than TV shows  
- 📌 USA leads in producing Netflix content  
- 📌 Most movies range between 90–120 minutes  
- 📌 TV-MA is the most popular rating  
- 📌 Release counts increased massively after 2010  

## ⭐ Future Improvements
- Add genre-wise visualizations  
- Analyze actor/director frequency  
- Add dashboards (Streamlit/Power BI)  
- Sentiment analysis of descriptions  

## 🤝 Contributing
Pull requests and improvements are welcome.

## 📜 License
This project is open-source.
