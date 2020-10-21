# Short Answer Questions

Zachary Le
A00774311
Midterm for October 2020
BCIT

## Q1
Git is a locally installed version control tool used for a project's code history while Github is
a cloud based platform where developers can share projects. Git can be used to push code to a 
Github repo.

## Q2
A Branch is a divergance from the master/main code of the project that allows you 
to work on an isolated version. A branch can be created on Visual Studio Code with Git Enabled by
using a "Git: Create Branch..." command.

## Q3
A resource that cannot be found will return an HTTP 404, which is one in the 400 Series of
Client Error codes. It is not always permanent as the resource can be later uploaded.

## Q4
h2 will be red. The red style property takes precedence over the earlier
declarations of having pink assigned from the school id, purple of body 
and the green from the h2 class.

## Q5
Protocol: Determines the communication method the browser uses when sending and fetching resources.
Domain Name: A human inuitive name of the web server address to request.
Path: Referral to specific files or directories on the server

## Q6
An html header contains all the information about the page that does not need to be seen.
    <title>:  Sets the name of the webpage as it appears on a browser window
    <link>:  defines relationship between the current page and an external resource
    <meta>:   Specifies meta data on the page such as keywords and character set

## Q7
The CSS Box model is system of layers around an HTML element that can be altered to change how
content is laid out on a page. From Inside to Outside these parts are: Content, Padding, Border, Margin

## Q8
Descendant: combines two selectors if the second has any ancestral element match with the first
    div p {} will select ALL p elements inside div

Child: only combines the second selector if it is a direct descendant of the first
    div > p {} will select only the p elements are a child of div

Adjacent Sibling: combines with equal levels of hierarchy only if they are next to each other
    div + p {} will select the p element that follows div

General Sibling: selects all siblings even if they are not directly adjacent
    div ~ p {} will select all p elements that follow div
    
## Q9 
These paragraphs will be on separate lines. Paragraphs in HTML always begin on a new line.

## Q10
The title attribute should be moved inside the initial anchor tag, with any spacing removed on the end tag.
    <a href="https://bcit.ca" title="bcit"> bcit site </a>