# Project 1: Movie Success Analysis

## Project Title: Movie Success Analysis

### Due Dates:
- **Jun 11**: Cleaned data file shared
- **Jun 13**: Visuals w/ Stats Tests completed
- **Jun 15**: Analysis completed
- **Jun 16**: Team review

### Team Members
- Finn
- Jackson
- John
- Parisha
- Sanem

### Project Description/Outline
We are aiming to answer questions pertaining to what some may call a "dying industry." What factors go into making the theatrical release of a movie successful? Is a movie successful based on how much money was put into its production? Are certain genres more economical? Do movies with MPAA ratings that cater to a wider audience make more money in theaters? These are just some of the questions we're hoping to answer.

### Our Hypotheses
- High production cost results in higher worldwide sales
- There is a significant difference between movie genres when it comes to profitability 
- There's a strong correlation between opening weekend sales and worldwide sales
- Summer movies have higher opening weekend sales
- MPAA Rating significantly impacts worldwide sales 

### Our Null Hypotheses
- Higher production costs do not result in higher or lower worldwide sales
- There is no significant difference in profitability between movie genres
- There is no correlation between opening weekend sales and worldwide sales
- Summer movies do not have higher opening weekend sales compared to non-summer movies
- There is no difference in worldwide sales when it comes to a movie’s MPAA Rating

### Research Questions to Answer
1. Production Cost vs. Worldwide Sales
   - Graph Type: Scatter Plot
   - Stats Test: Linear regression
2. Opening Weekend Sales vs. Worldwide Sales
   - Graph Type: Scatter Plot
   - Stats Test: Linear Regression
3. Profit Margin vs. IMDB Viewer Rating
   - Profit Margin = Worldwide Sales - Production Cost
   - Graph Type: Scatter Plot
   - Stats Test: Linear Regression
4. Profit Margin vs. Genre
   - Graph Type: Box Plot or Bar Plot
   - Stats Type: ANOVA
5. Release Date vs. Opening Weekend Sales
   - Graph Type: Box Plot or Bar Plot
   - Stats Type: Independent T-test
6. Duration vs. Worldwide Sales
   - Graph Type: Scatter Plot
   - Stats Type: Linear regression
7. Duration vs. IMDB Viewer Rating
   - Graph Type: Scatter Plot
   - Stats Type: Linear Regression
8. MPAA Rating vs. Worldwide Sales
   - Graph Type: Box Plot or Bar Plot
   - Stats Type: ANOVA
9. Actor vs. Worldwide Sales
   - Graph Type: Bar Plot

### Datasets to Be Used
#### ["Top 500 Movies by Production Budget"](https://www.kaggle.com/datasets/mitchellharrison/top-500-movies-budget)
This dataset will include data surrounding:
- Production Cost
- Worldwide Sales
- Opening Weekend Sales
- Profit Margin (Worldwide Sales - Production Cost)
- Genre
- MPAA Rating

#### ["IMDB Movies Dataset"](https://www.kaggle.com/datasets/amanbarthwal/imdb-movies-data)
This dataset will include data surrounding:
- Release Date
- Duration
- Rating
- Cast (Actor information)

### Rough Breakdown on Tasks
- **Data cleaning:** Jackson
- **Data merging:** Finn
- **Data visualization:**
  - Finn: Profit Margin vs. IMDB Viewer Rating, Release Date vs. Opening Weekend Sales
  - Jackson: Opening Weekend Sales vs. Worldwide Sales, Production Cost vs. Worldwide Sales
  - John: Duration vs. IMDB Viewer Rating, Duration vs. Worldwide Sales
  - Parisha: Profit Margin vs. Genre
  - Sanem: Actor vs. Worldwide Sales, MPAA Rating vs. Worldwide Sales
- **Data Analysis/Summary:** Parisha, Finn
- **Presentation:** Jackson, Parisa, Finn

### Comprehensive Notebook
The `movie_FINAL.ipynb` file consolidates the work of the entire team, integrating all individual analyses into a single comprehensive notebook. The individual contributions are compiled from the following notebooks:
- `movie_sanem.ipynb`: MPAA Rating vs. Worldwide Sales, Actor vs. Worldwide Sales
- `movie_finn.ipynb`: Profit Margin vs. IMDB Viewer Rating, Release Date vs. Opening Weekend Sales
- `movie_jackson.ipynb`: Production Cost vs. Worldwide Sales, Opening Weekend Sales vs. Worldwide Sales
- `movie_parisha.ipynb`: Profit Margin vs. Genre
- `movie_john.ipynb`: Duration vs. Worldwide Sales, Duration vs. IMDB Viewer Rating

### Visualizations
All visualizations generated from the analysis can be found in the `movie_analysis_visualizations` directory. This directory contains all the graphs and charts created during the analysis phase.

### Resources
- [NumPy Standard Deviation](https://numpy.org/doc/stable/reference/generated/numpy.std.html)
- [SciPy Tutorial](https://docs.scipy.org/doc/scipy/tutorial/index.html)
- [Pandas DataFrame Reference](https://pandas.pydata.org/docs/reference/frame.html)
- [Matplotlib Pyplot Plot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)
- [IMDB Movies Dataset](https://www.kaggle.com/datasets/amanbarthwal/imdb-movies-data)
- [Top 500 Movies by Production Budget](https://www.kaggle.com/datasets/mitchellharrison/top-500-movies-budget?resource=download)
- [F-Critical Value](https://www.stat.purdue.edu/~lfindsen/stat503/F_alpha_05.pdf)
