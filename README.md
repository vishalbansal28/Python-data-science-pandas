## Sales Data Analysis

This project analyzes sales data from a fictional online store to extract insights and inform business decisions.

**Data:**

* The data is stored in a directory named "Sales_Data" containing multiple CSV files, each representing sales data for a particular month. 
* Each CSV file contains the following columns:
    * `Order ID`: Unique identifier for each order.
    * `Product`: Name of the product purchased.
    * `Quantity Ordered`: Number of units of the product ordered.
    * `Price Each`: Price of each unit of the product.
    * `Order Date`: Date and time of the order.
    * `Purchase Address`: Delivery address for the order.

**Analysis:**

The project performs the following steps:

1. **Data merging:** Combines all monthly sales data into a single CSV file.
2. **Data cleaning:** Removes irrelevant rows, converts data types, and adds derived columns like:
    * `Month`: Month of the order.
    * `City`: City of the delivery address.
    * `Hour`: Hour of the order.
3. **Exploratory data analysis:** Answers key questions about the sales data:
    * What was the best month for sales? How much was earned that month?
    * What city sold the most product?
    * What time should we display advertisements to maximize likelihood of customer's buying product?
    * What products are most often sold together?
    * What product sold the most? Why do you think it sold the most?
4. **Data visualization:** Creates bar charts and plots to represent the findings visually and make the insights clear.

**Tech Stack:**

* **Python:** Programming language used for the analysis.
* **pandas:**  Library for data manipulation and analysis.
* **os:** Library to interact with the file system.
* **matplotlib.pyplot:** Library for creating visualizations.

**Running the code:**

1. Ensure you have the required Python libraries installed (`pip install pandas matplotlib`).
2. Place the "Sales_Data" directory in the same directory as the Python script.
3. Run the Python script.
4. The script will generate the following outputs:
    * A consolidated CSV file named "all_data_copy.csv".
    * Plots and visualizations showing the key findings.
