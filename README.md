#WebSearchEngine

Tech Stack includes JAVA, JS, BootStrap and Jquery. 

Modules and algorithms: 
 1. Web Crawler - which is gathering the string tokens from a URL recursively. Currently, we have limited the scope of URL crawling nodes to 10,000. But can easily be changed. 
 2. Inverted Index - We have used the inverted Index to store the Data Dictionary from Web Crawler Output. This is implemented using Trie(for Data Dictionary) and HashMap(Occurrences of Strings in a URL). 
 3. Ranking of Webpages: QuickSelect Algorithm is used to rank the top 5 web pages for the searched String.
 4. Autocompletion of words using Trie.
 5. Correct Word recommendation using EDIT Distance Algorithm.
