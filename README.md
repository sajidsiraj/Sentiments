# This is a repository for sentiments analysis tutorial using KNIME.
Our aim is to become familiar with workflow-based analytics and to performing some common data analytics tasks. We will be using KNIME Analytics software for this purpose. Once you are comfortable in using KNIME, you can easily migrate to any other workflow-based tool, for example, RapidMiner, SAS Analytics etc. 

We used KNIME version 3.3, if you are downloading the latest version (3.5+), please ensure that you download all extensions (File Menu -> Install KNIME Extensions)

# Sentiments
This is a table compiled for those interested in perofrming sentiments analysis without worrying about pulling information from different sources. The table contains information on 

    - subjectivity/objectivity of terms,
    - positivity/negativity of terms, and 
    - types of emotions contained in different terms
    
The table is constructed by pulling information from different dictionaries:

   - Wordnet (https://wordnet.princeton.edu/)
   - Sentiwordnet (http://sentiwordnet.isti.cnr.it/) 
   - SentiSense (http://nlp.uned.es/~jcalbornoz/resources.html)

I hope that using this table will save considerable amount of time and effort for analysts in their data preparation phase, therefore giving them more time to perform the actual analysis.

The table has following fields:

   1. word: a concept which is explained in the last column (meaning). n.b. same word can have multiple meanings and therefore each meaning is mentioned as separate row in this table.
   
   2. positivity: 0 means no positive sentiment at all. 1 means absolutely positive sentiment.
   
   3. negativity: 0 means no negative sentiment at all. 1 means absolutely negative sentiment.
   
   4. objectivity: 0 means purely subjective term. 1 means purely objective term.
   
   5. emotion: type of emotion carried by the term
   
   6. partofspeech: n NOUN, v VERB, a ADJECTIVE, s ADJECTIVE SATELLITE, and r ADVERB
   
   7. meanings: description of the word sense
         
