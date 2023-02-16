# Welcome to My Mr Clean
***

## Task
The problem is to create a program that extracts relevant articles based on a user's search. However, the problem is reduced to 
analyzing the content of a single Wikipedia article to see if it matches the search result.  

## Description
To solve the problem, I have made the following steps: 
- I have retrieved a wiki article that matches a user input
- I have cleaned the returned object(string) to get the plain text
- I have tokenized the text into individual words
- I have computed the frequency of each word and vizualized it in a histogram 
- I have removed insignificant words and vizualized it again

## Installation
To launch the program, you use the command 'python3 my_mr_clean.py'

## Usage
After running the program, the program will make a request to Wikipedia to access the article on "Ozone layer" using the library 'requests'.
    - It uses the revision API rather than extract or parser API's to access the whole content


### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
