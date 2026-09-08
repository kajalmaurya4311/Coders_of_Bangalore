# Coders of Bangalore: Data Parsing & Analysis
Welcome to the **Coders of Bangalore** project! This repository contains a simple yet powerful data extraction and analysis project that parses unstructured text data about various tech influencers, developers, and tech communities based in Bangalore (Bengaluru) and transforms it into structured JSON data for easy querying and analysis.
## Project Overview
The project takes raw, semi-structured data from social media profiles (like Instagram/Twitter) of Bangalore's tech ecosystem—including their username, post count, follower count, following count, page category, and bio. It cleans and processes this data, making it ready for insights.
### Key Highlights:
- **Data Parsing**: Converts unstructured text dumps (`finaldata.txt`) into a clean array of Python dictionaries.
- **Data Serialization**: Exports the cleaned data into `data.json`.
- **Data Analysis**: Answers key questions about the dataset using Python in a Jupyter Notebook environment.
##  Repository Structure
- `finaldata.txt`: The primary raw text file containing the profile dumps of various tech pages.
- `main.ipynb`: Jupyter Notebooks containing the parsing logic and data analysis.
- `data.json`: The final structured output of the parsed data.
- `initialdata.txt`: Initial sample of the raw dataset.
## Insights & Features
The Jupyter Notebook extracts interesting insights from the data, such as:
1. **Maximum Posts**: Identifying the profile with the highest content output.
2. **Maximum Followers**: Finding the most popular tech profile in the dataset.
3. **Maximum Following**: Finding the profile that follows the most people.
4. **Categories Count**: Grouping the profiles and finding the total number of unique page categories (e.g., Software Engineer, Media, Tech Creator, Community).
## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/kajalmaurya4311/Coders_of_Bangalore.git
   cd Coders_of_Bangalore
   ```
2. **Open the Notebook**:
   Ensure you have Jupyter Notebook installed.
   ```bash
   jupyter notebook
   ```
3. **Run the Analysis**:
   Open `main.ipynb` and execute the cells sequentially to see the parsing in action and the resulting insights.
## Tech Stack
- **Python 3.x**
- **Jupyter Notebook**
- **JSON** for data storage
## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

