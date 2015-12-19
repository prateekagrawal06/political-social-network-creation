
    ##Collecting a political social network
    
    In this assignment, I've given you a list of Twitter accounts of 15 U.S. presedential candidates.
    The goal is to use the Twitter API to construct a social network of these accounts. We will then use the [networkx](http://networkx.github.io/) library to plot these links, as well as print some statistics of the resulting graph
    
    1. Copy the files from this directory into the `asg/a1` folder of your private repository
    2. Create an account on [twitter.com](http://twitter.com)
    3. Generate authentication tokens by following the instructions [here](https://dev.twitter.com/docs/auth/tokens-devtwittercom)
    4. Add your tokens to the `twitter.cfg` file. (API Key == Consumer Key)
    5. Be sure you've installed the Python modules [networkx](http://networkx.github.io/) and [TwitterAPI](https://github.com/geduldig/TwitterAPI). Assuming you've already installed [pip](http://pip.readthedocs.org/en/latest/installing.html), you can do this with `pip install networkx TwitterAPI`
    
    OK, now you're ready to start collecting some data!
    
    I've provided a partial implementation below. Your job is to complete the code where indicated.  
    You only need to modify the 6 methods indicated by **#TODO**
    
    Your output should match the samples provided below.
