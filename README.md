Part 1 Description:

The first part of the Cybersecurity Awareness Chatbot project is a basic command-line application designed to introduce users to essential cybersecurity concepts in a friendly and interactive way. Upon launch, the chatbot greets users with a voice message using a WAV file and displays an ASCII art image of a locker to create a thematic visual experience. The chatbot allows users to ask questions about common cybersecurity topics such as phishing, safe passwords, suspicious links, and malware. It uses keyword recognition to match user input with predefined responses, ensuring that relevant information is shared in a simple, understandable manner. The console interface is enhanced with color-coded text—blue for user input and green for bot responses—along with clean dividers and borders to maintain a neat appearance. The chatbot also personalizes responses by addressing the user by name and presents a clear opening prompt to guide the interaction.

How to Run the Chatbot:

To run the chatbot, ensure you have the .NET SDK or a suitable C# compiler installed on your system. Open a terminal or command prompt and navigate to the folder containing the chatbot source files. Compile the chatbot using the appropriate build command (e.g., dotnet build if you're using a .NET project). Once compiled, execute the program with dotnet run or by launching the compiled executable file. Make sure the WAV greeting file and ASCII art text file are placed in the correct directory as specified in the code. When the program starts, it will greet the user with sound, display the ASCII logo, and prompt with “Ask me a question or press exit to enter.” Users can then interact with the bot by typing cybersecurity questions, and the bot will respond accordingly. Version control is managed using GitHub, and a CI pipeline is set up to ensure consistent and error-free builds during development.

# Cybersecurity_Awareness_bot_Part2
Welcome to Part 2 of the POE get ready to be amazed by the power of AI.

The Cybersecurity Assistant Chatbot is a console-based AI chatbot designed to help users with cybersecurity-related questions.
It provides personalized responses based on the user's name and interests, remembers conversation history during the session, 
and offers predefined tips on topics like passwords, scams, and malware. 
The bot integrates with the Azure OpenAI API to generate context-aware responses and even suggests improvements based on user inactivity.

Key features include sentiment-aware responses, a fuzzy matching system to handle minor spelling errors, 
and a 15-second inactivity timer that offers personalized advice.
The chatbot also allows users to export chat history as a text file. 
It's a helpful tool for anyone seeking cybersecurity guidance,
offering practical tips and expert advice throughout the conversation.

This chatbot leverages Azure OpenAI for smart responses, tracks user sentiment, and provides tailored advice.
It also includes a spell-checking system and allows users to request summaries of their conversations.

10 Things You Need to Know:

1.Personalized Responses: The bot uses your name and interests to provide tailored responses.

2.Context Memory: It keeps track of conversation history within a session to maintain context.NB, the bot will only answer once questions like what is a pin and after 
it responds you ask it how can i apply it to my device because the AI has a limit you can overload it once if you want to ask it again like 
what is a firewall and after it responds you ask it how does it work you must first end the program and start afresh.

3.Predefined Tips: Offers quick advice on common cybersecurity topics like passwords, scams, and malware.

4.Sentiment Analysis: It detects emotional tones (e.g., worry or curiosity) and adjusts responses.

5.Inactivity Timeout: After 15 seconds of inactivity, the bot offers personalized cybersecurity advice.

6.Spell Correction: It detects common misspelled words and offers corrections.

7.Levenshtein Distance: Uses fuzzy matching to handle typos and slight variations in user input.

8.API Integration: The bot interacts with the Azure OpenAI API for context-aware responses.

9.Conversation Summary: You can request a summary of your conversation at any time.

10.Chat Export: At the end of the session, you can export the entire conversation to a text file.










