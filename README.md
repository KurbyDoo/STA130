# Homework Repository for the University of Toronto STA130 course during the year 2024
This repository contains homework assignments for the STA130 Statistics course. The homework assignments are designed to provide you with hands-on experience in applying statistical concepts and coding techniques introduced in the lectures and tutorials.

**Key Features of Homework in this Repository**

*   **Organized by Week:** Each weekly module will have its own dedicated folder (e.g., `Week-01`, `Week-02`, etc.) to maintain a clear structure.
*   **Jupyter Notebooks:** Homework will primarily involve coding and written responses within Jupyter Notebook files (`.ipynb`). Each week's folder will contain a notebook file for that week's assignments (e.g., `Week-01/STA130F24_HW01.ipynb`).
*   **ChatBot Interaction Summaries:** As a core element of the course, you are required to engage with ChatBots like ChatGPT or Copilot during your homework.  Each notebook will include dedicated sections to document your interactions.
    *   **Summary of Exchanges:**  Conclude each ChatBot session by prompting it for a concise summary of your interaction to paste into your notebook. For example:  "Please provide a summary of our exchanges here so I can submit them as a record of our interactions as part of a homework assignment."
    *   **Final Code Versions:** Similarly, request the ChatBot to provide the final working version of any code you developed collaboratively. For example: "Please provide me with the final working version of the code that we created together".
    *   **ChatGPT Log Links (If Applicable):** Include links to your ChatGPT chat log histories for traceability and reference. 
*   **Clear and Concise Explanations:**  While code is essential, demonstrating your understanding of the statistical concepts and your reasoning behind decisions is crucial.  Provide clear written explanations within markdown cells in the notebooks.
*   **Error Handling and Troubleshooting:**  The sources emphasize learning from coding errors. Document instances where you encountered errors, how you used ChatBots or other resources to troubleshoot, and the solution you implemented. This process of error handling and resolution is a valuable learning experience.

### Course Description: Statistics with ChatBots
This Statistics course provides a hands-on approach to learning data analysis techniques using Python, integrating ChatBots as a supplemental learning tool throughout.  The course emphasizes the development of practical skills applicable to real-world data analysis scenarios.

### **Course Objectives**

Upon completion of this course, students will be able to:

*   Import and clean data using Python's pandas library, handling missing values and understanding data types.
*   Summarize and visualize data to gain insights into its characteristics and identify potential patterns.
*   Apply fundamental statistical concepts, including probability distributions, sampling distributions, and hypothesis testing.
*   Conduct simple linear regression analysis to model relationships between variables.
*   Effectively communicate statistical findings through clear and concise writing.
*   Utilize ChatBots, such as ChatGPT and Copilot, as interactive learning aids for troubleshooting, code exploration, and deepening their understanding of statistical concepts.

### **Course Structure**

The course is organized into weekly modules, each focusing on a specific theme within data analysis.

1.  **Week 01: Data Summarization**

    *   Introduces the basics of working with data in Python, including importing data from CSV files using `pd.read_csv()`, handling missing data (`df.isna().sum()`), and examining data structure (`df.shape`, `df.columns`).
    *   Covers summarizing numeric data using `df.describe()` to obtain descriptive statistics such as mean, standard deviation, quartiles, and identifying data types using `df.dtypes`.
    *   Explores summarizing categorical data with `df.value_counts()` to understand the frequency distribution of categories.
    *   Introduces sorting data (`df.sort_values()`) and selecting specific rows and columns using indexing (`df.iloc[]`, `df.loc[]`) based on position and conditional statements.
2.  **Week 02: Coding**

    *   Focuses on core Python programming concepts essential for data analysis, including data types like tuples, lists, dictionaries, and NumPy arrays (`np.array`).
    *   Covers using loops (`for`, `while`) for iterative tasks and conditional statements (`if`, `else`, `elif`) for controlling program flow.
    *   Introduces error handling using `try-except` blocks to manage potential runtime issues.
3.  **Week 03: Data Visualization**

    *   Explores different types of data (continuous, discrete, nominal, ordinal, binary) and appropriate visualization techniques for each.
    *   Covers creating informative visualizations using libraries like matplotlib, seaborn, and plotly.
    *   Includes bar plots for categorical data, histograms for visualizing the distribution of numerical data, and box plots for displaying summary statistics and identifying outliers.
    *   Addresses concepts like skew (asymmetry of data), multimodality (multiple peaks in the distribution), and normality (bell-shaped distribution).
4.  **Week 04: Bootstrapping**

    *   Introduces the concept of simulation in statistics and its applications in estimating uncertainty.
    *   Covers generating random samples from data (`df.sample()`) and theoretical distributions using the `scipy.stats` module.
    *   Explores the sampling distribution of the mean and how it relates to the standard error.
    *   Introduces the concept of confidence intervals and how to construct them using bootstrapping techniques.
5.  **Week 05: Hypothesis Testing**

    *   Covers formulating null and alternative hypotheses to test specific claims about populations.
    *   Explores the process of hypothesis testing, including determining p-values and interpreting their significance.
    *   Distinguishes between one-sided and two-sided hypothesis tests and when each is appropriate.
    *   Explores different types of hypothesis tests, including one-sample, paired-sample, and two-sample tests.
6.  **Week 06: Simple Linear Regression**

    *   Introduces the concept of correlation as a measure of the linear association between two variables.
    *   Covers building simple linear regression models to predict a continuous outcome variable based on a single predictor variable.
    *   Explores interpreting the coefficients of the regression model, including the slope and intercept.
    *   Introduces assessing model fit using metrics like R-squared and understanding the assumptions of linear regression.

### **ChatBot Integration**

ChatBots, such as ChatGPT and Copilot, are integrated into the course as supplementary learning tools. Students are encouraged to interact with these ChatBots to:

*   Troubleshoot coding errors by providing error messages and seeking guidance on resolving them.
*   Explore and understand Python code by asking questions about specific functions or methods.
*   Gain different perspectives on statistical concepts by prompting the ChatBot with conceptual questions.
*   Practice effective communication by formulating clear and concise prompts and interpreting the ChatBot's responses.

### **Important Notes**

*   While ChatBots can be valuable tools, students are cautioned against relying on them to complete assignments or provide direct answers. The emphasis is on using ChatBots to guide understanding and develop independent problem-solving abilities.
*   Effective communication is crucial in statistics and data science. The course emphasizes clear and concise writing when summarizing findings, interpreting results, and communicating statistical insights.
*   Students are encouraged to actively participate in class discussions, seek help from the instructor and teaching assistants when needed, and collaborate with peers to foster a supportive learning environment.

This course aims to provide students with a strong foundation in data analysis techniques using Python, enabling them to tackle real-world data challenges with confidence.
