# ITE306_SAS19
REST API using Flask

STEPS in creating a web application that will say Hello and print the username :
Step 1:  Installation:
 We will require two package to setup your environment. virtualenv for a user to 
create multiple Python environments side-by-side. Thereby, it can avoid 
compatibility issues between the different versions of the libraries and the next will 
be Flask itself.
<virtualenv> pip install virtualenv
<Flask> pip install Flask
After completing the installation of the package, let’s get our hands on the code.
Step 2:  Save it with a file name myflask1.py.
Step 3:  Then go to the url given there you will seeing your first webpage displaying hello world 
there on your local server. Go to the url http://127.0.0.1:5000/
Step 4: @app.route('/hello/<name>') 
def hello_name(name): 
 return 'Hello %s!' % name 
STEP 4: Digging further into the context, the route() decorator in Flask is used to bind URL to a 
function. Now to extend this functionality our small web app is also equipped with another 
method add_url_rule() which is a function of an application object is also available to bind 
a URL with a function as in the above example, route() is used.
Modify myflask1.py and add the following lines of code then save it. Don’t forget to run
again the script.
Step 5: Go to the url http://127.0.0.1:5000/hello/<name>
Replace <name> with your name. Example: http://127.0.0.1:5000/hello/Juan
Step 6: Save your file.

STEPS in creating an HTML form and use the POST method to send form data to a URL.:
Follow this folder directory:
>pythontest (folder)
 > login.html (html file) 
    >login (folder)
        >myflask2.py (python file)
STEP 1: Now let’s create a html login page. Save this new file as login.html inside the
pythontest folder.
STEP 2: Create a new python script and save it as myflask2.py inside the login folder, this python 
script will create the server.
STEP 3: Go to your cmd and run the myflask2.py. After the development server starts running, open 
login.html in the browser.
Enter name in the text field and click submit button. Please notice the URL. Example Output: Output: “welcome subhajit”.
STEP 4: Save your file
