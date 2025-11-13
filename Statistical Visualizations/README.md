### Statistical Visualizations

Here I explore how Python can be used for statistical data visualization and insight discovery. I focuse on applying advanced visualization techniques to interpret patterns, relationships, and key findings in data.

In addition, I explore integration between Python, MySQL Workbench, and Power BI, enabling complex visualizations and analytical results to be easy embedded into interactive Power BI reports for web presentation.
 
### Structure

- `Data:` .csv data files and an equivalent database dump
- `1_statistical_visualizations.ipynb:` Jupyter Notebook with statistical visualizations
- `2_scripts_for_powerbi.ipynb:` Python scripts adapted for use in Power BI
- `3_powerbi_sql_python.pbix:` complete Power BI report integrating Python scripts and MySQL data
- `4_powerbi_sql_python.pdf:` PDF export of the Power BI report for visual reference

### Implementation

I use the "Commerce" database, you will also need it to run the code. So start with the `Data` folder, there are .csv data files and equivalent database dump, create a database and upload the data there. But finally I didn't use all the tables for visualizations, for example the 'card_status' and 'credit_cards' tables were not used.

Next, go to the `1_statistical_visualizations.ipynb` file. In the first code block I load data from the database and do some data transformations, then each code block corresponds to one visualization. The code blocks are independent from each other, but you always need to run the first block with loading data, so after restart you can run the first block and any of the exercise you are interested in.

I used Matplotlib and Seaborn for visualizations. Here I practice OO-style for more control and consistency throughout the notebook. I chose the size of the figures considering using the code for scripts into Power BI in the next part, and the default backends are used. I always use plt.show(), so the code can be executed in any environment.

Next, go to the `2_scripts_for_powerbi.ipynb` file. This part includes creating a Power BI report using Python's analytical capabilities. I used the code I had already written and rewrote them for use in Power BI. So you need to create a new blank Power BI report and copy the code blocks one at a time, and paste them into Power BI. The first block of code corresponds to loading data into Power BI, each subsequent block of code corresponds to a script of the PY-visual in Power BI. It should be noted that Power BI will also take data directly from MySQL Workbench. You can see how this is implemented by downloading my report `3_powerbi_sql_python.pbix` or look visually right here in the `4_powerbi_sql_python.pdf` .pdf file.



