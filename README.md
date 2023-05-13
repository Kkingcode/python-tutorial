# python-tutorial
The code provided is written in Python and is used to count the number of times each unique word appears in a list called 'words'. 

First, an empty dictionary called 'count_occur' is created. Then, the code loops through each word in the 'words' list. For each word encountered, the code checks if that word is already a key in the 'count_occur' dictionary. If the word is already in the dictionary, the code increments the value associated with that key by 1 (i.e., incrementing the count of occurrences of the word). If the word is not yet a key in the dictionary, the code adds it as a key with a value of 1 (i.e., indicating that it has occurred once so far).

Finally, the code prints out the resulting dictionary, which shows the unique words and the number of times each word appears in the original 'words' list. This output is "Unique words and occurrences (case sensitive):" followed by the 'count_occur' dictionary. Note that the output is case sensitive, which means that words with different capitalization will be counted as separate words.
