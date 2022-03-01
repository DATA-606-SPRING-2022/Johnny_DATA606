EDA directory provides a storage for source materials that are useful to understand methodologies.
## Exploratory data analysis

### Notes from 20220227
I have done extensive EDA working on exploring Google search engine scripting to develop scripts to pull down urls from google of articles published on particular dates.  Ideally I'm looking for scripting to pull up to 100 urls per day for 2 years into a dataframe, store this to disk and run newspaper3k scripting to parse the records.

I'm working on also processing the data frames using Spacy or gensim to produce word vectors of the parsed data.
My work has not all been migrated to this directory structure since I am very inexperienced in making multiple python development file systems.  

I believe that I am able to push data from my laptop directory structure into github and work through the differences in working directly in github on the web and github repositories on my laptop.  I have had issues every day since I started working in this directory.  I believe that this is up-to-date as of today.  

currently my google script work attepts have been met woth blocking on my googlesearch script and my google developer api script.  

Limitations involve a top limit of 100 responses at 10 responses per page. with a max of 10 pages allowed.

It was possible to use a sort function in the script to focus output for a specific day.  This was working but I was blocked after 250 urls as a bot.  

Moving to the google developer api, the script was working but the sort command fails and there is no explanation to resolve the frustration.

I have some data from my previous class that was from twitter.  I can probably use it for the topic modeling work if the google work continues to fail.  It may be possible to explore long timeouts like 30 seconds to see if blocking continues.  I'm hopeful but frustrated.

I will be exploring a paid API access to see if I gan just pay for my target of 150k urls. over 2 years.

I am also looking into the newspaper3k package.  I have a list of about 75 top level domains that I want to exp0lore with the newspaper3k package.  Hopefully I can either get direct urls through the google search engine process and process them with the newspaper package, or additionally, pull down the newspaper structure from these kinds of news sources and explore articles directly.

I am working to migrate these efforts into the project directory to upload it into the github.  There are a few gotchas such as API keys embedded in scripts.  I ran afoul of this with github disabling my API keys since they were found in a file in github.  

Lots of learning curves.  Please be patient with me.  

One I have a better understanding of the newspaper package and the two processes, I will develop a data structure to contain the preprocess files with the target article urls, process the articles with newspaper and save the resulting data in a set of dataframe files pickled onto the file system.  

Since this is iterative I am working to first understand how the newspaper package parses articles, crawls newspapers, and how to capoture the parse results into files for followon word2vec processing.

I'll try to move to migrate these efforts into this filesystem so that the work is visible and progress will be more apparent.

This effort is a little ambitious in that the data is not a canned data set, but rather a compilation of datasets that I have to collect.  If I am unsuccessful at getting google data I will punt and work with twitter data.  I'm not beaten quite yet.  

## Notes 20220228
Running the google api script with a pause of 30 seconds.  Hopefully it will allow me to have a few more days of results.  The search criteria is AAPL.  There are a few other search terms I want to try to get stock articles.
So far so good... I got a few more days so far.  i only got 5 days of queries done.  HTTPError: HTTP Error 429: Too Many Requests 

will try 300 seconds next.  Not sure how much time to back off.  Sop far so good.  It ran another day.  I'll let this run and go to sleep.  Maybe it will work.  If not I'll try 600 seconds.  I've seen some scripts say they have exponential backoffs and retries.  I may have to explore those.  Tis is very distracting to my purpose of getting the actual data to work with. This part of data science sucks!

I'm starting on a topic modeling effort.  Looking at gensim Latent Dirischlet Allocation LDA topic modeling.  The PYldavis script looks promising.  