## Matplotlib-Challenge

# General

Hi there, My homework submission is uploaded as per the instructions. There is also one folder in Pymaceuticals called "images" where I have printed all the screen shots of graphs and bars. I have approached this homework by reviewing class lessons BarCharts and PyPieCharts.

# Code overwiev

To begin with I've started with generating whole data study files from the folder which are mouse_metadata and study_results, after that I've made a clean DF and removed all the duplicates and generated actual number of mice in Clean DataFrame. After that generated summary statistics DF by doing basic calculations like mean, meadian, variance, standard_deviation and SEM. Next tip was to create bar and pie charts showing the total number of timepoints for all mice tested for each drug regimen using Pandas. To do that I created the dataframe down to two columns (Drug Regimen,Mouse ID) followed with set_index(Drug Regimen). Next was to create the plot by gender where I've approached to do some basic calculations like count and sum and also percentage, where I get the result that we have total of 125 Male and 124 Mices, which I've included in mouse_gender DF where was plot created from. For Quartile I have used .loc with combined_df and timepoints for Capomulin, Ramicane, Infubinol, and Ceftamin and I have included all the results in one plot instead of generating one for each other because of reading. Than jumped on next part which was to generate a line plot of tumor volume vs. time point for a mouse treated with Capomulin. In this part I have collected data from one mouse with capomulin_df.loc[capomulin_df]. In next graph there is a scatter plot of mouse weight versus average tumor volume for the Capomulin regimen where I've determined to use 3 columns combined Mouse ID, Weight (g) and Tumor Volume (mm3). To get the correlation used just basic code to run in between Weight and Tumor Volume(mm3) and result was 0.53. Next was to import linregress which was done by using code from scipy.stats import linregress and adding the lineear regression equation and line to the scatter plot.

# Conclusion

For this homework I was bit overdue because lots of the other things are happening in the background at the moment but at the end everything was done well, little bit tricky because in this homework we can get even different results by just changing the Mouse ID's so I'm not sure which way was correct but I have picked this one. I have included in actual file ## Observations and Insights.

