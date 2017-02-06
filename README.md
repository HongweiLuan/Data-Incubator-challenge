# Data-Incubator-challenge
###I am a tennis lover and I need a tennis racket but I live in a small town. There is no supplier nearby and I don't want to run 30 miles for a 5-dollar band. I searched for it on Amazon. Amazon is a really great place where we have a ton a different, highly rated tennis rackets. So how do I choose one? Well there are many aspects of rackets and many aspects that make them great. What I really care about is power and stability of the racket. The reviewing scores are not very helpful becasue they are not specific and detailed. The reviews may be a better criteria. If I look at a racket review, it will talk about different aspects of the racket. So for example, a specific review might have a sentence that says something like, the experience of using a racket was excellent. What does this tell me? Well if I look at this sentence, the sentence is positive about the experience of using this racket. Then there might be another sentence that says, my son tried the racket and the texture was pretty forgettable. What does that mean? The texture, forgettable. Don't want to use it. But I'm not going to buy rackets for texture, I don't care about this sentence in the review. On the other hand, the same racket might say, the power was great, it was the best racket I ever used. Now that says about the power, which is the thing I care about the most with respect to that racket I choose. So every review has different aspects and different sentences. I would like capture a sentiment of each sentence so I can understand if it's good with respect to racket which is what I care the most about. So for each review, I'm going to classify it between a positive sentiment and a negative sentiment. Also, different words have different sentiment meanings. For example, excellent, great, and good have different sentiment meanings. I want to find which words are most positive for a product review. That's my task. I will start with baby staff because one friend of mine wants a baby formula and asked me select for him. 
###I used python to do classification on baby product review data from amazon. First, I removed punctuation using Python's built-in string functionality and computed word counts (only for the important_words first). Second, I split the data into train and test data. Then I trained the data with logistic regression and find the 5 most positive and negative words in reviews. 
