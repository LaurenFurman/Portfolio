# Portfolio
# About Me
Hi, I'm Lauren Furman. I'm a Senior Business Analyst with skills in technology with a specialty in health care.

# Work info
Accenture since 2015

## Skills/Proficiencies
- Data analysis
- BI tools
- Agile Methodologies
- SQL and DBs 
- Proficient communcation
- Adaptable


# Contact Information
- Email: Lauren.Furman5@gmail.com

# Projects
## Project 1
## Walmart’s Customer Satisfaction in Electronics & Home Entertainment

### Overview
This project analyzes Walmart’s customer satisfaction levels in the electronics and home entertainment sectors, aiming to uncover factors influencing positive and negative sentiments. By examining review data, the project investigates the impact of product quality, price, demographics, and promotions on satisfaction to generate actionable insights for Walmart. Findings are intended to guide Walmart in tailoring its offerings and engagement strategies to improve customer satisfaction.

### Tools Used
- Python Libraries: Pandas, VADER Sentiment Analysis, Matplotlib
- Data Visualization: Word cloud, sentiment distribution charts
- Data Source: Data.world (CSV format)

### Key Findings
1. **Sentiment Distribution**: Approximately 80% of reviews reflect positive sentiments, suggesting an overall favorable perception of Walmart’s electronics and home entertainment offerings.
2. **Top Positive Features**: High-rated keywords such as “easy,” “use,” “quality,” and “Roku” suggest ease of use and affordable quality are key satisfaction drivers.
3. **Negative Sentiment Drivers**: Keywords like “sound,” “battery,” “screen,” and “work” indicate that issues with durability and performance are major concerns among dissatisfied customers.
4. **Popular Products**: Roku streaming devices were frequently reviewed and received high ratings, affirming their strong performance. Conversely, RCA products, particularly the RCA Viking Pro tablet, had mixed reviews, suggesting improvement areas.
5. **Recommendations**: The proposed Electronics Home Entertainment Experience Platform (EHEEP) aims to personalize Walmart’s customer experience using predictive analytics, enhancing product recommendations and satisfaction.

