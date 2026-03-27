AI Personal Chatbot (Portfolio Assistant)

A web-based chatbot that answers user queries about my profile, experience, skills, and projects using Natural Language Processing (NLP) techniques. 

Check out the live website https://chatbot-app-1-w6ej.onrender.com/

Begin the conversation by typing “Hi” or “Hello” to activate the chatbot.


Features
* Interactive chatbot interface
* Answers questions related to career, skills, and experience
* Uses NLP-based similarity matching
* Maintains conversation history
* Provides fallback response for unknown queries

Tech Stack
* Python
* Flask
* Pandas
* Scikit-learn
* HTML, CSS

Predefined Question-Answer Dataset
* Predefined dataset stored in a CSV file
* Contains question-answer pairs related to:
    * Profile and introduction
    * Work experience
    * Technical skills
    * Projects
    * Career goals

How It Works
1. User enters a query in the chatbot interface
2. Input text is cleaned and converted to lowercase
3. Query is compared with stored questions using CountVectorizer
4. Cosine similarity is calculated between user query and dataset
5. Similarity scores are computed for all questions
6. Best matching answer is selected based on highest score
7. If no match exceeds threshold:
    * Displays fallback response
8. Chat history is updated and displayed

Use Cases
* Personal portfolio assistant
* Resume-based chatbot
* FAQ automation system
