# 🚢 Titanic Dataset Power BI Project 🚢   

---

## 🎯 **Objective**  
To clean, transform, and analyse the Titanic dataset using Power BI, uncovering insights about passenger demographics, survival rates, and embarkation points, all while creating an interactive and visually appealing report.  

---

## 📖 **Dataset Overview**  
The dataset includes information about Titanic passengers, such as:  
- 🎫 **Passenger Class (Pclass)**: 1st, 2nd, or 3rd class.  
- 👩‍👩‍👦 **Family Size**: Number of family members traveling together.  
- 🌍 **Embarkation Point**: Southampton, Queenstown, or Cherbourg.  
- 💰 **Fare**: The ticket price (in 1912 GBP).  
- 🧓 **Age**: Passenger's age.  

---

## 🧹 **Data Cleaning and Transformation**  
Using Power Query Editor, I turned the raw data into something beautiful! 🧽✨  

### Key Steps:  
1. **Fixed Data Types** 🛠️  
   Ensured each column had the correct data type (e.g., numbers, text).  

2. **Renamed and Transformed Columns** ✏️  
   - Replaced values in the `Survived` column with "Deceased" and "Survived."  
   - Updated `Pclass` values to "1st," "2nd," and "3rd."  

3. **Added New Features** 🔧  
   - Created a **Family Size** column by combining `SibSp` and `Parch` with a +1 (to include the passenger themselves).  

4. **Cleaned Up Embarkation Data** 🚢  
   - Transformed `Embarked` values:  
     - "C" → "Cherbourg"  
     - "S" → "Southampton"  
     - "Q" → "Queenstown"  

5. **Split Columns** ✂️  
   - Split the `Name` column into **Surname** and **Title** for deeper analysis.  

6. **Handled Missing Values** ❌  
   - Removed rows with null values in the `Embarked` column.  

7. **Removed Unnecessary Columns** 🗑️  
   - Dropped the `Cabin` column due to excessive missing data.  

---

## 🎨 **Report Creation**  
After cleaning the data, I built some awesome visuals!  

### **Visual 1: Passenger Demographics** 🧍‍♂️🧍‍♀️  
- **Pie Chart**: Gender distribution of passengers.  
- **Bar Chart**: Class distribution (1st, 2nd, 3rd).  

### **Visual 2: Survival Analysis** 🩺  
- **Bar Chart**: Survival rates (Survived vs. Deceased).  

### **Visual 3: Embarkation Points** 🌍  
- **Treemap**: Visualized the number of passengers by embarkation point.  
- Filtered to show only passengers who survived.  

### **Additional Visual** 🎉  
- Added a **custom visual** a stacked bar chart to show passenger survival by gender.  
- Styled with custom colors and formatting for a polished look.  

---

## 🌟 **Features and Insights**  
- **Interactive Filters**: Explore survival rates, demographics, and embarkation points dynamically.  
- **Easy Navigation**: Clean layout with a title and consistent formatting.  
- **Publishing to Power BI Service**: Made my report accessible online for sharing and feedback.  

---

## 📸 **Screenshots**  
### Gender Distribution Pie Chart  
![image](https://github.com/user-attachments/assets/c858e511-8f95-432f-9744-358aa1332db9)

### Class Distribution Bar Chart  
![image](https://github.com/user-attachments/assets/fc7d98c2-efc0-46cd-b291-0ef18906b2d0)

### Survival Rate Bar Chart  
![image](https://github.com/user-attachments/assets/349f8980-4233-4758-957b-f070613eeed5)
  
### Embarkation Points Treemap  
![image](https://github.com/user-attachments/assets/7675e6ca-a4e8-4827-aa67-e18ae89556a5)

---

## 📝 **Reflections**  
Working on this project was an absolute blast! 🎉 Here’s what I learned:  
- 🧹 **Data Cleaning**: How to handle messy data and transform it into something usable.  
- 📊 **Visualisation Skills**: Crafting visuals that are both informative and engaging.  
- 🚀 **Power BI Service**: Publishing reports and sharing insights seamlessly.  

---
