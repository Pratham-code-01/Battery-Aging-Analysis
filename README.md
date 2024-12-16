# NASA Battery Impedance Analysis #
### Project Overview
This project analyzes the NASA Battery Dataset, focusing on the evolution of key impedance parameters (__Re__ - Electrolyte Resistance and __Rct__ - Charge Transfer Resistance) over time as batteries age through repeated charge-discharge cycles. The data is visualized interactively using Plotly, providing insight into the degradation of battery performance.

### Key Features
+ ___Data Parsing___ : Extracts and preprocesses metadata for impedance measurements.
+ ___Time-Series Visualization___ : Plots __Re__ and __Rct__ changes over time for each battery.
+ ___Average Impedance Calculations___ : Reads individual data filesm computes avaerage battery impedance and visualizes its trend over time.
+ ___Interactive Plots___ : Enables zooming, plaining and detailed exploration of data using Plotly.

### Installation and Setup
1. __Clone the repository__\
Start by cloning the repository to your local machine:
    ```
    git clone <repository_link>
    cd project_name
    ```

2. ___Set up the environment___\
Create and activate a virtual environment:
    ```
    python3 -m venv venv
    source venv/bin/activate    #For Mac
    venv\Scripts\activate   #For Windows
    ```

3. ___Install dependencies___\
Install the required Python libraries:
    ```
    pip install -r requirements.txt
    ```

    The requirements.txt file includes the necessary libraries for this project, such as:
    ___numpy
    pandas
    plotly___

### Run the Code
+ Run the script using
    ```
    python script/battery_aging_analysis.ipynb
    ```



Let me know if you need any changes or additional details added!


## Credits
- ### Developer : Pratham Sharma