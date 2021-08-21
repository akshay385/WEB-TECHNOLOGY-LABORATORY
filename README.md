# WEB-TECHNOLOGY-LABORATORY
Visvesvaraya Technological University syllabus 📘

## Study Experiment / Project: 💻

**Develop a web application project using the languages and concepts learnt in the theory and exercises listed in part A with a good look and feel effects. You can use any web technologies and frameworks and databases.**

# programming questions 📔
1. **Write a JavaScript to design a simple calculator to perform the following operations: sum, product, difference and quotient**
## EXPLANATION
This program demonstrates the use of embedding Javascript inside a webpage designed using HTML. The usefulness of Java script in client-side computations for small tasks, displaying results in its own graphical window, rendering the output to the web pages dynamically and requesting for input from the user are illustrated through this program** 

2. **Write a JavaScript that calculates the squares and cubes of the numbers from 0 to 10 and outputs HTML text that displays the resulting values in an HTML table format**
## EXPLANATION
This program aims at demonstrating the usefulness of Java script in generating dynamic web pages using Java script. Accepting user input as web page loads is also demonstrate in
this program. This script also illustrates validation using Java script.

3. **Write a JavaScript code that displays text “TEXT-GROWING” with increasing font size in the interval of 100ms in RED COLOR, when the font size reaches 50pt it displays “TEXT-SHRINKING” in BLUE color. Then the font size decreases to 5pt.**
## EXPLANATION
This program brings out the event handling capabilities of Java script. Timer event handling using Java script is explained in this program. Further, the use of style attributes
in HTML and Java script is demonstrated. This program also brings out usefulness of Java script in handling dynamic positioning of elements in HTML page. These give the life to a
web page and make it engaging.


4. **Develop and demonstrate a HTML5 file that includes JavaScript script that uses functions for the following problems:**
* __Parameter: A string__
__Output: The position in the string of the left-most vowel__ <br/>
* __Parameter: A number__
__Output: The number with its digits in the reverse order__
## EXPLANATION
This program demonstrates the structure of HTML5 files and semantic structure followed. Writing of functions in Java script and form based event handling in Java script is
also illustrated. The dynamic processing of Java script without reloading HTML5 pages is also shown.

5. **Design an XML document to store information about a student in an engineering college affiliated to VTU. The information must include USN, Name, Name of the College, Brach, Year of Joining, and e-mail id. Make up sample data for 3 students. Create a CSS style sheet and use it to display the document.**
## EXPLANATION
eXtensible Markup Language (XML) is used in many aspects of web development. It is often used to separate data from presentation. XML does not carry any information about how to be displayed. The same XML data can be used in many different presentation scenarios.Because of this, with XML, there is a full separation between data and presentation. In many HTML applications, XML is used to store or transport data, while HTML is used to format and display the same data. An XML document with correct syntax is called "Well Formed". An XML document validated against a DTD is both "Well Formed" and "Valid". A "Valid" XML document is a "Well Formed" XML document, which also conforms to the rules of a Document Type
Definition (DTD). XML files suffer though from poor usability by nature as they are not friendly to look at in the browser. Hence they are rendered either using CSS or XSLT
(eXtensible Style Sheet Language Transformation from XML to XHTML). CSS does not support new elements to be added or records to be sorted. XSLT is template based and support manipulating contents of XML as well as ordering of XML elements

6. **Write a PHP program to keep track of the number of visitors visiting the web page and to display this count of visitors, with proper headings.**
## EXPLANATION
With server side technologies, server executes the program (PHP) and sends output to browser. This program using PHP gives the most commonly used script in web-site design i.e
keeping track of the number of visitors of a web page. File handling capabilities of PHP also demonstrated

7. **Write a PHP program to display a digital clock which displays the current time of the server.**
## EXPLANATION
This program fetches the current time from the server. The automatic page refreshing ability of PHP programs based on timers is demonstrated. This feature can be exploited in any online exam scenarios which are time bound and server time should be shown continuously.

8. **Write the PHP programs to do the following:**
* **Implement simple calculator operations.**
* **Find the transpose of a matrix.**
* **Multiplication of two matrices.**
* **Addition of two matrices.**
## EXPLANATION
This program is used to demonstrate numerical processing abilities of PHP. The use of scalar variables, functions and multi-dimensional arrays is explored in this program.

