Download Link: https://assignmentchef.com/product/solved-cs39002-assignment-1-familiarization-with-shell-scripting
<br>
<strong>Assignment 1: </strong>Familiarization with shell scripting (commands like awk, grep, sed, sort, cat)

<ol>

 <li>Write programs in shell script under the Linux environment that would run in bash terminal and perform the following Tasks.</li>

</ol>

<h1>1.a. Simple calculator</h1>

<ul>

 <li>Take in three arguments: first is an integer, separated by a space second argument is any one of the following operators: addition (+), Subtraction (-), Multiplication (*), Division (/) and Modulo (%), third argument is again an integer. Compute and print the expression created by argument 1, argument 2, argument 3.</li>

 <li>Name your shell script “Assgn1_1a_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

 <li>Example input: Assgn1_1a_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh 1 + 2 Example output: 3</li>

</ul>




<h1>1.b.  Adding line numbers and headers</h1>

<ul>

 <li>You have a text file with around 500,000 lines (download from <a href="https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1b_input.txt">https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1b_input.txt</a><a href="https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1b_input.txt">)</a>:</li>

 <li>Write a shell script which will read this file and add line numbers to the beginning of each line. These line numbers should be followed by spaces. Also add the following headers in the two columns of the new file: “Serial”, “Random string”</li>

 <li>Name your shell script “Assgn1_1b_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

</ul>




<h1>1.c. Finding GCD</h1>

<ul>

 <li>Write a shell script which will take less than 10 integers and output their GCD.</li>

 <li>Name your shell script “Assgn1_1c_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

 <li>Example input: Assgn1_1c_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh 4,8,16,56 Example output: 4</li>

</ul>




<h1>1.d. Sorting and merging large number of files</h1>

<ul>

 <li>You are given a folder with hundreds of text files (download from here and unzip):</li>

</ul>

<a href="https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1.d.files.zip">https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1.d.files.zip</a>

<ul>

 <li>You need to sort each of these individual files in decreasing order, write the sorted files in a new “1.d.files.out” folder (keep the name same), and then merge these individual sorted files into a single sorted file (name it “1.d.out.txt”) which is sorted in decreasing order. Write a shell script which will iterate over the given files and perform this task.</li>

 <li>Name your shell script “Assgn1_1d_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

</ul>




<h1>1.e. Creating frequency distribution from a large file</h1>

<ul>

 <li>You have a text file with around 1.5 million lines (download from <a href="https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1e_input.txt.zip">https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1e_input.txt.zip</a> and unzip)</li>

 <li>This text file has four space-separated columns, example of three lines from the file:</li>

</ul>

1 ib Jim 34

1 cr JoHn 24

1 ut MaRY 46




<ul>

 <li>Write a shell script which will take two inputs: (i) the input file, and (ii) a column number as a user provided input (varies from 1 to 4). For that column number the code will read entries of that column from the input file (e.g., in case of column number 3 as input the entries will be Jim, JoHn, MaRY), and convert these entries to lower case.</li>

 <li>Finally the script should create a file “1e_output _&lt;column_number&gt;_column.freq”. This file will have two columns: first is a string (converted to lowercase) from the given column and second is the frequency of that string. Sort the “1e_output _&lt;column_number&gt;_column.freq”. The file should be sorted in decreasing order of the second column values (i.e., frequency).</li>

 <li>Name your shell script “Assgn1_1e_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

</ul>




<h1>1.f. Cleaning up graphs</h1>

<ul>

 <li>You have a large graph (around 5 million edges) as edgelist (download it from <a href="https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1f.graph.edgelist.zip">https://cse.iitkgp.ac.in/~mainack/OS/assignments/01/1f.graph.edgelist.zip</a> and unzip).</li>

 <li>In the graph there are n nodes which are labeled as integers. In the file a line “n1 n2” means that there is an undirected edge between nodes labeled n1 and n2</li>

 <li>Now, write a shell script that will take your graph as input and remove (i) self-edges (i.e, lines like” 345 345”) (ii) duplicate edges (i.e. if “2 1” exists, then “1             2” should not exist) and finally, (iii) parallel edges (i.e., there should be only unique edges in the file)</li>

 <li>Your script should write the new clean output graph in a file named “1f_output_graph.edgelist”</li>

 <li>Finally your code should then parse the new “1f_output_graph.edgelist” and print out 5 nodes which have highest undirected degree and their corresponding undirected degrees. Each node should be printed on a separate line as follows:</li>

</ul>

&lt;node_with_higest_degree&gt; highest_degree_in_the_graph

&lt;node_with_second_higest_degree&gt; second_highest_degree_in_the_graph

…

…

<ul>

 <li>Name your shell script “Assgn1_1f_&lt; groupno&gt;_&lt;roll no. 1&gt;_&lt; roll no. 2&gt;.sh”</li>

</ul>