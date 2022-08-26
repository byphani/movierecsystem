# movierecsystem
A content based movie recommendation system I made. This is just the skeleton of the project.. The real fun begins when I deploy this on heroku :)


This type of content based recommendation systems are quite simple to understand and implement. 
It's pretty much self explanatory. The user is recommended movies based on content they have chosen to watch.
This depends on various factprs like :
     1. genre
     2. Cast
     3. Director
     4. Title
     5. budget
 
 
 In the EDA, I have extracted the info about the same.

I have created a tags column that has the above info.

Then I used CountVectorizer and fit_transform to basically convert the words to vectors and store the values in form of arrays.
The CountVectorizer belongs to the sklearn library.

Then I take the index of any movie and find its similairty score with other movies and sort it in ascending order. Then I take the indexes of the top 5 simiiarity scores and output their actual title.

Thats it!
