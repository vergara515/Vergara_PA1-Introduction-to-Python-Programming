# Experiment 1: Introduction to Python Programming
This respiratory contains Python codes for the given programming problems. Furthermore, solutions and explanations for each problem are written here.

# Alphabet Soup Problem
Function: alphabet_soup(input)

Description: The problem used 'def' to define the function alphabet_soup, which contains the necessary codes for sorting the strings alphabetically. 'input' would be the argument passed whenever the function is called.

Function: ''.join(sorted(input)) and 'return'

Description: Sorts characters in a string and joins them back together. Moreover, 'return' was used to return the sorted string.

Example: print(alphabet_soup("hello"))

Output: ehllo

# Emoticon Problem
Function: emotify(input), emoticon_dict = {}, and sentence = input.split()

Description: The problem used 'def' to define the function emotify(input), which contains an emoticon dictionary. 'input' would be the argument passed whenever the function is called. The dictionary was defined using emoticon_dict = {}, which contains the strings and their corresponding emoticon. A split function was also used by using sentence = input.split(), which splits the words into the given sentences and, 

Function: emotified = ' '.join(emoticon_dict.get(word, word) for word in sentence) and 'return'

Description: Copies word for word the given sentence, replaces the keywords according to what is contained in the dictionary, and joins them together. Lastly, it is returned by using 'return'.

Example: print(emotify("Make me smile"))

Output: Make me :)

# Unpacking List Problem
List: writeyourcodehere = [1, 2, 3, 4, 5, 6]

Description: Contains the list of variables to be unpacked

Function: *middle

Description: Unpacks the elements between the first and last into the middle

Example: [1, 2, 3, 4, 5, 6]

Output: first: 1   middle: [2, 3, 4, 5]   last: 6
