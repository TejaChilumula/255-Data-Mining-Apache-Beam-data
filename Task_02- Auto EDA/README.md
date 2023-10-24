# 📚 Power of Sweetviz ( AutoML ) in building an EDA on Book dataset 📊

## 📖 Overview
This repository contains an exploratory data analysis (EDA) of a book dataset using the Sweetviz library. 📈 Sweetviz is an open-source Python library that creates beautiful, high-density visualizations for a quick and easy EDA.

## 📄 Dataset
The dataset features information on over 11,000 books 📚, providing details such as title, authors, average rating, ISBN numbers, language codes, number of pages, publication dates, and publishers.

## ✨ Analysis Highlights

- **General Overview**: The dataset comprises 11,123 books with 12 distinct features. These features are a mix of categorical, numerical, and text-based attributes. 📑
   
- **Unique Identifiers**: Both `bookID` and the `isbn` & `isbn13` numbers act as unique identifiers for books. 🔑 They play a pivotal role in ensuring data integrity.
   
- **Diversity in Titles and Authors**: About 93% of books have unique titles, and around 60% have unique authors. 🖋 Some prolific authors, like Stephen King, have multiple entries, suggesting different editions or a vast bibliography.
   
- **Language Distribution**: A significant portion of the dataset (80%) comprises books written in English 🇬🇧🇺🇸. However, the dataset also represents a myriad of other languages 🌍.
   
- **Publication Patterns**: The dataset offers a temporal view of book publications 🗓. Some specific dates see a surge in book releases, suggesting possible trend patterns in the publishing world.
   
- **Ratings and Reviews**: The average rating across books is close to 4 out of 5 ⭐. There's a strong correlation between the number of ratings a book has and the number of text reviews it has received.
   
- **Prominent Publishers**: The dataset showcases several well-known publishers 🏢, with entities like Vintage, Penguin Books, and Penguin Classics leading the charge.

## 🛠 Visualization Tool: Sweetviz
Sweetviz was chosen for this EDA due to its capability to generate insightful visualizations swiftly. The library compares and visualizes datasets, drawing out patterns and relationships between features. The report generated is interactive and provides a comprehensive overview of the data distribution, comparisons, and associations.

## 🔍 Usage
To view the Sweetviz report, you can open the `sweetviz_report.html` file in a web browser 🌐. It provides an interactive and detailed visualization of the dataset.

## 🚀 Future Scope
This EDA serves as an initial step in understanding the dataset. Further analyses can delve deeper into author-specific trends, genre classifications 📖, and potential predictive modeling to forecast book ratings based on various features.

