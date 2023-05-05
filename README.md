Download Link: https://assignmentchef.com/product/solved-cse222_505-hw6-setmap-hashing-sorting-algorithms-and-performance
<br>
<strong>Q1:</strong>

<ul>

 <li>A is an ordered integer array with 10 elements from small to large</li>

 <li>B is an ordered integer array with 10 elements from large to small</li>

 <li>C = {5, 2, 13, 9, 1, 7, 6, 8, 1, 15, 4, 11}</li>

 <li>D = {‘S’, ‘B’, ‘I’, ‘M’, ‘H’, ‘Q’, ‘C’, ‘L’, ‘R’, ‘E’, ‘P’, ‘K’}</li>

</ul>

Apply the following sorting algorithms for the given arrays.

<ul>

 <li>Shell Sort</li>

 <li>Merge Sort</li>

 <li>Heap Sort</li>

 <li>Quick Sort</li>

</ul>

Show your works step by step and make explanation. Express how many comparisons and how many displacements have been made for each. Write your solution by latex or word and upload it as a <em>StudentNumber.pdf</em> file.

<strong>Q2:</strong>

Implement Quick Sort and Merge Sort algorithms. Suppose the data is stored in a linked list. You should use LinkedList class in Java.

In the book, there are methods for 7 algorithms which are

<ul>

 <li>Selection Sort</li>

 <li>Bubble Sort</li>

 <li>Insertion Sort</li>

 <li>Shell Sort</li>

 <li>Merge Sort</li>

 <li>Heap Sort</li>

 <li>Quick Sort</li>

</ul>

Compare your implementation with the methods in the book. To do this, you must create 100 (20 of each) random and 5 (1 of each) sorted arrays/linked lists with a length of ten thousand (10000), forty thousand (40000), one hundred thousand (100000), one hundred and fifty thousand (150000) and one hundred and eighty thousand (180000). Run all 9 methods for each, save run times and expected run times in excell, and draw graphs for each method. Run times and expected run times should be drawn on the same graphic.

<strong>Q3: </strong>

Design a library automation system. The system has two types of users: administrators who can update information and users who browse books.

Book search is a public feature. To update the information, administrators have to enter the system with a password (a single general password is sufficient).

While designing this system, realize the following: In the system, for each book, the name of the author, the title of the book, the location of the book  (for example, if a book on the 5<sup>th</sup> shelf in the 3r<sup>d </sup>corridor, such as “c3s5.1534” can be used) should be stored. Information about the books should be stored in nested map and set data structures. For the outermost map, the author name is used as a key, the value is another map whose keys are book names. In the inner map, the values are sets showing the location (or locations if there is more than one copy) of that book.

The system should include at least the following functionality:

<ol>

 <li>When searching by author name, all books of the author in the library will be listed on the screen.Then, whichever book the user chooses, the location(s) of that book will be displayed.</li>

 <li>When searching by book title, author name, location and status will be shown.</li>

 <li>When the administrator enters the system with a password, he will be able to add books, deletebooks, update information.</li>

</ol>

<strong>Q4: </strong>

Implement KWHashMap interface in the book using the following hashing methods to organize hash tables:

<ol>

 <li>In chaining is a technique, each table element references a linked list that contains all the items thathash to the same table index. Use chaining with binary tree instead of linked list.</li>

 <li>In open addressing, if the table entry is full, subsequent probe locations are calculated using linearprobing (hash(x) +i) or quadratic probing (hash(x) + i^2) methods. Use an alternative probing method called double hashing where a second hash function is used to calculate subsequent probe locations (hash(x) + i*second_hash(x)).</li>

</ol>

Compare the performance of your implementations with HashTableOpen and HashTableChain classes in the book. Note that you should generate large maps of several entries and perform several random operations to compare the performance of the methods. Report your experimental evaluation using tables and graphs.

<strong>RESTRICTIONS:</strong>

<ul>

 <li>Use only specified data types</li>

 <li>Can be only one main class in each question</li>

 <li>Don’t use any other third part library</li>

</ul>

<strong>GENERAL RULES:</strong>

<ul>

 <li>For any question firstly use course news forum in Moodle, and then the contact TA.</li>

 <li>You can submit assignment one day late and will be evaluated over sixty percent (%40).</li>

</ul>

<strong>TECHNICAL RULES:</strong>

<ul>

 <li>Use given CSE222-VM to develop and test your Homeworks (your code must be working on CSE222-VM), CSE222-VM download link will be given on Moodle.</li>

 <li>Implement <a href="https://www.google.com.tr/search?q=clean+code+standart&amp;oq=clean+code+standart&amp;aqs=chrome..69i57j0.3015j0j4&amp;sourceid=chrome&amp;es_sm=122&amp;ie=UTF-8">clean code standards</a> in your code; o Classes, methods and variables names must be meaningful and related with the functionality.</li>

</ul>

o Your functions and classes must be simple, general, reusable and focus on one topic. o Use standard <a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">java code name conventions</a><a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">.</a>

<strong>REPORT RULES:</strong>

<ul>

 <li>Add all <a href="http://www.oracle.com/technetwork/articles/java/index-137868.html">javadoc</a> documentations for classes, methods, variables …etc. All explanation must be meaningful and understandable.</li>

 <li>You should submit your homework code, Javadoc and report to Moodle in a</li>

</ul>

“studentid_hw3.tar.gz” file.

<ul>

 <li>Use the given homework format including selected parts from the table below:</li>

</ul>

Detailed system requirements

Use case diagrams (extra points)

Class diagrams                                                                          X

Other diagrams

Problem solutions approach                                                     X

Test cases