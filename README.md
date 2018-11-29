# SPORTS DATA ANALYSIS USING MACHINE LEARNING
Tennis is certainly among the world’s most popular sports. Throughout the history of tennis, there have been champs who have captivated fans with their achievements. There is an abundance of historical tennis data which is available online. Most current state-of-the-art approaches to tennis prediction take advantage of this data to define hierarchical expressions for the probability of a player winning the match. However, these models use only the probability of each of the players winning a point on their serve to compute their respective probabilities of winning the match. So, we propose a sequential learning approach that uses historical player performance across a wide variety of statistics to predict locations of serves – wide, body or down the T. Here we define an innovative method of extracting features from raw historical data, including abstract features, such as player fatigue and confidence levels throughout the game. Based on the shots being played during a rally we estimate the probability of the outcome (e.g., winner, continuation, or error) and the location of the next serve. As player behavior heavily depends on the opponent, we use model adaptation to enhance our prediction. Using the resulting dataset, we develop and optimize models based on two machine learning algorithms: logistic regression and artificial neural networks.

### APPROACH
1. The dataset charting-m-points.csv contains the details of Server, Sets, Games, Points and Shot Details. (https://raw.githubusercontent.com/JeffSackmann/tennis_MatchChartingProject/master/charting-m-points.csv) <br/>
2. To study the behavior of a player, I have filtered out all the data with one player so that the behavior study will be accurate.<br/>
3. Perform Exploratory Data Analysis to clean the dataset to remove unwanted NaN/null values.<br/>
4.	Drop columns which do not have much impact on the output.<br/>


### Gathering Data
1.	In order to get the right output for our problem, we need to have the right inputs to feed to our model.<br/>
2. Different Tennis data sets have been studied and gathered for this purpose.<br/>

### Cleaning Data
Data Cleaning is nothing but preparing your data for a dedicated purpose; taking the data from its raw state and transforming and mapping into another format.

### Choosing Model
Different machine learning models like Decision trees, Random Forest methods and Knn algorithms are trained and tested for the classification.<br/>


### TOOLS AND LIBRARIES USED
1.	Python<br/>
2.	Pandas<br/>
3.	NumPy<br/>
4.	Jupyter Notebook<br/> 
5.	Anaconda Navigator<br/>
6.	Scikit Learn<br/>


### Installation Steps:
1.	Go to https://anaconda.org/anaconda/anaconda-navigator and download anaconda navigator for the respective Operating System. For detailed information about the installation go to http://docs.continuum.io/anaconda/install/<br/>
2.	After the installation, launch Anaconda Navigator.<br/>
3.	Launch Jupyter Notebook and open an existing Python Notebook in it.<br/>

### Conclusion
1.	We are able to find a unique way of creating a model which classifies the serve direction with a high prediction accuracy of 84%. <br/>
2.	We need to understand that this model will not predict what is the best possible serve for any given situation.<br/>
3.	The next steps would be introducing other features like Opposite players age, height and agility into consideration for better accuracy.<br/>

 


