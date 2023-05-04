Download Link: https://assignmentchef.com/product/solved-csci203-data-structures-and-algorithms-assignment-02
<br>
<h1 style="padding-left: 30px;">Objectives</h1>

Design and implement a discrete event simulation

Choose and implement appropriate data structures

Adapt standard algorithms to a specific problem

<h1>Task</h1>

You should write a single program which simulates the queuing and service of customers under two different queuing strategies and compare the results.

<h2>Program</h2>

Your program should run two <strong>discrete event </strong>simulations, one for each strategy. Each simulation should start at time 0 and run until all customers have been served. The two queueing strategies are as follows:

<ol>

 <li>Use a single queue from which each server will take the next customer as soon as the server becomesavailable.</li>

 <li>Use a queue for each server. Customers will choose the server with the shortest queue on arrival andwill not move from queue to queue.</li>

</ol>

Your program should be readable and well commented.

<h2>Data Structures and Algorithms</h2>

Part of the purpose of this subject is to gain an in-depth understanding of data structures and algorithms. As such, all programming tasks in this subject require you to <em>choose appropriate data structures and algorithms</em>, and to <em>implement them yourself</em>. You may not take advantage of any built in data structures more complex than an array, but instead should provide your own implementation. The use of STL, Java Collection, or any collection framework in your language of choice, is disallowed. If you use any references other than the lecture notes, ensure you cite them or you may receive 0 for plagiarism. A clear comment in your code is sufficient.

<h2>Readme</h2>

Write a text file named readme. Include clear instructions on how to compile and run your algorithm. Ensure that your program compiles and runs correctly on ubuntu, in the lab. If your program does not compile, it will receive 0 marks. If it doesn’t run according to the specification, you will receive very few marks. You may also include a makefile if you wish.

<h2>Analysis</h2>

Once your program is complete, you should run it for some sample scanarios and examine the results. Write a file named analysis.pdf containing a discussion the differences you observe in statistics between the two queueing strategies. Which strategy is most efficient?

<h1>Input</h1>

Both simulations will use identical inputs. Your program should read a <strong>file name </strong>from <strong>standard input</strong>, and run each simulation using the named file as the input file.

The input file has the following format:

<ul>

 <li>The number of servers.</li>

 <li>A set of lines each consisting of a customer arrival time followed by the corresponding service time.</li>

</ul>

Times are in seconds, from the start of the simulation. Although a sample input file has been provided, your program should still run sucessfully substantially larger inputs.

<h1>Output</h1>

Output should be to standard output.

For each of the two simulations the output should consist of the following data, clearly labelled:

<ul>

 <li>Number of people served.</li>

 <li>Time that the last customer finished being served (total simulation time).</li>

 <li>Average service time (note this should depend only on the input file).</li>

 <li>Average time a customer spends in queue.</li>

 <li>Maximum time a customer spends in queue.</li>

 <li>Average length of queue in any given second. For each queue and in total for the multi-queue version of the simulation.</li>

 <li>Maximum Length of queue. For each queue and in total for the multi-queue version of the simulation.</li>

 <li>Total idle time for each server.</li>

</ul>