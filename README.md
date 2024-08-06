Python API Challenge

You will find my analysis split up between weather and vacation with my output documentation in the output_data file. I also added the map and hotel map plots as html in the output_data file as well. You will see 2 warning that arose from saving the himl file but the code still works. 

Our instructor stated the following in regards to the apikeys:
>  I apologize. I should have told you the homework was wrong. Where it asks you to create a config.py or api_keys.py, please don't. Please just create a .env file as you have seen in the classes. Creating a file like the api_keys.py is a very bad idea and not something you want to take with you into the job market or workplace. It's too easy to accidentally check in your keys and push them to GitHub.
Whenever you have keys, use environment variables, which is what the .env file and the load_dotenv() function are doing for you.
4:17
If you create a function using Python in Microsoft Azure Functions or Amazon AWS Lambda, you won't need a .env file, but you will need to put your keys in: 1) a secure key vault, or 2) in environment variables in the tool environment, but definitely NOT in your code or in a config.py or api_keys.py.
