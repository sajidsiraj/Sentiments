# Sentiments
This is a table compiled for those interested in perofrming sentiments analysis without worrying about pulling information from different sources. The table contains information on 

    - subjectivity/objectivity of terms,
    - positivity/negativity of terms, and 
    - types of emotions contained in different terms
    
The table is constructed by pulling information from different dictionaries:

   Wordnet (https://wordnet.princeton.edu/)
   Sentiwordnet (http://sentiwordnet.isti.cnr.it/)
   SentiSense (http://nlp.uned.es/~jcalbornoz/resources.html)

I hope that using this table will save considerable amount of time and effort for analysts in their data preparation phase, therefore giving them more time to perform the actual analysis.

The table has following fields:

   word
         a concept which is explained in the last column (meaning).
         n.b. same word can have multiple meanings and therefore
         each meaning is mentioned as separate row in this table
         
   positivity
         a score between 0 and 1. 
         0 means no positive sentiment at all.
         1 means absolutely positive sentiment.
   
   negativity
         a score between 0 and 1. 
         0 means no negative sentiment at all.
         1 means absolutely negative sentiment.
   
   objectivity
         a score between 0 and 1. 
         0 means purely subjective term.
         1 means purely objective term.
   
   emotion
         type of emotion carried by the term
   
   partofspeech
         n NOUN
         v VERB
         a ADJECTIVE
         s ADJECTIVE SATELLITE
         r ADVERB
   
   meanings
         description of the word sense
         
