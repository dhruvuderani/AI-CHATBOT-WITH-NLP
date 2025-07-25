# AI-CHATBOT-WITH-NLP
COMPANY: CODTECH IT SOLUTIONS
NAME : DHRUV UDERANI 
INTERN ID: CT08DN331
DOMAIN : PYTHON PROGRAMMING
DURATION : 8 WEEKS
MENTOR: NEELA SANTHOSH

##This Python-based chatbot is designed to provide informative and interactive responses specifically about Bayern Munich, one of the world’s most renowned football clubs. Leveraging natural language processing libraries such as spaCy and NLTK, the chatbot recognizes user intent, matches questions semantically with relevant content, and delivers engaging responses—including jokes.

At its core, the chatbot combines multiple strategies to ensure versatile interaction. It begins by detecting predefined intents like greetings, farewells, help requests, and expressions of gratitude through keyword matching (intent_keywords). Each intent corresponds to a set of responses (intent_responses) chosen at random for more natural dialogue.

For more specific questions, such as “Who founded Bayern?” or “When was it created?”, the bot uses a direct answer dictionary. This is a quick lookup for precise facts, ensuring quick and accurate replies without complex processing.

If a user asks a question outside the predefined intents or keywords, the chatbot performs semantic similarity matching using the large English model from spaCy (en_core_web_lg). It loads Bayern-related sentences from an external text file (bayern.txt), compares them to the user's input using vector similarity, and returns the most relevant match if it passes a confidence threshold.

To make interactions more fun, the bot also includes a joke module, randomly selecting a tech-related joke when prompted.

Finally, the chatbot runs in an infinite loop until the user types exit commands like "bye" or "quit". This simple architecture allows for expansion—developers can easily enhance it with more intents, deeper knowledge bases, or APIs.

This bot provides a great foundation for building customized, domain-specific assistants using Python and natural language processing tools.

NOTE: IF YOUR FILE DOESNT GET THE PUNKT DATA AND GIVES NOLOOKUP ERROR TRY DOWNGRADING YOUR NUMPY VERSION WHICH COULD AFFECT THE SPACY LIBRARY 

##OUTPUT
EXAMPLE INPUTS:
1. HELLO!
2. WHO ARE YOU?
3. WHEN WAS BAYERN MUNICH FOUNDED ?
4. WHAT IS THERE JERSEY COLOURS?
5. TELL ME JOKE
6. BYE
<img width="1085" height="223" alt="Image" src="https://github.com/user-attachments/assets/fb8f2b4b-323c-4fe3-bf3f-056af8cb83d1" />