9. **Write a PHP program named states.py that declares a variable states with value "Mississippi Alabama Texas Massachusetts Kansas". write a PHP program that does the following:**
* **Search for a word in variable states that ends in xas. Store this word in element 0 of a list named statesList.**
* **Search for a word in states that begins with k and ends in s. Perform a caseinsensitive comparison. [Note: Passing re.Ias a second parameter to method compile performs a case-insensitive comparison.] Store this word in element1 of statesList.**
* **Search for a word in states that begins with M and ends in s. Store this word in element 2 of the list.**
* **Search for a word in states that ends in a. Store this word in element 3 of the list**
## EXPLANATION
This program illustrates the regular expression capabilities in PHP. Writing patterns and matching against a given string is provided. Case sensitive and anchor patterns are explored

10. **. Write a PHP program to sort the student records which are stored in the database using selection sort.**
## EXPLANATION
This program brings out the use of PHP in developing dynamic web pages. The webapplication required follows 3-tier architecture as shown in the figure below. Three tiers include
Presentation logic (HTML with CSS), Business logic (PHP) and Data access (MySQL). The choice of MySQL is because its open source, light weight and platform independent.

# FUNCTIONS/LIBRARIES USED:
The PHP Data Objects (PDO) extension defines a lightweight, consistent interface for accessing databases in PHP. Each database driver that implements the PDO interface can expose database-specific features as regular extension functions. Note that you cannot perform any database functions using the PDO extension by itself; you must use a database-specific PDO driver to access a database server. PDO provides a data-access abstraction layer, which means that, regardless of which database you're using, you use the same functions to issue queries and fetch data. PDO does not provide a database abstraction; it doesn't rewrite SQL or emulate missing features. You should use a full-blown abstraction layer if you need that facility. PDO ships with PHP 5.1, and is available as a PECL extension for PHP 5.0; PDO requires the new OO features in the core of PHP 5, and so will not run with earlier versions of PHP. Connections are established by creating instances of the PDO base class. It doesn't matter which driver you want to use; you always use the PDO class name. The constructor accepts parameters for specifying the database source (known as the DSN) and optionally for the username and password (if any). f there are any connection errors, a PDOException object will be thrown. You may catch the exception if you want to handle the error condition, or you may opt to leave it for an application global exception handler that you set up via **set_exception_handler().**

**new PDO(..) – establish a new connection with specified
credentials query() – Execute specified SQL query
fetch() –fetch result of SQL query record at a time
Output
Preparing Back End(Database):
Creating table in phpmyadmin:
Database:**

# ABOUT XAMP 🔨
**XAMPP (/ˈzæmp/ or /ˈɛks.æmp/[2]) is a free and open source cross-platform web server solution stack package developed by Apache Friends,[2] consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages.[3][4] XAMPP stands for Cross-Platform (X), Apache (A), MariaDB (M), PHP (P) and Perl (P). It is a simple, lightweight Apache distribution that makes it extremely easy for developers to create a local web server for testing and deployment purposes. Everything needed to set up a web server – server application (Apache), database (MariaDB), and scripting language (PHP) – is included in an extractable file. XAMPP is also cross-platform, which means it works equally well on Linux, Mac and Windows. Since most actual web server deployments use the same components as XAMPP, it makes transitioning from a local test server to a live server extremely easy as well.**

# LAB WORKING ENVIRONMENT: 🛠️
**The Web Programming Lab is implemented as Client/Server environment. XAMP software is installed only in a server with an IP Address connected by a LAN with many client machines.For each student a login is created and a folder is created to save the programs and scripts of the students. A login screen is presented, when the student enters URL of
remote machine:**

**Once login is successful, following editor screen is presented:** ▶️

* **Upload – used to upload a file. One should have selected file in the Browse button beside the label Upload File**
* **Compile-Perl – used to compile Perl program**
* **Compile-PHP –used to compile PHP program**
* **View – to view the output of XHTML/Perl/PHP/XML in browser**
* **List – to display list of files belonging to the user**
* **Checkwellformedness – to check whether XML file is well-formed**
* **Validate – to check whether XML confirms to specific DTD**
* **LineNumbers – to display line numbers in the editor textarea**










