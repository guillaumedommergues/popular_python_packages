# Which python packages and objects are used the most?

Anyone interested in learning Python can easily find hundreds of tutorials on the web. However deciding what to learn, in which order, remains a difficult question. In particular, which packages are popular right now? For a beginner, the choice between urllib and requests may not seem obvious at first.

In the same way, most package documentations are organized in an alphabetical order. It's easy to find the documentation for a specific function you know. It's a bit harder to know which functions you must learn to become efficient in using this package. 

We want to help to answering these questions by looking at which packages and objetcs are used by top Python users now. 

# Method
Specifically, we use the Github API to get the python scripts of the most starred 40 repository for each month between November 2016 and October 2018. We limit ourselves to smaller projects (less than 20 .py files). We parse the scripts (3800 files from 460 repositpries) to localize the imports and their uses. 

# Results
We combine the top packages and objects imported from these packages in the csv file in this repository. 

For instance, we see requests may be easier to use than urllib, but urllib was still used a bit more in the past two years. Also, we see that deep learning packages are extremely popular among highly rated projects.


# Requirements
Running this Notebook requires Python 3, a github API username and token, both of which are available for free on the Github website. 

