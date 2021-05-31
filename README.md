# Recommender_system

# Introduction

Over time, we rely more and more heavily on online platforms and applications such as Netflix, Amazon, Spotify etc. we are finding ourselves having to constantly choose from a wide range of options.

One may think that having many options is a good thing, as opposed to having very few, but an excess of options can lead to what is known as a “decision paralysis”. As Barry Schwartz writes in The Paradox of Choice:

“A large array of options may discourage consumers because it forces an increase in the effort that goes into making a decision. So consumers decide not to decide, and don’t buy the product. Or if they do, the effort that the decision requires detracts from the enjoyment derived from the results.”

Also resulting in another, more subtle, negative effect:

“A large array of options may diminish the attractiveness of what people actually choose, the reason being that thinking about the attractions of some of the unchosen options detracts from the pleasure derived from the chosen one.”

An obvious consequence of this, is that we end up not making any effort in scrutinising among multiple options unless it is made easier for us; in other words, unless these are filtered according to our preferences.

This is why recommender systems have become a crucial component in platforms as the aforementioned, in which users have a myriad range of options available. Their success will heavily depend on their ability to narrow down the set of options available, making it easier for us to make a choice.

# Outline:

This post starts by exposing the different paradigms in recommender systems, and goes through a hands on approach to a content based recommender. I’ll be using the well known Research papers dataset from ICMLA which has abstracts and keywords, and show how we could recommend abstracts based on their features.

# Types of recommender systems:

Most recommender systems make use of either or both collaborative filtering and content based filtering. Though current recommender systems typically combine several approaches into a hybrid system. Below is a general overview of these methods:

# Collaborative filtering: 

The main idea behind these methods is to use other users’ preferences and taste to recommend new items to a user. The usual procedure is to find similar users (or items) to recommend new items which where liked by those users, and which presumably will also be liked by the user being recommended.

# Content-Based: 

Content based recommenders will instead use data exclusively about the items. For this we need to have a minimal understanding of the users’ preferences, so that we can then recommend new items with similar tags/keywords to those specified (or inferred) by the user.
# Hybrid methods: 

Which, as the name suggests, include techniques combining collaborative filtering, content based and other possible approaches. Nowadays most recommender systems are hybrid, as is the case of factorization machines.
