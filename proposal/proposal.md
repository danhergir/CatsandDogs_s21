---
title: "Proposal"
output: html_document
---


1. Who is the client?

    The client in our case would be the library. The library is trying to check out more books so we need to help with it.

2. Proposals on the sets of features we will need to develop from our base data.
 
    The library is trying to maximize book space and people getting what they need when they come in.
    We will look at which books get potentially checked out more. 

    First we will start with physical books since those will most likely cost more and will take more space than ebooks. Technically I am assuming that ebooks have unlimited space (but not unlimited resources)
    To understand these we will use graphics (maybe a histogram) and group by different ages. First we will see which ages do more frequntly visit the library. Then see what genres of books get checked out more from one or two group ages. 
    Then we see the most influental authors in those particular genres that we have chosen. In our dataset those authors will have more books checked out. Usually the tendency is that people who have liked one specific author will continue buying from that one until the author stops producing quality books.

    Then we filter the data for ebooks and if we have more time we will look into ebooks and how often they are checked out.

3. External data source ideas (links to data found would be great)


4. Details on the target/label you think we are predicting and how you  will build that variable.

    Target variable ~ number of checkouts
    other variable ~ genre, author, year of production

5. Ideas on how the client will use the tool.

    The client will hopefully use the tool to decide on what books will buy for the next year so it can maximize it's resources.



