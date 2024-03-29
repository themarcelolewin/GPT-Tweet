![Creative Spark AI - Logo - Rectangle (1280 × 640 px)](https://user-images.githubusercontent.com/55222201/209981245-3a0e6a81-df6e-42a3-bd8b-7caac67c7086.png)
# GPT-Tweet
Creates a Twitter Bot that Posts Random AI (Artificial Intelligence) Terms using OpenAI GPT-3.  For more information, check out [Creative Spark AI](https://www.creativespark.ai). Below are the steps I took to get this script completed.
#
- **Create Web Accounts**
    - Create a developer account in Twitter
    - Create a developer account in Open AI
- **Create API Keys**
    - Create app in Twitter Developer
    - Make sure app has read/write access
    - Get Consumer Key, Consumer Key Secret, Access Token and Access Token Secret from Twitter.
    - Create a secret key in OpenAI
    - Create a config.ini file and store all those there.  If you are going to push to GitHub, make sure you gitignore this file. Don’t share this!
- **PIP Install Libraries**
    - Tweepy
    - OpenAI
- **Python Code**
    - Import libraries (Tweepy, OpenAI and ConfigParser)
    - Import secret keys for all APIs
    - Set up client for Twitter
    - Set up client for OpenAI
    - Send a prompt to GPT-3 language model.
    - Send response from GPT-3 to Twitter (as a tweet).
- **Schedule Daily Task**
    - Use your favorite online service to schedule tasks that run Python scripts.
    - I'm using [Python Anywhere](https://www.pythonanywhere.com)
