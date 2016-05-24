# technical-test

For this exercise I used HTML, CSS, Python-cgi and Javascript.

One of the first problem encontered is the compatibility between python 2.7 (which I used to solve the exercise 2) and Python 3.4 which is the python that is configuered on my apach for python cgi to work properly. 

I added a some python line to check the value given by the user. By construction only an integer can be entered in the form field but I still needed to check that this value was greter than 0.

I used Javascript to modify the page according to the value given by the user. I used the json python library create a string recognized by JSON. Then within the javascript the this string is transformed to the JSON format. It cant then be used to display the results.

web link to the webservice: 
