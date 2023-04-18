# Phonepe-Pulse-Data-Visualization-and-Exploration  ![MIT LICENSE](https://badgen.net//badge/license/MIT/green)   ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg)  
I have created a dashboard to visualize Phonepe pulse Github repository data(https://github.com/PhonePe/pulse) using Streamlit and Plotly in Python 

`Application Link:` https://shamhiruthik-phonepe-pulse-data-visualizati-pe-dashboard-42o1h7.streamlit.app/

`Demo Link:` 

## COMPONENTS OF DASHBOARD
    * GEO-VISUALIZATION
    * TRANSACTIONS ANALYSIS
    * USERS ANALYSIS
    * TOP STATES DATA
    
1 `Geo-Visualization:`
    The India map shows the Total Transactions of PhonePe in both state wide and District wide.It comes with zoom 
    option and on hover displays the content related to that particular state or district.The main 
    functions I have used to create this map are (User can give year and quarter input to show how the data changed over time)
    
    1 Plotlys scatter_geo for plotting districts along with the conent    
    
    2 Plotlys coropleth for drawing the states in India map    
    
2 `Transactions Analysis:`
    The Transactions data mainly contains the total Transactions count and total amount  in each state and 
district, I have used different graphs available in plotly to represent this data

    1 State-wise study
    The above bar graph shows the increasing order of PhonePe Transactions according to the states of India, 
    Here we can observe the top states with the highest Transaction by looking at graph
    
    2 District-wise study
    User can observe how transactions are happening in districts of a selected state.We can observe the 
    leading distric in a state
    
    3 Year-wise study   
    We can observe the states with total transactions in particular mode in the selected year
    
    4 Overall Analysis
    To show how the transactions drastically increased with time

3 `User Data Analysis:` 
    The Users data mainly contains the Registered Users count and App openings via different 
    mobile brands in each state and  district,I have used different graphs available in plotly 
    to represent this data

    1 State-wise study
    User can observe how the App Openings are growing and how Registered users are growing in a state
    
    2 District-wise study
    User can observe how App Openings are happening in districts of a selected state
    
    3 Year-wise study   
    User can observe the top leading brands in a particular state in given year
    
    4 Overall Analysis
    We can see that the Registered Users and App openings are increasing year by year
    
`4 Top States Data:`
    1 States with top Registered users
    2 States with top Total Amount Transacted
    3 States with highest Trabsactions count
    4 States with top app openings    


## Installation and Running
 
 open cmd:
1. > C:\Users\shamhiruthik> pip install virtualenv 
2. > C:\Users\shamhiruthik> virtualenv my_phonepe_env
3. > C:\Users\shamhiruthik> cd my_phonepe_env
4. > C:\Users\shamhiruthik\my_phonepe_env> cd Scripts
5. > C:\Users\shamhiruthik\my_phonepe_env\Scripts>activate                    # It will activate the virtual environment
6. > (my_phonepe_env)  C:\Users\shamhiruthik\> mkdir phonepe           #create a folder 
7. > (my_phonepe_env)  C:\Users\shamhiruthik\> cd phonepe              # download the above files from this repository and place inside this folder
8. > (my_phonepe_env)  C:\Users\shamhiruthik\phonepe> pip install -r requirements.txt       # it will install all the required modules in the environment
9. > (my_phonepe_env)  C:\Users\shamhiruthik\phonepe> streamlit run Pe_Dashboard.py   # Now run the app using streamlit
10. > You can now view your Streamlit app in your browser.
