java cSubject: C39RF Applied Financial Modelling in Python Case Study 1
Date: Submission deadline: 28th of February, 12pm UK time, 4pm Dubai time, and 8pm Malaysia
time.
Please note the following before you commence the assignment:
• You have to submit a Jupyter Notebook file (with extension ipynb) as well as a script with
the html extension which contains the solutions (output) to the tasks enumerated below.
Upload these files into the Assignment - Case Study 1 Submission. Failure to upload the
html file will result in losing 10 marks.
• Number the tasks so it is clear which one your are answering.
• You also have to submit all the csv files that contain your data - failing to do so will result in
losing marks.
• Make sure you don’t download data that was discussed in class (lectures and tutorials) such
as: IBM, META, Spotify, Apple, Nvidia, Microsoft, Google, Tesla, SP index, FTSE100 index,
DAX index, VIX index, Bitcoin, Oil price, Gold price.
• Please remember that only four types of files are allowed to be uploaded onto Canvas/Turnitin:
ipynb, html, excel and csv. Do not upload PNG files. Make sure you download the files and
upload them well before the deadline. Practice downloading the ipynb and html files from
the Jupyter Notebook now.
• For each task, 25% of the marks will be awarded for successfully writing up the code, and
the rest of the marks (75%) will be given for explaining in-depth the results. If you are asked
to discuss for example a plot in 100 words and you only discussed it in 50 words, your mark
will reflect that. Of course, the content of your discussion matters primarily and not the
length of your discussion. Your discussion should always relate to results and you should
not discuss generic issues (such as defining what p-values or test statistics are) as those do
not carry marks.
• Discussions should be provided in a Markdown cell and not in a code cell as comments. Do
not provide definitions of statistical and econometrics terms as that will not yield marks.
• Only use code that was used in Lectures and Tutorials. Do not produce a script using
different coding techniques - otherwise, it will be assumed that external help was utilised,
which will result in your assessment being reported as academic misconduct.
• This assessment is worth 100 marks and it accounts for 50% of your final grade.
• Make sure you have read, understood and followed the Universitys Regulations on plagia rism as published on the Universitys website, that you are aware of the penalties that you
will face should you not adhere to the University Regulations:
https://www.hw.ac.uk/uk/services/academic-registry/academic-integrity/
academic-misconduct.htm
1
• Make sure you have read, understood and avoided the different types of plagiarism ex plained in the University guidance on Academic Integrity and Plagiarism:
https://heriotwatt.sharepoint.com/sites/skillshub/SitePages/Academic-Integrity-and-Plagiarism.
aspx
You have to solve each task to get full marks.
1. Download daily adjusted close price of stock market data from Yahoo Finance for the period
January 2019 to December 2024 for two corporations from two different industries (choose
from: Automobile, Information Technology, Pharmaceuticals, Financial, Healthcare). The
two companies should be of high market capitalisation and they should not have been dis cussed in class. You should use a data scraping method that was used in class. 2 marks
2. Create a new dataframe (using the correct pandas method) with the two stocks. Make sure
the index column is not displayed. 1 mark
3. If the prices of the two stocks are of the same magnitude, plot a timeline of your two time
series (prices) in a single plot. However, if your two stock prices are of different magnitude,
display the two plots separately. Make sure the timeline (date) is visible. Name the axes and
give a title. Also, provide a legend. Discuss the figure in a Markdown cell in 100 words. 3
marks
4. Calculate the daily first differenced log returns for your two variables. 2 marks.
5. Check for missing values in the two returns series and remove them. Then inspect the head
of the two time series to show there are no missing values. Also, display the last 10 rows of
your returns. All these tasks should be executed in a single cell, not separately. 3 marks
6. Save the dataframe as a csv file. You will have to submit this file along with your Jupyter
Notebook and html files. 0.5 mark
7. Calculate the summary statistics for the two stock market returns. Critically discuss the
summary statistics in 200 words in a Markdown cell. 3 marks
8. Calculate the correlation between the two stock returns. Discuss your results briefly (max. 3
sentences) in a Markdown cell. 2 marks
9. Plot a histogram with 70 bins for both of your stock returns. Display the two代 写C39RF、Python
代做程序编程语言 histograms in
separate figures. Also save your histograms in a png format. These tasks should be executed
in one cell. Discuss in a Markdown cell in 100 words whether the data appears normally
distributed. 4 marks
10. Plot a timeline of your two returns in a single plot. Make sure the timeline (date) is visible.
Discuss the figure in a Markdown cell in no more than 100 words. 3 marks
11. Check your two returns’ series for stationarity and discuss the results in-depth in a Mark down cell in no more than 150 words. 3 marks
2
12. Check if your two returns’ series have outliers. Plot a boxplot for each of the time series
showing the outliers. Discuss in a Markdown cell the plots in 100 words. 3 marks
13. Remove the outliers and replot the two boxplots. Discuss in a Markdown cell the plots in
100 words. 3 marks
14. Download the daily adjusted prices of 30 individual stocks of a main stock market index
(stock market index constituents). You can find the list of indices here: https://finance.yahoo.com/world indices/. We’ve done a similar task for the DAX30 index stock market constituents. At this
stage you need to download the individual stocks of the index and not the index itself. The
stocks should not be the constituents of the SP500, FTSE100 or the DAX30 indices. The
target period is January 2019 to December 2024. Discuss the index, how is calculated and its
constituents briefly in 100 words in a Markdown cell. 2 marks
15. Calculate and plot the cumulative returns time series for the index constituents. Discuss the
plot in no more than 100 words in a Markdown cell. 3 marks
16. Save the cumulative returns in a csv file. You will have to submit this file along with your
Jupyter Notebook and html files. 0.5 mark
17. Compute and plot the first principal component and discuss your results in detail (300
words). The task is to find out which stocks cause the highest degree of variability in the
index. 8 marks
18. Build a portfolio of stocks by allocating funds proportionally to the 1st principal component
in order to replicate the returns of your chosen index. You need to calculate the cumulative
returns using the weights of the top stocks that form the 1st principal component. 2 marks
19. Plot the cumulative returns of the newly created portfolio. Also, save the figure as a png file.
The two tasks should be executed in one cell. Discuss the plot in 100 words. 2 marks
20. Download the daily adjusted closing price for the index for the January 2019-December 2024
period. 2 marks
21. Calculate the first differenced log returns for the index and save them in a csv file. You will
have to submit this file as part of your assessment. 1 mark
22. Plot in one figure the portfolio of stocks you’ve created using the first principal component
as well as the returns of the index. Discuss whether the portfolio tracks the index or not in a
maximum of 200 words in a Markdown cell. 4 marks
23. Evaluate the effect of the Covid19 pandemic on individual stock returns. Discuss the results
in-depth in 250 words in a Markdown cell. 9 marks
24. Download daily adjusted closing price data for two stocks: one from the Telecom industry
(this will be your dependent variable) and one from the Energy industry (this will be your
independent variable). Both companies should be of high market capitalisation. The period
of interest is January 2000 to December 2024. 2 marks
25. Calculate first the differenced log returns, then transform the data to a dataframe and plot
both returns in one plot. The first two tasks should be executed in one cell. Discuss the plot
in 100 words in a Markdown cell. 4 marks
3
26. Save the returns as a csv file. You will have to submit this file along with your Jupyter
Notebook and html files. 0.5 mark
27. Plot a histogram with 80 bins for both returns separately. Discuss the normality of your data
in a Markdown cell in 100 words. 3 marks
28. Run summary statistics on your returns dataframe and discuss the results in 100 words in a
Markdown cell. 2 marks
29. Calculate the correlation, skewness and kurtosis of the returns. Discuss the results in 150
words in a Markdown cell. 4.5 marks
30. Run an OLS regression and discuss your results in-depth in a Markdown cell in 250 marks.
9 marks
31. Calculate the regression residuals and test these for the Classical Linear Model assumptions.
Discuss your results in a Markdown cell in 300 words. Provide plots where necessary. 9
marks
Total 100 marks
Don’t forget the following:
• Make sure you show all of the outputs (solutions, plots, etc) before downloading the ipynb
and html files.
• Download the ipynb and html scripts and upload them to the Assessment page.
• Upload all the csv files to the Assessment page. Do not upload the png files onto Canvas.
4

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
