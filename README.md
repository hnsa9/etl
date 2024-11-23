# Credit Card Transaction ETL & Analysis

# Overview
The solution contains 2 main parts which is 
- Data Transformation 
    - Transform the data into tabular form from the JSON file and create additional columns
- Data Analytics & Visualization
    - Showcase insights and visualize findings from the dataset 

# Environment 
This solution was developed on
- Windows 10
- Python 3.9.13

# Pre-requisite
1. Install Java from https://www.java.com/download/ie_manual.jsp (dependency for Spark)
2. Install Python

# Setup 
1. Clone this repository 
    ```
    git clone https://github.com/hnsa9/etl.git
    ```
2. Create virtual environment (requires virtualenv package)
    ```
    python -m virtualenv venv 
    ```
3. Activate virtual environment 
    ```
    # Windows
    cd venv/
    cd Scripts/
    activate

    # Linux
    source/venv/bin/activate
    ```
4. Install Python dependencies
    ```
    pip install -r requirements.txt
    ```

5. If you are using VSCode, you can open ```etl.ipynb``` and select the 'venv' as kernel. After that, click on 'Run All' and you are done!

6. If you want to use Jupyter Notebook in a browser, run the command ```jupyter notebook```, go to the link given and open  ```etl.ipynb```