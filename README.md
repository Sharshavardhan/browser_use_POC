Author for POC & Documentation : Harshavardhan Reddy Sivadi

Step 1 – create a new folder, install latest python version & click on ADD TO PATH
NOTE : in VS code, add Microsoft python extensions
Step 2 – open the terminal and run the following command “pip install uv”
Step 3 – run the command “uv venv --python 3.11”
NOTE for windows activate the virtual environment 
Step 4 – run the command “.venv\Scripts\activate”
Step 5 – Install the dependencies: “uv pip install browser-use”
Step 6 – install pytest plugin  “pip install pytest-playwright”
Step 7 – install playwright “playwright install”
Step 8 – install browser use  “pip install browser-use”
Step 9 – install langchain “pip install langchain_openai”
Step 10 – create a “.env” file in same folder and provide following information. Here you need to setup your API key for antropic/OpenAI
“OPENAI_API_KEY=<YOUR_OPENAI_KEY_PAID_VERSION”
ANTHROPIC_API_KEY=
# Set to false to disable anonymized telemetry
ANONYMIZED_TELEMETRY=true
# LogLevel: Set to debug to enable verbose logging, set to result to get results only. Available: result | debug | info
BROWSER_USE_LOGGING_LEVEL=info“
NOTE : rename the example.py.txt file to example.py file
Step 11 – create a example.py file (AI AGENT) and fill it with sample code from : https://github.com/browser-use/browser-use/tree/main/examples/use-cases 
Step 12 – to switch between models(OpenAI, OLLMA, GROK, KIWI, GEMINI etc) use the documentation : https://docs.browser-use.com/customize/supported-models 
Step 13 – run the agent with command “python example.py”




task 1
Go to Reddit, search for 'browser-use', click on the first post and return the first comment.

task 2
'Go to the Greece MFA webpage via the link I provided you.'
'Check the visa appointment dates. If there is no available date in this month, check the next month.'
'If there is no available date in both months, tell me there is no available date.'
		

Task 3
Find the founders of browser-use and draft them a short personalized message

Task 4
Navigate to 'https://en.wikipedia.org/wiki/Internet' and scroll to the string 'The vast majority of computer'

Task 5 - Amadeus specific airlines - flight search
Find the lowest-priced one-way flight from Cairo to Montreal on February 21, 2025, including the total travel time and number of stops. on https://www.google.com/travel/flights/
