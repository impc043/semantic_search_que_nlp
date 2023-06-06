# semantic_search_que_nlp

## General Information
- This project based on NLP task which help to extract/print similar top 5 questions from famous ELI5 dataset. 
- for example QUE: "car engine optimal temperature":
- Result:
Top 5 Similar Questions:
1. Why is it recommended we warmup our vehicles on colder days?
2. Why do (a lot of) cars get optimal fuel efficiency at 55-60 mph/88-95 kph??
3. New irons which have no variable temperature setting
4. Why is 350 degrees farenheit the most common temperature for most recipes?
5. Why do engines/motors sometimes have a hard time starting up in colder weather?

## How to use:
you need to change the code on ``step 4: query processing`` of `semantic_search_que.ipynb` file, and provide your own question
``NOTE``: We haven't integrate it with ``redis vector db`` yet.
``Further Development``: We will develop command line tool for easy to use rather than changing the code itself. 
## Technologies Used
- numpy 
- pandas 
- spacy
- redis
- annoy
- NLP

## updated version
- https://github.com/impc043/Semantic_Search_NLP_v2#result
## Contact
Created by [@impc043] - feel free to reach out!
