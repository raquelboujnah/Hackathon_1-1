Alonn,
Your Hackathon project is really great! I like the idea and the final result.
You used all the topics and tools we learned in class
The code is readable, clean, and well-structured with differents files, classes and functions.
One points I’d like to highlight:
This piece of code appears in almost all of your files:
connection=psycopg2.connect(database='Hackathon',
                            user='alonnbarthels',
                            password='310103',
                            host='localhost',
                            port='5432')

What we usually do is place these credentials in a .env file and use the dotenv module to load them from there. The .env file should look like this:

database=Hackathon
user=alonnbarthels
password=310103
host=localhost
port=5432

It’s also important to use .gitignore to prevent this file from being pushed to GitHub, as it contains sensitive credentials that should remain private.

You did an excellent job!
