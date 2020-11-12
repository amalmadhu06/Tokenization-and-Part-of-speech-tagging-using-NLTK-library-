# Tokenization-and-Part-of-speech-tagging-using-NLTK-library-

# 1. Tokenization Using NLTK
# importing the nltk library 

import nltk

# creating a sentence 
sentence1 = "Here we are trying to do tokenization using nltk library. Lets add some $ symbols also "

# creating tokens using library 

tokens = nltk.word_tokenize(sentence1)

# printing the tokens 

print("Tokens : ", tokens)

# It has considered . $ and symbols as a tokens

# We have tokenized the sentences now. Lets try part of speech tagging now...


# ## 2. Part of speech tagging using NLTK


# We have already imported the nltk library. 



# creating a sentence 

sentence2 = "Here we are trying to do tokenization using nltk library. Lets add some $ symbols also "

# We have used the same sentence to see the change 



# creating tokens using library 

tokens = nltk.word_tokenize(sentence2)

# printing the tokens by part of speech tagging 

print("Part of speech :", nltk.pos_tag(tokens))

# we have received the outputs as we want 

