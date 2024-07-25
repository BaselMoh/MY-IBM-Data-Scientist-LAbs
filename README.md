
![Uploading Capture.PNG…]()

This project aims to develop a machine learning pipeline to predict the success of SpaceX's Falcon 9 rocket landings. By achieving a high success rate, the project seeks to enable Space Y to offer competitive services and reduce launch costs significantly.

Methodology
The data collection involved two primary methods

API Requests: Data was collected from SpaceX's API.
Web Scraping: Additional data was obtained from Wikipedia using BeautifulSoup.

The data underwent extensive wrangling, including handling missing values and applying one-hot encoding to categorical features. Exploratory Data Analysis (EDA) was performed using visualization techniques and SQL queries to uncover insights. Interactive visual analytics were created using Folium and Plotly Dash. Finally, predictive models were developed using various classification algorithms, and hyperparameters were tuned using GridSearchCV.
![image](https://github.com/user-attachments/assets/0ffec661-3f78-4034-99c3-86ea6f31a967)
Results:
Key findings from the analysis include:
Launch Site Success Rates: KSC LC-39A had the highest success rate among all launch sites.
Payload and Orbit Analysis: Heavy payloads tend to have higher success rates for specific orbits like PolarLEO and ISS, while GTO orbits showed mixed results.
Yearly Trends: The success rate of launches has steadily increased since 2013, reaching its peak in 2020.

The decision tree classifier emerged as the best-performing model for predicting landing success, with a high accuracy score. However, the model's confusion matrix revealed some issues with false positives, indicating areas for further improvement

![image](https://github.com/user-attachments/assets/72641563-8845-4c3a-8e11-27fc8f53e9da)
Conclusion
The project successfully developed a predictive model that can help Space Y optimize their launch processes and reduce costs. The insights gained from the EDA and the interactive visualizations provide valuable information for decision-making and strategic planning. The continuous improvement of the model and further analysis of additional features will enhance the accuracy and reliability of the predictions.
![image](https://github.com/user-attachments/assets/43a7a80d-d024-4c02-a11c-8e3817098155)
