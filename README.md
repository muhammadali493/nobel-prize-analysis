# 📊 Nobel Prize Data Analysis

This notebook explores patterns and trends in Nobel Prize laureates using a dataset of past winners. The analysis focuses on gender, nationality, time periods, and notable individuals or organizations.

## 🧠 Key Questions Answered

1. **Top Gender and Country**
   - What is the most commonly awarded gender?
   - Which birth country has the most Nobel laureates?

2. **Decade-Based Insights**
   - Which decade had the highest **ratio** of US-born Nobel Prize winners to total winners?

3. **Female Representation**
   - In which **decade and Nobel Prize category** did female laureates make up the highest proportion?

4. **Historic First**
   - Who was the **first woman** to win a Nobel Prize, and in what category?

5. **Repeat Winners**
   - Which individuals or organizations have won **more than once**?

## 📁 Output Variables

- `top_gender`: Most commonly awarded gender.
- `top_country`: Country of birth with the most laureates.
- `max_decade_usa`: Decade with the highest ratio of US-born winners.
- `max_female_dict`: `{decade: category}` pair with the highest proportion of female laureates.
- `first_woman_name`: Name of the first female Nobel Prize winner.
- `first_woman_category`: Her prize category.
- `repeat_list`: List of individuals or organizations who won multiple Nobel Prizes.

## 📦 Dataset

The dataset used for this project consists of 18 columns containing details of Nobel Prize laureates, including:
- Winner names
- Prize categories
- Years awarded
- Gender
- Birth country


## 🛠️ Technologies Used

- Python 🐍
- Pandas 📊
- Jupyter Notebook 📓
