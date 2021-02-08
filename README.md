# Tableau

### Welcome to the Tableau Skill Set..!

##### Here, You can find about the Tableau skills, which I have learnt in the Course, namely,’ Tableau 2020 A-Z: Hands-On Tableau Training for Data Science’ on Udemy, created by Kirill Eremenko. 
##### All the dataset you can find on the following link: https://www.artofvisualization.com/pages/tableau

##### The content will be presented in following manner : 
- At first, I will explain about the task.
- After that, I will show you the file name. Please pay attention on the file type also.
- Afterward, I will discuss about the approaches, by which I have create the plots and dashboards.All the approaches have been performed in Tableau Software only.
- For the better understanding, I have shown the sample of that dataset.
- At last, you can see the results.

#### Task 1: Find the most profitable and less profitable states.              Dataset: SuperStoreUS_2015.xlsx
##### Sample dataset of task 1 and its result have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_1.png" width="35%" height= "35%" alt= "Sample_Dataset" />
  <img src="/Tableau_images/Image_2.png" width="50%" height= "50%" alt= "Results" />
</p>

#### Task 2: It is the end of Financial Year and that means time for annual bonuses! The store operates in three regions and only the top-performing employee in each region qualifies for a bonus. Find out which three employees are eligible to get bonuses for this year. Employees are measured on total sales ($$).           Dataset:  OfficeSupplies.csv / OfficeSupplies.xlsx
#### Approach:    
- Create calculate field : Total sales = Units * Unit Price
##### Sample dataset of task 2 and its result have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_3.png" width="45%" height= "45%" alt= "Sample_Dataset" />
  <img src="/Tableau_images/Image_4.png" width="45%" height= "45%" alt= "Results" />
</p>

#### Task 3: Visualize Time Series Data at different Granularity with quick filters.            Dataset:  Long-Term-Unemployment-Statistics.xlsx
##### Sample dataset of task 3 and its result have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_5.png" width="40%" height= "40%" alt= "Sample_Dataset" />
  <img src="/Tableau_images/Image_6.png" width="45%" height= "45%" alt= "Results" />
</p>

#### Task 4: Make an interactive Dashboard, which should have profit margin at every state and the customer scatter plot based on profit vs sales.            Dataset: AmazingMartEU2.xlsx
#### Approach:    
1. Apply Inner join with key: Order ID
2. Calculate field: Profit Margin = SUM(Profit) / SUM(Sale)

##### Sample excel sheets of task 4 have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_7.png" width="80%" height= "80%" alt= "Sample_Dataset" />
  <img src="/Tableau_images/Image_8.png" width="80%" height= "80%" alt= "Results" />
</p>

#### Result:
<p float="left">
  <img src="/Tableau_images/Image_9.png" width="80%" height= "80%" alt= "Results" />
</p>

#### Task 5: Evaluate the performance of each department based on its sales target by creating dual axis chart.            Dataset:  AmazingMartEU2.xlsx
#### Approach:    
- 	Use Data Blending instead of joining excel sheets due to different graduality or different type of data sources.
##### Sample from dataset after inner joint with two excel sheets for the task 5 have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_10.png" width="100%" height= "100%" alt= "Sample_Dataset" />
  <img src="/Tableau_images/Image_11.png" width="30%" height= "30%" alt= "Results" />
</p>

#### Result:
<p float="left">
  <img src="/Tableau_images/Image_12.png" width="80%" height= "80%" alt= "Results" />
</p>

#### Task 6: Analyse the customers based on region, age, gender, bank balance and job class, using dummy dataset of the bank and create Storyline.           Dataset:  UK-Bank-Customers.csv
#### Approach:    
1. Set Geographical Roles
2. Convert Gender proportion in to percent using quick table calculation
3. Create bins for age distributions using parameters
4. Create bin for balance distributions using parameters

##### Sample from dataset 6 have been shown below:
<p float="left">
  <img src="/Tableau_images/Image_13.png" width="70%" height= "70%" alt= "Sample_Dataset" />
</p>

#### Result:
<p float="left">
  <img src="/Tableau_images/Image_14.png" width="80%" height= "80%" alt= "Results" />
</p>


