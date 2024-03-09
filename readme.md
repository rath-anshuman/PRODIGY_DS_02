# Titanic Dataset Analysis

This project involves cleaning and analyzing the Titanic dataset, which contains information about passengers on the Titanic. The dataset has been processed through data cleaning and exploratory data analysis (EDA) to extract insights and patterns.

## Files

1. **titanic.csv:** The original dataset.
2. **titanic_cleaned.csv:** The cleaned dataset after handling missing values and unnecessary columns.
3. **EDA_Titanic.ipynb:** A Jupyter Notebook containing Python code for data cleaning and EDA.

## Steps Taken

### Data Cleaning

1. **Handling Missing Values:**
   * Imputed missing values for 'Age' with the mean.
   * Imputed missing values for 'Embarked' with the most common value.
   * Dropped unnecessary columns with a high percentage of missing values.

### Exploratory Data Analysis (EDA)

1. **Basic Statistics:**
   * Displayed basic statistics of numerical columns such as mean, standard deviation, etc.
2. **Distribution Visualizations:**
   * Visualized the distribution of passengers by class (Pclass) and gender (Sex).
   * Explored the distribution of passenger ages.
3. **Survival Analysis:**
   * Investigated the survival count based on class and gender.
4. **Fare Distribution:**
   * Explored the distribution of passenger fares.
5. **Correlation Matrix:**
   * Analyzed the correlation between numerical features.

## How to Use

1. **Clone the Repository.**
2. **Install Dependencies:**
   <pre><div class="dark bg-gray-950 rounded-md"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><span class="" data-state="closed"><button class="flex gap-1 items-center"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M12 3.5C10.8954 3.5 10 4.39543 10 5.5H14C14 4.39543 13.1046 3.5 12 3.5ZM8.53513 3.5C9.22675 2.3044 10.5194 1.5 12 1.5C13.4806 1.5 14.7733 2.3044 15.4649 3.5H17.25C18.9069 3.5 20.25 4.84315 20.25 6.5V18.5C20.25 20.1569 19.1569 21.5 17.25 21.5H6.75C5.09315 21.5 3.75 20.1569 3.75 18.5V6.5C3.75 4.84315 5.09315 3.5 6.75 3.5H8.53513ZM8 5.5H6.75C6.19772 5.5 5.75 5.94772 5.75 6.5V18.5C5.75 19.0523 6.19772 19.5 6.75 19.5H17.25C18.0523 19.5 18.25 19.0523 18.25 18.5V6.5C18.25 5.94772 17.8023 5.5 17.25 5.5H16C16 6.60457 15.1046 7.5 14 7.5H10C8.89543 7.5 8 6.60457 8 5.5Z" fill="currentColor"></path></svg>Copy code</button></span></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">pip install pandas matplotlib seaborn
   </code></div></div></pre>
3. **Run the Jupyter Notebook:**
   Open and run the `EDA_Titanic.ipynb` notebook in a Jupyter environment.
4. **Explore Insights:**
   Review the visualizations and analyses in the notebook to gain insights into the Titanic dataset.

## Usefulness

* **Decision Making:**
  * The analysis helps in making informed decisions based on patterns observed in the dataset.
* **Feature Engineering:**
  * Understanding the relationships between variables aids in feature selection or engineering for predictive modeling.
* **Data Visualization:**
  * Visualizations provide a clear understanding of the distribution of key features, aiding in effective communication of insights.
* **Further Analysis:**
  * The cleaned dataset and EDA results serve as a foundation for further statistical or machine learning analyses.
