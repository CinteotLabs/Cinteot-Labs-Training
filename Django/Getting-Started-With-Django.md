# Django Tutorial

## What is Django
Web applications have become very popular today and as a result frameworks like Django have been created to allow developers to quickly design and develop applications without having to understand lower level concepts of web development such as websockets and HTTP protocols. Frameworks like Django abstract the lower level details and do the heavy lifting so that you don't have to. Think of it as a template that you can customize into anything you want.

## Getting started with Django

### Installing Python

*Note: In the following instructions you will see commands such as `python3 --version`. It is possible that on your machine that same command is equivelent to `python --version`. This is because as I write this I have multiple version of python installed and therefore need to specify which version of Python I would like to use. Do not worry about this now. If `python3` does not work then try `python`.

Likewise with Pip. If `pip3` does not work, try `pip`.*

Go to Python.org and download Python 3.8.2. Scroll to the bottom and select the appropriate installer based on your machine. Assuming you are on a windows machine you will use the `Windows x86-64 executable installer`.

```
https://www.python.org/downloads/release/python-382/
```

1. Select the bottom checkbox in the installer to `add Python to your PATH` in the installer! This will allow your machine to find the installation.<br><img src="img/py-installer.png" alt="drawing" width="500"/>
2. Then continue with all default settings by selecting `Install Now`
3. Verify the installation was successful
    - Open Command prompt on your machine
    - type `python3 --version`
   
        ```
        $ python3 --version
        Python 3.8.2
        ```
    - Now type `python3`
    
        ```
        $ python3
        Python 3.8.2 (default, Dec 21 2020, 15:06:04)
        [Clang 12.0.0 (clang-1200.0.32.29)] on darwin
        Type "help", "copyright", "credits" or "license" for more information.
        >>> print("Hello World!")
        Hello World!
        >>>
        ```  

**If you are here then you now have Python installed on your machine and are ready to use it!**
<br><br>
### Installing Pip
Pip is a package manager for Python. Because Python is so popular, there are thousands of tools available for you to use in your project - Django is one of them. To be able to use these tools you will need Pip.
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```
Then run the following command.
```
python3 get-pip.py
```

If done properly, you can do the following now.
```
$ pip3 --version
pip 21.0.1 from /usr/local/lib/python3.9/site-packages/pip (python 3.9)
```

<br><br>
### What we have
You now have Python installed on your machine and added to your PATH. In short, adding to PATH tells your computer where to look when it sees `python`.

You also have Pip which will allow you to use open source Python projects as your own - which is exactly what we will be doing with the Django package.

The tutorial assumes you have Django installed so we will take care of that step here in 1 command.
```
python -m pip install Django
```
The command above tells Pip to install a module called `Django`. When you install a module, you can then use that module in a project by importing it like this:
```
import django

<your code here>
```
<br>
Lets make sure that worked. Do the following from the terminal:
```
$ python3
Python 3.8.2 (default, Dec 21 2020, 15:06:04)
[Clang 12.0.0 (clang-1200.0.32.29)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import django
>>> print(django.get_version())
3.1.4
```
Your output may look a little different but should be almost identical. 

<br><br>
## Now what?
You are ready to begin your first Django application! There are endless tutorials to follow but we picked one that will cover what you need to know without overloading the details while you are starting out.

The tutorial is simple but covers all the basics of how to use Django and creating your first app. It will cover:
```
1. Installing Django
2. Creating your first Django project
3. Creating apps within the project
4. Defining URLs
5. Writing views to handle user requests
6. Database tables and queries
7. Writing HTML and CSS to design to webpage that users will see
8. How to serve your project locally so you can actually use the app you built
```
 
[Your first Django Application](https://www.pythonistaplanet.com/to-do-list-app-using-django/)
 
<br><br>
## Want to keep going?
When you are finished with your first app, you will have seen a lot of the cool features that Django has to offer. You also have your first web application done!!! Using what you have built, you can customize the design using CSS to style your webpage.

### Exploring CSS
If you haven't worked with CSS before, I recommend you play with it a bit because there isn't a website on the planet (except yours...) that doesn't have some CSS. I recommend [w3schools.com](https://www.w3schools.com/css/default.asp) to learn it! They have a linear progression through CSS that will move from beginner to advanced concepts and they include short quizzes along the way.

W3Schools also has thorough lessons for so many other languages that you can explore beyond CSS. 

[HTML Tutorial](https://www.w3schools.com/html/default.asp)<br>
[CSS Tutorial](https://www.w3schools.com/css/default.asp)<br>
[JavaScript Tutorial](https://www.w3schools.com/js/default.asp)<br>
[Python Tutorial](https://www.w3schools.com/pyth0n/default.asp)<br>
[Bootstrap Tutorial](https://www.w3schools.com/bootstrap4/default.asp)<br>
[jQuery Tutorial](https://www.w3schools.com/jquery/default.asp)<br>
And Much More ...

*The tutorials linked above are **ALL** tools that we use for the Voice Engine project. That may seem like a lot... and it is. Web development has SO many tools, languages and frameworks that can be used - each to accomplish different things. No one can master all of these and no one expects you do either. This resource is meant to introduce you to the basics and expose you to various aspects of what we do.*
 
<br><br>
At this point you have seen **ALOT** of very cool, and likely, new technologies. Practice makes perfect(ish) and that is exactly what you have been able to do. 

Having covered the basics, you are now ready to start contributing!
