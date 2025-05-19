# Sentiment-analysis
This project focuses on basic sentiment analysis and aspect identification for  review data. The goal is to extract both the overall sentiment and specific  product-related aspects from a limited dataset. 
Key points of the application include: 

● Sentiment Analysis: 
Uses rule-based scoring (VADER and custom amplifiers/negators) to 
assign a sentiment polarity score to each review, capturing emotional 
tone.

● Aspect Identification: 
Applies part-of-speech tagging (via a trained HMM model) to extract 
key nouns and associated adjectives that represent product aspects. 

● Aspect Scoring: 

Two approaches are used: 

  ○ Polarity-based scoring using sentiment weights of adjectives.
  
  ○ Frequency-based scoring using unigram probabilities to reflect 
  how strongly a word is associated with the review context.
