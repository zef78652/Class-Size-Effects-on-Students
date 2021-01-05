## Purpose
Self Organizing Maps (SOM) are a type of neural network that is trained using unsupervised learning algorithm for the purposes of demensionality reduction and data clustering. The notebook discusses the intuition and theory behind SOM, and applies it to a publicly avaiable education data set from the state of Tennessee to classify each student as being weak, average, or gifted based on their characteristics. 

## Data
From 1985-1989 the state of Tennessee conducted a experiment to examine the causal impacts of smaller class sizes on student test scores. The data set from this study is now publicly available and can be found on [dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/10766). I use a subset of this data set to apply SOM. In particular, I keep 6 variables for the grade 1 students, free or reduced lunch status, school absences, math, reading, listening, and word study standardized test scores. I only keep students that non-missing data for each of these variables. 


## References
[Video on using SOM for Classification of Input Data](https://www.youtube.com/watch?v=H9H6s-x-0YE)

[Tutorial on SOM with some code](http://www.ai-junkie.com/ann/som/som1.html)

[Lecture Slides on SOM](http://www.cs.bham.ac.uk/~jxb/NN/l16.pdf)
