# AWS_Review_Analysis
The Original Dataset Consists more than 4 lakh rows. Itis become to difficult to upload the csv file and run the file due, to this reason. I am trained my model using 5000 rows or records.  
The Dataset consists ['overall', 'verified', 'reviewTime', 'reviewerID', 'asin', 'style', 'reviewerName', 'reviewText', 'summary', 'unixReviewTime','vote', 'image'] as columns in this I preferred two Independent columns ['reviewText', 'summary'] and one Dependent column['verified']. 
And I am concatenated two columns Independent columns and maked it as a new column and trained model using new column and 'verified' after processing the new column and performed Naive Bayes and MLPClassifier. 
And the accuracy is better for Naive Bayes Model than MLPClassifier Model.
