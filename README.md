# DS400-Final

This project is to satisfy the requirements of DS400 and the Data Science B.S. program.

Data analysis and prediction was performed on the "Chicago Traffic Crashes" dataset, sourced from Kaggle.
See link: https://www.kaggle.com/datasets/anoopjohny/traffic-crashes-crashes

After a detailed analysis of the data, we were able to determine useful information regarding traffic accidents such as what factors cause crashes, and which types of crashes cause more injuries.  We were also able to create a machine learning model that is able to predict the amount of fatalities in a crash with 85% accuracy based on factors such as location, date, and time.

After applying many preprocessing methods such as dimensionality reduction, scaling, PCA, and resampling, I tried multiple different machine learning algorithms on the data.  The most effective was a random forest classifier, which I then tuned using a grid search cross validation to achieve my final modeling accuracy.  The most important features in making these predictions were the location, date, and time.  Further study would be necessary to explore exactly what effect these values have on the prediction.  I also found that accidents involving padestrians and cyclists were much more likely to result in injuries.
