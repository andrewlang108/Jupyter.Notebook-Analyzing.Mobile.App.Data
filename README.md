# Jupyter.Notebook-Analyzing.Mobile.App.Data
A Jupyter notebook that analyzes App store and Google Play store data.

## Objective:
Do market research to determine what type of app would perform the best in both the Google and Apple application stores. Performing well means the apps have many downloads and make money. 

Two data files were read into the notebook. One contained app data from the Google Play Store, the other from the Apple App store. Each row in was a different app, with columns containing information such as price, primary genre, number of installs, and reviews. Notably, both tables did not contain all of the same columns. The combined number of rows was nearly 18,000.

Data was then cleaned by merging duplicate entries and filtering out non-english apps. Additinally, our analysis was only to include free apps, so any apps that cost money were filtered out. After these steps, about 12,000 rows of data were left. 

Analysis proceeded by attempting to answer a single question: which app genres are the most popular? primarily consisted of building and comparing frequency tables for each data set. Since the Apple data lacked information on number of downloads, the frequency table was built on average ratings per genre. For the Google data, the table was built on average installs per category (Google's equivalent to Genre). 

## Conclusions
Top genres across both app stores include Social, Navigation, Game, Productivity, and Photography. 
A successful app in the social media space would undoubtedly lead to high profitability. However, due to the highly competetive social media market, I am recommending that an app be created in the Photography genre. A free photography app could include in-app purchases for filters, editing presets, or additional features the can generate revenue beyond the ad space. Additionally, a photography app could be adjacent to a social media app such as Instagram that relies so heavily on users posting photos. 
