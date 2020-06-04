# hybrid-question-answering
A question answering system using different QA model
The question answering system consists of 4 parts: 1 query classifier. 2 product-related QA model. 3 open domain QA model. 4 Meta-data related QA model.

# Query classifier.
A query will go into a rule-checking first to check if it starts with question words(what, how, when, where, can,...)
Then accordingly will be sent to two different SVM classifiers to predict which type the query is.
Query Type: 1 normal query. 2 product-related query. 3 open domain query. 4 meta-data related query

# Product-related QA model
Using community QA model.
