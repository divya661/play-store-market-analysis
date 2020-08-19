# play-store-market-analysis

# Introduction
A analysis of Android app on google play store from different view points/factors by comparing more than 10,000 apps across different categories & insights from the data are drawn that deivse the strategies to drive growth & retention. 
The `user_reviews.csv` dataset contains 100 reivews for each app.
The `app.csv` dataset contains 13 features most relevant to describe a given app.
1. Libraries are imported & the dataset files. Duplicates apps are droped from the dataset & the concise summary of apps dataframe has been shown.
2. Data cleaning is done for columns `Price` & `Installs` as are initially present in `object` datatype in the dataset file. Unwanted special characters in the `Installs` & `Price` columns are also removed.
3. Exploring app categories : In this different app categories are studied based on the highest share in the apps market. A bar plot has been ploted to study.
4. Study on app ratings has been done to found out the impact on discoverability, conversion of apps as well as the company's brand image. A histogram is ploted to make the study.
5. Impact of size & price of app is studied. `Rating` VS `Size` & 'Rating' VS `Price` is plotted.
6. Impact of app category on app price is studied. 
7. Junk apps are filtered out from the dataset & a striplot is plotted to provide visualization to easily find junk apps in each category.
8. Study on popularity of paid apps vs free apps is done & boxplot is plotted to visualize the no of downloads of paid apps vs free apps
9. Sentiment analysis of user reviews is done & boxplot is plotted.

# Instructions to run the code
1. Make a virtual environment

```
python3 -m venv env
```

2. Activate the virtual environment

```
source env/bin/activate # This command is for linux 
```

3) clone the repository : 

```
git clone https://github.com/divya661/play-store-market-analysis.git
```

Or

Download the zip folder & unzip the folder downloaded

4) Install the requirements by running the command in terminal:
```
pip install -r requirements.txt
```
5) Open the jupyter notebook and run the file `notebook.ipynb`
