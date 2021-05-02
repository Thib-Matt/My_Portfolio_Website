## Contact

thibault.mattera@gmail.com  
[LinkedIn](https://www.linkedin.com/in/thibaultmattera/)

# Projects

## [Project 1: Recommendation System for Restaurants](https://github.com/Thibault-Mattera/Recommendation_System_Restaurants.git)

In a world where the large commercial offer is overwhelming us, online reviews have a significant impact on customers' decision.

The project consisted in creating a tool that proposes a personalized list of restaurants based on users profiles.
- Scraped around 1800 restaurants and 1900 reviewers' profiles from TripAdvisor using Python and Selenium
- Engineered features from restaurants' description to extract usable information (type of cuisine, price range and popularity)
- Built profiles' clusters based on an unspervised learning algorithm
- Productionized the solution: created and deployed a web-app connected to a Flask API: [Click here to try it!](https://tmattera.pythonanywhere.com/)

![](/images/demo-recommendation-system.gif)

## [Project 2: COVID-19 Relevant Articles Finder](https://github.com/Thibault-Mattera/COVID-Relevant_Articles-Finder.git)

To answer the call to action to leverage our expertise as Data Scientists and developers in the fight against COVID-19, we created a smart search engine that suggests relevant academic articles related to coronavirus based on user's specific request. 

The project consisted in:
- cleaning and preprocessing the articles
- building an unspervised learning algorithm to identify undiscovered topics in the set of articles.
- productionizing the solution by developing a Flask API and a Web-interface
- Deployment/DevOps: containerizing the whole solution with Docker

This could help the medical community by generating new insights among over 400k academic articles.

![](/images/covid-app-demo.gif)

## [Project 3: Disaster Tweet Detector](https://github.com/Thibault-Mattera/Disaster_Tweet_Detector)

Twitter has become an important communication channel in times of emergency as it gives near real-time information. But the task to recognize if a tweet is clearly related to a real disaster is tricky and time-consuming.

I built a solution based on Machine Learning (Supervised Learning) that can identify if a tweet is related to a real disaster or not. This could help emergency services to automatically monitor Twitter to detect disasters with a better accuracy and deploy the resources more effectively.

After trying different methods (Classifiers and Neural Networks), I was able to predict a real disaster tweet with 88% accuracy. 
This was obtained after preprocessing the tweets (cleaning, NLP, vectorizing) and using a BERT-based model.

Word cloud disaster tweets |  Model performance
:-------------------------:|:-------------------------:
![](/images/word_cloud_disaster_tweets_resized.png)  |  ![](/images/performance_BERT_resized.png)
