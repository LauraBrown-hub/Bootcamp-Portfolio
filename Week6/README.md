# Bootcamp - Week 6
This is the Workbook for Week 6 from a course delivered by Just IT. The content focuses on fundamental programming logic and advanced data manipulation and analysis using Python and the Pandas library, often within a Jupyter Notebook environment.

## Key Topics and Skills Demonstrated

### Foundational Python Programming

**Logic and Control Flow**: Successfully implements the classic FizzBuzz problem using a `for` loop, `if`/`elif`/`else` statements, and the modulus operator (`%`) in Python, demonstrating proficiency in basic programming logic, iteration, and conditional statements.

### Advanced Data Wrangling with Pandas

This section demonstrates a comprehensive ability to manage and analyse tabular data using a `student.csv` dataset:

- **Data Loading and Inspection**: Reads a CSV file into a Pandas DataFrame and uses functions like `head()`, `info()`, and `describe()` to explore the data's structure, identify data types, and generate summary statistics.

- **Indexing and Slicing**: Efficiently selects specific columns (name, mark) and filters rows based on categorical criteria (e.g., selecting all rows where class is 'Four').

- **Feature Engineering & Manipulation**:
  - Creates a new calculated column (passed) using a Lambda function to indicate a pass/fail status based on a score threshold (mark >= 60).
  - Renames a column (mark to score) and drops a column (passed), demonstrating efficient DataFrame modification.

- **Aggregation and Grouping**: Uses the `groupby()` function to calculate and analyse descriptive statistics across different categories:
  - Calculates the mean score grouped by class.
  - Counts the number of students in each class.
  - Calculates the average score for each gender.

- **Advanced Analysis**:
  - Creates a pivot table to aggregate data, displaying the mean score by class (rows) and gender (columns).
  - Applies conditional logic to categorise students into letter grades ('A', 'B', 'C', 'D') using the `pd.cut()` function based on score ranges.
  - Sorts the DataFrame by score in descending order.

- **Data Visualisation and Export**: Creates basic visualisations (e.g., a bar chart of gender counts and a histogram of scores) using visualisation libraries (implied Matplotlib/Seaborn) and exports the final, processed DataFrame to a new CSV file (`Students_Updated.csv`).

### Real-World Data Application

Applies data exploration skills to a global dataset, loading the 'GDP (nominal) per Capita.csv' to analyse macroeconomic data, including selecting specific columns (Country/Territory and UN_Region) and inspecting the first 10 rows.

## Portfolio Value

This folder is a strong portfolio piece that showcases a comprehensive skillset in Python for Data Analysis, demonstrating the ability to handle a complete data lifecycle: from simple programming logic and environment setup to complex data transformation, statistical analysis, and producing actionable data summaries for stakeholders.
