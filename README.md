# 🥋 Dashboard of Olympic Judo

## 📚 About Data
3 datasets of Olympic: 2024 Paris, 2020 Tokyo, 120 years of Olympic History datasets.

Dataset was extracted from [here](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)

Dataset was extracted from [here](https://www.kaggle.com/datasets/piterfm/tokyo-2020-olympics)

Dataset was extracted from [here](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

## 💡 Questions to ask
- Have shark attacks been increaseing or decreasing over the past 20 years?
- Which countries report the most shark attacks?
- What body parts are most often injured?
- What time of day are shark attacks most common?
- Which species of shark are attacking most often? Can you compare the last 3 days with top 3 species?

## ✏️ Data Wrangling
- Removed unnecessary columns
- Removed duplicate rows
- If Country, Area, and Location columns are all missing, then deleted the rows
- If unable to determine what Country it is by either Area or Location, deleted the rows
- Modified Year column using Case Number and Date columns. If 2 years were given (due to unsure of date), then averaged the year
- Missing values under Area, Location, Activity, and Sex columns were filled in as Unknown
- If anything other than number under Age column, they're Unknown. If 2 numbers were given, then averaged the age
- Missing values under Injury were filled in as Unknown. Cleaned the column as which body part was injured
- If anything other than time under Time column, they're Unknown. Cleaned the time into 2 digits (01, 02...)
- Missing values under Species, no species were given, "large" or "small" shark, only size given, they were filled in as Unknown

📍 Clean Data: [Olympic_Judo_cleaned.csv](https://github.com/andyalwaysok/Olympic-Judo-Dashboard/blob/main/clean_olympics_data.xlsx)

## 📊 Visualization

<img width="1000" alt="image" src=https://github.com/andyalwaysok/Olympic-Judo-Dashboard/blob/47ecad6125cfad9b7ee68f26d2f043b177c50534/Olympic%20Judo%20Dashboard.png>
