# Youtube_comment_scraping-Sentiment_analysis
🎉🎉 My first attempt at Social Media data scraping


Process:
- Web scraping was done using Obsei, an open source AI automation tool. (https://obsei.github.io/obsei/)
- The scraper already existed in the YoutubeScrapperSource module of Obsei, which made the task a lot easier.
- The classification algorithm also existed in the ClassificationAnalyzer module.
- The target youtube video had to be one that had a spark of emotions in the comment section, so I chose one of the most viewed and talked about events thus far in 2022, to scrap its comment. View Ipynb file to know the video 🙃
- Zero Shot Classification Analyzer was used as technique because it does not require prior data or information on the text given. 
- Labels used for the analyzer were ['Positive and 'Negative'].
- A limit of 50 was set for data to be collected. The comments were selected randomly.
- The comments were loaded into the a Pandas DataFrame for easy accessibilty.
- After the Classification, The result of the classification was visualized using a bar graph, to show the obvious comparison between the records


<br>
- View result for the Negative Label below:

![ysa1](https://user-images.githubusercontent.com/43454449/174496941-41385e35-0352-440a-a892-caf9ad3dbfb4.PNG)

(The taller the bar, the more negative the comment)

- View result for the Positive Label below:

![ysa2](https://user-images.githubusercontent.com/43454449/174497017-e2b05fbe-6635-4393-b2cd-34aeb69952e5.PNG)

(The taller the bar, the more positive the comment)


<br>

A little interpretation of the result🙃:

--------From the look to things, this video had more positive reviews or comments than Negative comments; even though the margin is small.
