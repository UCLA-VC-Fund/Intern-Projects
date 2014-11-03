Intern-Projects
===============

2014-2015 UCLA VC Fund Software Engineer Intern Program

##Creating a Database of UCLA Tech Industry Alumni

There are several sources of publicly-available tech industry data, namely CrunchBase and AngelList. Your goal is to programmatically build a list of UCLA alumni accessible to members of the UCLA VC Fund.

You don’t need a large dataset for this first project. The goal is to demonstrate your ability to connect multiple disparate technologies into one useful deliverable for UCLA VC Fund members.

###Steps:

1. Use the [AngelList search API](https://api.angel.co/1/search?query=ucla&type=User) to return a list of UCLA-affiliated users.
2. Query the AngelList User API for additional information on each user from the search API response.
3. Store all of the user information in a database of your choice (MySQL, MongoDB, PostgreSQL)
4. Create a simple way for non-technical users to view the contents of the database, preferably a web page.

Please host your code with an open source license (e.g. the [MIT License](http://choosealicense.com/licenses/mit/) publicly on Github in a repository named however you like. (Note: make sure not to commit your API keys or other credentials!)

If you have questions email me at alex@enplug.com.
