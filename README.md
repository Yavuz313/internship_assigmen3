Internship Assignment 3
Mehmet Yavuz Gunduz

---

## Mad Libs Generator

This Python program generates a fun and interactive Mad Libs game themed around data science. Mad Libs is a word game where players fill in blanks in a story with different types of words (e.g., nouns, verbs, adjectives) to create a humorous story.

### How It Works

1. **Story Template**: 
   - The program starts with a predefined story template featuring placeholders for different word types such as adjectives, nouns, verbs, and adverbs. In this case, it's themed around data science with the character named Mehmet.

2. **Word Types and Examples**: 
   - The user is prompted to enter specific words based on predefined categories with examples:
     - Adjectives (e.g., funny, smart, fast)
     - Nouns (e.g., dataset, algorithm, model)
     - Verbs (e.g., analyze, train, predict)
     - Adverbs (e.g., quickly, carefully, excitedly)

3. **User Input**:
   - The program uses `input()` to get user input for each word type. It guides the user by showing examples of valid inputs.

4. **Generating the Story**:
   - Once all words are collected, the program substitutes them into the story template using Python's string formatting (`format()` method).

5. **Output**:
   - Finally, the completed Mad Libs story, filled with the user's words, is displayed to the user.

### Example Output

If the user enters words like "smart", "algorithm", "powerful", "analyze", and "excitedly", the generated story might look like this:

```
In the world of data science, there was a smart data scientist named Mehmet. 
Mehmet loved to analyze algorithm data. 
One day, Mehmet developed a powerful algorithm that could analyze. 
The results were so impressive that Mehmet let out an excitedly cheer!
```

### Usage

- Clone this repository.
- Run `mad_libs.py`.
- Follow the prompts to input words based on the provided examples.
- Enjoy the funny and personalized Mad Libs story generated!

This project is designed to showcase basic Python programming concepts such as string manipulation, user input handling, and simple control flow using a fun and engaging application.

---
