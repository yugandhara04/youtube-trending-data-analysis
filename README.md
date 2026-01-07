
# YouTube Trending Videos – Data Analysis Project

## 📌 Objective
To analyze YouTube trending video data and identify factors affecting audience engagement.

### How to Use This Project
1. Download the dataset from Kaggle using the link above
2. Extract `USvideos.csv`
3. Place it in the same folder as the notebook
4. Run the notebook


## 📊 Dataset
YouTube Trending Videos dataset (Kaggle)
Link- (https://www.kaggle.com/datasets/datasnaek/youtube-new?select=USvideos.csv)

The dataset used in this project is the **YouTube Trending Videos Dataset**, 
which contains daily records of trending YouTube videos from multiple regions.

Each row represents a video that appeared on YouTube’s trending list on a 
particular day.

### Description of Columns
- `video_id` : Unique identifier for each video  
- `trending_date` : Date when the video trended  
- `title` : Title of the video  
- `channel_title` : Name of the YouTube channel  
- `category_id` : Numeric ID representing the video category  
- `publish_time` : Timestamp when the video was published  
- `views` : Number of views  
- `likes` : Number of likes  
- `dislikes` : Number of dislikes  
- `comment_count` : Number of comments  
- `comments_disabled` : Whether comments are disabled  
- `ratings_disabled` : Whether likes/dislikes are disabled  
- `video_error_or_removed` : Indicates if the video was removed or unavailable  
- `description` : Video description (may contain missing values)

### Additional Files
The category names were mapped using a separate JSON file containing 
category IDs and their corresponding names.
Link - (https://www.kaggle.com/datasets/datasnaek/youtube-new?select=US_category_id.json)

## 🔍 Key Insights
- Music category videos show the highest like-to-view engagement ratio.
- Videos with comments enabled receive significantly higher engagement.
- Videos published during evening hours (16:00–19:00) and towards the end of the week (Thursday–Friday) tend to perform better.

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📈 Visualizations
Bar charts were used to compare engagement across categories, comment availability, and publish timing.

## 📁 File
- `youtube_trending_analysis.ipynb` – Complete analysis notebook
