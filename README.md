# Data-Visualization
Goal: Visualize and Analyse James Bond Movies data using pandas and matplotlib <br>
- Step 0: Clone this repo to your computer. <br>
- Step 1: Open the `james_bond_data_cleansed.csv` file using Excel and take a look at it to understand the data in the file. <br>
- Step 2: Create a jupyter notebook in VSCode. Save the notebook in the repo folder. <br>
- Step 3: Import pandas and matplotlib and use pd.read_csv() to read from the james_bond_data_cleansed.csv file. If you got error, you may need to install the two libraries by typing `pip install pandas matplotlib` in VSCode terminal. If the terminal doesn't understand pip, you may need to edit System Variables and add pip's path to system's Path. <br>
- Step 4: Answer the below questions:
  -	(1/4 pts) Is there a correlation between IMDb rating and Rotten Tomatoes rating? Hint: to answer this question, you can use plt.scatter() to create scatter plot with x-axis IMDb rating and y-axis Rotten Tomatoes rating. For more about scatter plot, check this link https://www.w3schools.com/python/matplotlib_scatter.asp. Your scatter plot should look similar to this
    ![image](https://github.com/user-attachments/assets/bba91fb3-b8a2-4b7d-b6f1-8fbb2ccedeea)

  -	(1/4 pts)  Is there a correlation between IMDb rating and the number of bad guys killed by Bond (stored in column named bond_kills)? Hint: use plt.scatter() to plot and answer this question. Your plot should look similar to this
 
    ![image](https://github.com/user-attachments/assets/31e106ce-e35f-429a-b97a-623bcfb296cc)


  -	(1/2 pts) What are the trends of movie budget and income world along the time? Hint: plot movie budget and income world vs release year can help you answer this question. Your plot should look similar to this. Check this for how to create legend https://www.geeksforgeeks.org/matplotlib-pyplot-legend-in-python/
    ![image](https://github.com/user-attachments/assets/b3b0aa54-7f54-4245-8d88-a013f660be86)

 
  -	(1/2 pts) What is the trend of income world – movie budget ratio along the time? Hint: you can use bar plot https://www.geeksforgeeks.org/bar-plot-in-matplotlib/ to plot this figure. Your figure should look similar to the one below.  From this trend, do you think producer make more profit now than they did in past? 
    ![image](https://github.com/user-attachments/assets/0e8596f3-6368-41ea-a912-80c0ba7ca00b)

  -	(1/2 pts) What is the shortest, the longest, the mean length, the median length, the highest rating, the lowest rating, the mean rating, the median rating James Bond movie(s)?

- Step 5: Answer the above questions by using comments below each figure in your notebook. Push your notebook to github by the due date.
