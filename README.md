# Youtube-trending-videos-analysis
Tags, Emojis, Likes, Dislikes analysis for top trending YouTube Channels
This dataset is a daily record of the top trending YouTube videos and it will be updated daily.
Context
YouTube maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”.

Note that this dataset is a structurally improved version of this dataset.

Content
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the IN, US, GB, DE, CA, FR, RU, BR, MX, KR, and JP regions (India, USA, Great Britain, Germany, Canada, France, Russia, Brazil, Mexico, South Korea, and, Japan respectively), with up to 200 listed trending videos per day.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the 11 regions in the dataset.

For more information on specific columns in the dataset refer to the column metadata.

Acknowledgements
This dataset was collected using the YouTube API.
This dataset is the updated version of Trending YouTube Video Statistics.

Inspiration
Possible uses for this dataset could include:

Sentiment analysis in a variety of forms
Categorizing YouTube videos based on their comments and statistics.
Training ML algorithms like RNNs to generate their own YouTube comments.
Analyzing what factors affect how popular a YouTube video will be.
Statistical analysis over time.
For further inspiration, see the kernels on this dataset!