### Visuals
1. **Sentiment Distribution Chart**: This chart shows the percentage of positive, neutral, and negative sentiments among reviews.
2. **Top Keywords Word Cloud**: A visual representation of the most frequently mentioned words in positive and negative reviews, highlighting recurring themes like “easy,” “quality,” “battery,” and “screen.”
3. **Most Popular Products Chart**: A bar chart displaying the ratings and popularity of top products, including Roku and RCA items, based on review frequency.
![Sentiment Distribution](https://github.com/user-attachments/assets/e6fcf42e-c52a-4d1d-a44c-5f08aca4348b)
![Top 30 W![Most Popular Ratings](https://github.com/user-attachments/assets/74e6d2b4-727d-490e-b659-83223903e187)
ord Sentiments](https://github.com/user-attachments/assets/61fd1db6-70c9-4105-9751-5a7184a009aa)




### Link to Code
The code for this project can be found in the following Google Colab space: [Google Colab Link](https://colab.research.google.com/drive/your_colab_link_here)


## Project 2 
## Survey Analysis of Student Satisfaction in Online Learning

### Overview
This project analyzes student satisfaction levels in online learning, aiming to uncover the factors influencing adaptation to online education. By examining survey data from 1,205 students, the project investigates the impact of demographics, access to technology, and institutional support on student adaptability. The findings are intended to inform strategies that can enhance the online learning experience, providing actionable insights for educational institutions and policymakers.

### Tools Used
- Python Libraries: Pandas, Matplotlib, Seaborn, SciPy
- Data Visualization: Pie charts, bar charts
- Data Source: Survey Data (CSV format)

### Key Findings
1. **Adaptability Distribution**: The majority of students face challenges in adapting to online learning, with only 7.6% reporting high adaptation levels.
2. **IT vs. Non-IT Students**: IT students exhibit slightly better adaptability, but the difference is not statistically significant.
3. **Institution Type Impact**: Students from non-government institutions report higher adaptability scores, suggesting that these institutions may offer more effective support for online learning.
4. **Demographic Influences**: Financial condition, network reliability, and use of self-directed learning management systems are positively associated with better adaptability.

### Visuals
1. **Adaptivity Level Distribution**: This pie chart shows the distribution of students based on their level of adaptation to online learning. A significant portion of students report struggling with online learning, highlighting the need for targeted support strategies.
2. **Adaptivity vs. IT Students**: This bar chart compares the adaptability scores of IT students versus non-IT students, showing that IT students have slightly better adaptability scores on average. However, this difference is not statistically significant.
3. **Adaptivity by Institution Type**: This bar chart displays the adaptability scores of students from government and non-government institutions, showing that students from non-government institutions have higher adaptability. This suggests that non-government institutions may provide more effective support for online learning.

   ![Pie Chart of Adaptivity Levels](https://github.com/user-attachments/assets/cc20aa9a-3deb-4c28-a5ac-4b5819621d54)
![Bar Chart of Adaptivity vs  Institution Type](https://github.com/user-attachments/assets/5fcefa3c-45c5-46e4-a104-c42fdde835f4)
![Bar Chart of Adaptivity vs  IT Student](https://github.com/user-attachments/assets/570486c0-23b2-4bda-916e-e237efcf2b88)


### Link to Code
The code for this project, including exploratory data analysis and visualizations, can be found in the following Google Colab space: [Google Colab Link](https://colab.research.google.com/drive/your_colab_link_here)



## Project 3 
## Predicting Employee Attrition with HR Analytics

### Overview
This project focuses on predicting employee attrition using the HR Analytics Dataset from Kaggle. The analysis explores various factors that contribute to employee turnover, such as job role, satisfaction levels, and compensation. By conducting exploratory data analysis (EDA), the project aims to uncover actionable insights that can help improve employee retention and inform HR strategies.

### Tools Used
- Python Libraries: Pandas, NumPy, Seaborn, Matplotlib
- Data Visualization: Bar chart, box plot, correlation heatmap
- Data Source: HR Analytics Dataset (CSV format)

### Key Findings
1. **Attrition Distribution**: The dataset indicates variations in attrition rates across different departments and job roles.
2. **Salary and Satisfaction**: Employees with lower monthly income and satisfaction levels tend to have higher attrition rates.
3. **Influential Factors**: Features such as Job Role, Work-Life Balance, and Age are strong indicators of employee turnover.
4. **Recommendations**: Implementing retention strategies targeting departments with higher turnover and improving job satisfaction can reduce attrition.

### Visuals
1. **Attrition Distribution**: This bar chart displays the distribution of attrition (whether an employee has left or stayed) across various departments and job roles. It helps visualize which areas of the organization experience higher turnover.
2. **Box Plot for Distribution Analysis**: These box plots represent the distribution of various features in the dataset, allowing us to examine the spread and variation of each variable. The box portion of the plot represents the interquartile range (IQR), which spans from the 25th percentile (Q1) to the 75th percentile (Q3). The line within the box marks the median (50th percentile) of the data. Outliers, represented as individual points beyond the whiskers of the box, are data points that fall outside the range defined by Q1 − 1.5 × IQR and Q3 + 1.5 × IQR. These outliers could indicate unusual values that may require further investigation, either as anomalies or as key signals for attrition prediction. By analyzing the distribution of features such as Age, Monthly Income, and Job Satisfaction, we can identify potential patterns or areas requiring deeper focus to better understand the drivers of employee turnover.
3. **Heatmap Correlation of Features**: This heatmap shows the correlation between different features in the dataset, revealing how attributes like Job Satisfaction, Work-Life Balance, and Monthly Income relate to attrition. Features with high correlations to attrition are key indicators that can be used to predict turnover.
![Attrition Rate Distribution](https://github.com/user-attachments/assets/eec5a9a9-5357-45c4-adac-269b94ce317f)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/cd5f391b-fa4b-402e-b8fc-91b694a92631)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/6b60af28-d59b-41de-8fa8-1d376c0ff23f)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/763299e5-b9c4-4556-9bc1-e4134258ad3e)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/6d346079-323b-48d1-9302-3db1c39ad51c)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/a193ad89-b2be-4a9d-8ee6-9a821fffe3b9)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/bc80d068-5efb-4d73-ad9f-1101a075a8e4)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/b93e3498-2d22-4010-9fbb-0fe5155b061b)
![Attrition Rate Distribution](https://github.com/user-attachments/assets/5f4548e0-0b06-4e29-8df1-f7e35792cc66)





### Link to Code
The code for this project, including EDA and the analysis leading to the visualizations above, can be found in the following Google Colab space: [Google Colab Link](https://colab.research.google.com/drive/your_colab_link_here)






