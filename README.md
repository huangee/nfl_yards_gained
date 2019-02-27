# Will an NFL Play Result in a Yard Gain or Loss?

The goal of this project was to determine if I could predict if a certain pass or run play would be yards positive or not. I used [this Kaggle dataset](https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016), containing play by play data from 2009 through week 15 of the 2018 season.  

Models tested include: 
- Logistic Regression
- KNN
- Naive Bayes - Gaussian
- SVC
- Decision Trees
- Extra Trees
- Random Forest

For more information, see [the presentation here](https://github.com/huangee/nfl_yards_gained/blob/master/nfl_play_classification.pdf)

**This github contains:**
- [code to put the data into a PostgreSQL database](https://github.com/huangee/nfl_yards_gained/blob/master/00_Create_SQL_Table.ipynb)
- [code for model analysis and Tableau visualization](https://github.com/huangee/nfl_yards_gained/blob/master/01_NFL_all_teams.ipynb)
- [Tableau dashboard](https://github.com/huangee/nfl_yards_gained/blob/master/NFL_Play_Yards.twb) (you will need Tableau Desktop to open, otherwise, see next bullet)
- [video demo of Tableau dashboard](https://github.com/huangee/nfl_yards_gained/blob/master/Tableau_demo.mov)
- [slide deck presentation](https://github.com/huangee/nfl_yards_gained/blob/master/nfl_play_classification.pdf)

**Tools & technology used:**
- Python
- Pandas & Numpy
- Jupyter Notebook
- PostgreSQL, sqlalchemy & psycopg
- Matplotlib & Seaborn
- Tableau
- [TabPy](https://github.com/tableau/TabPy)
- scikit-learn
- [rfpimp](https://github.com/parrt/random-forest-importances)
