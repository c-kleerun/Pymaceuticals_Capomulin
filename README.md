# Pymaceuticals Capomulin Medical Trial

This project explores data from Pymaceuticals' recent study regarding the efficacy of the drug, Capomulin, in treating squamous cell carcinoma (SCC). Tumor development was observed and measured over 45 days. The data was cleaned, removing any duplicate mouse ID data and the cleaned data was used to explore the following data: 

<ul><li> Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. 
  <li>![summary_stats_capomulin (2)](https://user-images.githubusercontent.com/71466063/127384959-76676f9b-6af4-457a-abda-dee727d30dd7.png) 
  <li> Generate a bar plot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
  <li> Generate a pie plot that shows the distribution of female or male mice in the study.
  <li> Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
  <li> Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
  <li> Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
  <li> Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
  <li> Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
  <li> Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
    
Many of the plots were created using both Panda's DataFrame.plot() and Matplotlib's pyplot for practice in using both modalities.  
visualzations will compare the performance of Capomulin compared to other treatment regimins. 
