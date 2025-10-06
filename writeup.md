# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
 i learned alot about lists and how they store things, i am still confused as to how they work but i am getting the hang of it. i also learned alot about different funtion types and how they work and how to make them.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The user imputs a question, it can ask for an actor, a director, a title, or a year. the chatboat searches through the lists to find a match, once it finds a match to what the user inputted, the chatbot will return the missing informaiton. 
Ex: Who Directed the F1 Movie?
The chatbot searches the question for the title, F1, then searches the list until it finds F1, Then it searches for the director inside the list.



3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

Google searches work in a similar way. it finds patterns and then searches a large algorithm to return matching results. We can extend the amount of movies to find more information or we can ad more things like where to watch these movies and such.