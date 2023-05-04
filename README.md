Download Link: https://assignmentchef.com/product/solved-cs69012-assignment8-web-crawling-and-extracting-information-part1
<br>



This assignment is on crawling web pages and extracting the required information from them by creating suitable grammar rules.

<h1>Task 1 (Crawling RottenTomatoes website)</h1>

<ol>

 <li>RottenTomatoes is an IMDb like website, where you can find an online database of information related to films, television programs, including cast, production crew, personal biographies, plot summaries, trivia, ratings, critic and fan reviews.</li>

 <li>You are provided with a file named “rotten tomatoes movie genre link.txt,” which contains URL links for ten different genre-wise top 100 movie lists.</li>

 <li>Write a python code that reads each of the URLs, saves the pages in HTML format.</li>

 <li>Now given a user input of any of the ten genres, you should list all the movies in that list and wait for user input of a particular movie name from the list.</li>

 <li>Given a movie name as the input, you should download and save the corresponding movie page’s HTML file.</li>

</ol>

<strong><u>Refer: </u></strong><a href="https://programminghistorian.org/en/lessons/working-with-web-pages"><em>https://programminghistorian.org/en/lessons/working-with-web-pages</em></a>

<h1>Task 2 (Creating grammar and parsing the files)</h1>

<ol>

 <li>After saving movie pages in HTML format, try to study the syntax of HTML files.</li>

 <li>Create grammar that can be used to extract the following fields for the movies.

  <ul>

   <li>Movie Name</li>

   <li>Director</li>

   <li>Writers</li>

   <li>Producer</li>

   <li>Original Language</li>

   <li>Cast with the character name</li>

   <li>Storyline</li>

   <li>Box Office Collection</li>

   <li>Runtime</li>

  </ul></li>

 <li>You can ignore other fields except the above.</li>

 <li>Write (python code using PLY) or (C code using Lex,Yacc) to extract the above fields. Your program should show all the possible query fields a user can ask for(from the above list items). And according to the user selection, it should show the corresponding field for the particular movie.</li>

 <li>Your program should also save the result in a log file as per the following format. &lt;Genre&gt; &lt;Movie_name&gt; &lt;Field_requested&gt; &lt;Field_value&gt;</li>

</ol>

For a field with multiple values, it should make an entry for each value.

<ol start="6">

 <li>You have to think correctly about what kind of errors can come in the process and try to handle them. Note that you can not use the “Beautiful Soup” python package for this assignment. <strong>Use the ply package in python / Or you can code in C using lex and yacc.</strong></li>

</ol>

<strong>Refer: </strong><a href="http://www.dabeaz.com/ply/">http://www.dabeaz.com/ply/</a>

<strong>Deliverables: </strong>codes for task1 and task2