# Wrangle-and-Analyze-Data
## About this project and Udacity Data Analysis Nanodegree Program
This project aims to aid the understanding of data wrangling. In this project, I will be run through the "Gather-Access-Clean-Analyze" process to get useful insights from raw data.<br>
The data used in this project is called [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. It has over 4 million followers and has received international media coverage.
## How to run this project
The coding environment is Python, including the following:
<li>Numpy</li>
<li>Pandas</li>
<li>requests(download data)</li>
<li>tweepy(API)</li>
<li>json(API)</li>
<li>Seaborn</li>
<li>Matplotlib</li>

The data contains three parts:<br>
**Enhanced Twitter Archive**(included as csv):The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything.<br>
**Additional Data via the Twitter API**:  Retweet count and favorite count are two of the notable column omissions. You're going to query Twitter's API to gather this valuable data.<br>
**Image Predictions File**: A table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction.
<br>
You can download the ipynb to run it with Jupyter Notebook(don't forget to download csv sheet as well) or view as a HTML.

## Visuals and Findings
1. **The most common dog breeds in our list:** Golden Retriever was the most common dog breeds on We Rate Dogs, accounting for roughly 9% of all posts. The second most common dog type was Labrador Retriever, at around 6%.<br>
2. **Dog ranking by likes and retweets:** Very similar to the most common dog breeds ranking.<br>
3. **Does the most top rated dog get the most likes and retweets?** <br>
-Generally, a higher dog score does not asscoicates with higher view activity. However, the most popular posts with viewers all have highest viewer score.
4. A list of Winner Post of every month by likes and retweets.
