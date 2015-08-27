# Leverage Azure Machine learning in SharePoint #

### Summary ###
The Text Analytics API, part of Microsoft Azure Machine Learning platform, allows devs to submit text to the Text Analytics API. The API then analyzes this text, and is able to perform sentiment analysis, or keyword extraction. For example, it is able to determine whether a sentence like “Azure Machine Learning is a very powerful tool” is positive or negative. Pretty cool!

In this sample (and related blogpost) I’m going to look at keyword extraction. I thought it would be really useful to integrate this with SharePoint in the following scenario:

Every time a user saves a content page (for example on the Intranet), the Text Analytics API is used to extract all the keywords from this page, and saves it to a different field in the content page. This information can then be used for automatic tagging, tag clouds, and generally improving the search experience.

For a detailed walkthrough, see the blog post: [http://www.spcaf.com/blog/leverage-azure-machine-learning-in-sharepoint/](http://www.spcaf.com/blog/leverage-azure-machine-learning-in-sharepoint/). 
